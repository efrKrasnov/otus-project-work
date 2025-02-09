ARG ELASTIC_VERSION
ARG ELASTIC_DOCKER_HUB
# https://www.docker.elastic.co/
FROM ${ELASTIC_DOCKER_HUB}elasticsearch:${ELASTIC_VERSION:-8.17.0}

ENTRYPOINT ["/entrypoint.sh"]