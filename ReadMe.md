#Real Time BigData Processing UseCases

| Module                   | Description                                                                                                                                                                                  |
| ------                   | -----------                                                                                                                                                                                  |
| log_events_processing    | processes apache log events <br> *components involved*: storm, kafka, logstash, cassandra                                                                                                    |
| index_tweets_solr        | fetches tweets from twitter streaming api and indexes them to solr <br> *components involved*: solr, solrj, twitter4j                                                                        |
| index_logs               | scala application to interface with solr to generates and index apache http log events as well as provide a naive query interface <br> *components involved*: solr, solrj, solr-scala-clinet |
| LogEventsProcessingSpark | processes apache log events using spark streaming <br> *components involved*: spark, kafka, cassandra                                                                                        |
