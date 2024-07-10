## KVStore

Distributed Key Value Store Implmentation in Golang (Work In Progress)

Inspired by MIT 6.824 Distributed Systems Lab, this is my implementation of Distributed Key Value Store in Golang.
Implemented the Raft consensus algorithm including Leader Election, Log Replication and Compaction
Implemented a Key Value Service which uses the above Raft Layer to achieve Fault tolerance.

Currently, this is Work In Progress, you can refer to MIT Labs solution for raft implementation [link](https://github.com/sunkadshreyas/6.824)

# Things to Do

- [ ] Key Value Store with HTTP Server
- [ ] Leader Election
- [ ] Log Replication and Compaction