[![Build Status](https://travis-ci.org/vegasbrianc/docker-pulls.svg?branch=master)](https://travis-ci.org/vegasbrianc/docker-pulls)

# docker-pulls
This is a docker-compose file that can be used with the [Prometheus Project](https://github.com/vegasbrianc/prometheus).

The compose file adds the container [Docker Hub Exporter](https://hub.docker.com/r/infinityworks/docker-hub-exporter) which tracks the image metrics pulls and stars for the selected images. 

Additionaly, the prometheus.yml file has also been updated to include the new metrics service to be added as a Prometheus Target.
