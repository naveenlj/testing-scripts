testing-scripts
===============

aws/

Two scripts for auditing S3 permissions/access and Security Groups. Requires AWS client setup.

vulnquery/

Uses web page fetches to look up CVEs for a given Apache version for example. Requires running memcached, so we don't hammer the server.

mallory2cap/

Reads in a Mallory SQLite database file and writes a pcap file call using "python mallory2cap.py file.sql output.pcap"
