
#Build N-grams based on several .txt files.





After mapreduce jobs finish successfully, N-grams will be stored in table output of database test in MySQL.

mysql> select * from output limit 30;

+-----------------+----------------+-------+

| starting_phrase | following_word | count |

+-----------------+----------------+-------+

| a               | man            |   263 |

| a               | little         |    90 |

| abash           | d              |     4 |

| abide           | and            |     7 |

| ability         | and            |     6 |

...

Details and walkthrough can be found:
https://quip.com/RGlDA4SUtlat


