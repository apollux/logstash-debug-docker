# What?
Provides configuration to create a debug environment for logstash filters.

# Usage
`docker run --rm -v <path to workspace>/config:/usr/share/logstash/config -v <path to workspace>pipeline:/pipeline -v <path to workspace>/input:/input docker.elastic.co/logstash/logstash:6.0.0`
NOTE: on Windows remember to start with lowercase drive letter and use forward
slashes: `c:/path/to/workspace/pipeline`
