FROM debian

RUN set -x \
    && apt-get -qq update \
    && apt-get -qqy install curl \
    && apt-get install -qqy apt-transport-https apt-utils \
    && apt-get -qq update \
    && apt-get install -qqy \
        git \
        sudo \
        wget

RUN set -x \
    && curl -sL https://deb.nodesource.com/setup_11.x | bash \
    && apt-get install nodejs -qy

RUN set -x \
    && npm install --silent -g \
        gulp-cli \
        grunt-cli \
        bower \
        eslint \
        webpack-cli

RUN set -x \
    && echo "cd /src"

VOLUME /src
WORKDIR /src

CMD /bin/bash