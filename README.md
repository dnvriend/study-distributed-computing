# study-distributed-computing
A study project on distributed computing

## Introduction

## Design Patterns

## Hash

## Consistent Hash Ring

## MEP: Request - Reply

## MEP: Pub - Sub

## Merkle Tree

## Consensus Algorithms - RAFT

## Vector Clocks
- A means of proving sequence
- Not a means of telling the time

__Pro:__
- Vector clocks cannot be wrong (Last Write Wins can be wrong)

__Cons:__
- Push complexity into the client
- Does time (precision) matter?

## Conflict Resolution
If you've got a vector clock conflict, the conflict must be resolved
either automatically or manually (user decision).

## Papers
- [Amazon Dynamo Paper](http://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)

## Resources
- [DS201: DataStax Enterprise Foundations of Apache Cassandra](https://academy.datastax.com/resources/ds201-foundations-apache-cassandra)

## Blogs
- [Why Vector Clocks are Easy - Basho](http://basho.com/posts/technical/why-vector-clocks-are-easy/)
- [Why Vector Clocks are Hard - Basho](http://basho.com/posts/technical/why-vector-clocks-are-hard/)
- [Why Cassandra Doesn't Need Vector Clocks - DataStax](https://www.datastax.com/dev/blog/why-cassandra-doesnt-need-vector-clocks)

## Youtube
- [(0'32 hr) A Brief History of Logical Time - John Daily](https://www.youtube.com/watch?v=b_swtL5bxJg)
- [(0'41 hr) Distributed Patterns you should know - Eric Redmond](https://www.youtube.com/watch?v=otWvr8VBRx0)
- [(0'42 hr) How to Have your Causality and Wall Clocks, Too - Jon Moore](https://www.youtube.com/watch?v=YqNGbvFHoKM)
- [(0'12 hr) Vector Clocks Distributed Systems in One Lesson](https://www.youtube.com/watch?v=IT5AqUEGLwM)