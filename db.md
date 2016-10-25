## Shard
A database shard is a horizontal partition of data in a database or search engine. Each partition is a database shard. Horizontal partitioning is a database design principle whereby rows of a database table are held separately, rather than being split into columns. Each of these partitions is a "shard".

# Elasticsearch

## Lucene 
Apache Lucene. A search engine library or "Information retrieval software library" if you want to get fancy with words.

## Shard in Elasticsearch
A shard is a single Lucene instance. It is a low-level worker unit managed by elasticsearch. An index is a logical namespace pointing to primary and replica shards. 

Elasticsearch distributes shards amongst all nodes in the cluster. It can move these shards automatically from one node to another in case of node failure. 

## MySQL vs postgresQL
