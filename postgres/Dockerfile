ARG POSTGRES_VERSION

FROM postgres:${POSTGRES_VERSION}

RUN localedef -i sk_SK -c -f UTF-8 -A /usr/share/locale/locale.alias sk_SK.UTF-8

ENV LANG sk_SK.utf8