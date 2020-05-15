# elasticsearch-bitbucket-pipelines
Use elasticsearch in development mode in bitbucket-pipelines

Elasticsearch [requires the discovery.type environment variable to be run in dev mode.](https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html#docker-cli-run-dev-mode)

As of May 2020, [Bitbucket still does not support variable names with periods in them.](https://jira.atlassian.com/browse/BCLOUD-18007)

This packages that environment variable with the official elasticsearch 7.7.0 image.
