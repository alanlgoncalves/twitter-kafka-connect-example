# TWITTER-KAFKA-CONNECT-EXAMPLE

This project is a sample of how to use [kafka-connect-twitter](https://github.com/jcustenborder/kafka-connect-twitter)

## How to run the project?

Update all the configuration file `twitter.properties`

| Name                            | Description                                       | Type     | Default | Valid Values | Importance |
|---------------------------------|---------------------------------------------------|----------|---------|--------------|------------|
| filter.keywords                 | Twitter keywords to filter for.                   | list     |         |              | high       |
| twitter.oauth.accessToken       | OAuth access token                                | password |         |              | high       |
| twitter.oauth.accessTokenSecret | OAuth access token secret                         | password |         |              | high       |
| twitter.oauth.consumerKey       | OAuth consumer key                                | password |         |              | high       |
| twitter.oauth.consumerSecret    | OAuth consumer secret                             | password |         |              | high       |

After configure, just runs `./run.sh`
