# Kiss Metrics Log File Processor - km-send

This utility mimics the km ruby gem which processes a log file generated by the km gem in a ruby
application.  It takes each line and sends it to the Kiss Metrics server.

Unlike the ruby version of km-send, this has a couple of optional arguments.  Use "-h" for
details.

To use the utility, build the build/km-send.jar file and run it thus:

  java -jar km-send.jar -h
  
If an output directory is specified on the command line it will also write each successful event
to an archive file which can be used to replay the events.

Author: Bill Kayser, New Relic, Inc. copyright (c) 2012