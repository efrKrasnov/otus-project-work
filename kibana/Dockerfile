ARG ELASTIC_VERSION
ARG KIBANA_DOCKER_HUB
# https://www.docker.elastic.co/
FROM ${KIBANA_DOCKER_HUB}kibana:${ELASTIC_VERSION:-8.17.0}

# Add your kibana plugins setup here
# Example: RUN kibana-plugin install <name|url>