based on
https://github.com/Semantive/docker-spark
http://datastrophic.io/core-concepts-architecture-and-internals-of-apache-spark/


docker-compose start
doceer-compose stop

docker exec -it <master> /bin/bash
--> spark-shell 

or in another computer
spark-shell --master spark://localhost:7077
spark-shell --master spark://<docker-host-ip>:7077


