# fluentd configured to send logs to elasticsearch

## configuration

Update lines 10 and 11 in `fluent.conf` file. These are additional fields
you would like to see in kibana. If not needed, the whole section `filter`
can be removed.

Update line 19 with hostname where the elasticsearch is running.

## run
`docker-compose up -d`