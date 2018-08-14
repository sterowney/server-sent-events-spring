siege -c50 -t60s -H 'Content-Type: application/json' 'http://localhost:8080/messages POST'

./kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic messages