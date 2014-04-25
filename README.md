# riak_q
========

I got tired of typing out curl commands everytime I want to use HTTP to query riak.

```
riak_q ls_b                                    list all buckets
riak_q ls_k <bucket>                           list all keys
riak_q k <bucket> <key>                        find key
riak_q d <bucket> <key>                        delete key
riak_q b_props <bucket>                        list bucket properties
riak_q put_b_backend <bucket> <backend>        set backend for a bucket
riak_q d_b <bucket>                            delete all keys from bucket (be careful!)
```

I might add more functionality as I find I need it. Feel free to help!
