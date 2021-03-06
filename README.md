TwitterStorm_TwitterWorkCountTopology
=====================================

Twitter Storm Topology to count words in the incoming tweet stream.

This project is derived from https://github.com/davidkiss/storm-twitter-word-count to be used in my student project.

The code subscribes to Twitter's Sample feed, keeps stats on words occuring in tweets and logs top list with of words with most count in every 10 seconds.

This project contains a simple storm topology that connects to the sample stream of the Twitter Streaming API and keeps stats on words occuring in tweets and prints top list of words with highest count in every 10 seconds.

To get started:

Clone this repo
Import as existing Maven project in Eclipse
Run Topology.java with your twitter credentials as VM args (see http://twitter4j.org/en/configuration.html#systempropertyconfiguration)
You'll need to have valid Twitter OAuth credentials to get the sample working. For the exact steps on how to do that, visit https://dev.twitter.com/discussions/631.
