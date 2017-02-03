
Build N-grams based on several .txt files.





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
| ability         | in             |     4 |
| ability         | to             |     4 |
| able            | to             |     5 |
| about           | the            |    72 |
| about           | his            |    31 |
| above           | all            |    12 |
| above           | and            |     6 |
| above           | the            |     6 |
| aboven          | ev             |     4 |
| absence         | of             |    10 |
| absolon         | that           |     4 |
| academy         | of             |     5 |
| access          | to             |    21 |
| accordance      | with           |     5 |
| accordant       | to             |     5 |
| according       | to             |    33 |
| account         | of             |    17 |
| accounts        | of             |     4 |
| acquaintance    | with           |     4 |
| acquainted      | with           |     4 |
| across          | the            |     4 |
| action          | and            |     6 |
| active          | links          |     4 |
| addition        | to             |     6 |
| additional      | terms          |     4 |
+-----------------+----------------+-------+


Details and walkthrough can be found:
https://quip.com/RGlDA4SUtlat


