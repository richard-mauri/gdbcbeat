# gdbcbeat
A custom elastic beat to query from oracle,mssql and ship data to supported libbeat outputs.

This is an experimental Elastic beat that can perform jdbc-like queries against mssql first and oracle next, and convert the resultset to beat events that can be shipped to your favorite output like logstash, elasticsearch, etc.

It is an alternative to using logstash and jdbc input plugin https://www.elastic.co/guide/en/logstash/current/plugins-inputs-jdbc.html

There are several blogs and git repos to help us get started. Here are a few links:

* https://www.quackit.com/sql_server/mac/install_sql_server_on_a_mac.cfm
* https://bsilverstrim.blogspot.com/2015/08/golang-and-mssql-databases-example.html
* https://github.com/godror/godror

Ideally, this repo wil include a vm and test ci system that will help demonstrate and qualify the beat.
This should also be available as an Elastic referenced community beat.
https://www.elastic.co/guide/en/beats/libbeat/current/community-beats.html


