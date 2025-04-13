# squid
squid proxy


curl http://sample_squid:3128
docker network ls
docker network inspect shared_network
docker exec -it my-ubuntu bash
curl -x http://localhost:3128 https://google.co.jp
curl --proxy http://sample_squid:3128 https://google.co.jp
curl -x http://sample_squid:3128 https://google.co.jp
ping sample_squid


curl: (6) Could not resolve host: sample_squid
docker-compose.ymlでのサービス間の通信に関する追加の設定が必要な可能性があります。
service間の疎通が必要かもしれない。