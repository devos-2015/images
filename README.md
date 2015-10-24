# images

Custom builds of some Docker images we use

## consul

This version of consul starts with CORS enabled.

~~~ sh
docker build -t consul-cors .
docker tag consul-cors 46.101.193.82:5000/consul-cors:latest
docker push 46.101.193.82:5000/consul-cors:latest
~~~
