# IIS for Training
This is a Dockerfile to generate a MS IIS that sends its logging information to STDOUT. Note IIS flushes the log every 60sec or every 64kB.


Inspired by: [https://blog.sixeyed.com/relay-iis-log-entries-to-read-them-in-docker/](https://blog.sixeyed.com/relay-iis-log-entries-to-read-them-in-docker/)
