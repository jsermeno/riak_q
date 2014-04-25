# riak_q
========

I got tired of typing out curl commands everytime I want to use HTTP to query riak.

```
ls_b                                    list all buckets
ls_k <bucket>                           list all keys
k <bucket> <key>                        find key
b_props <bucket>                        list bucket properties
put_b_backend <bucket> <backend>        set backend for a bucket
d_b <bucket>                            delete all keys from bucket (be careful!)
