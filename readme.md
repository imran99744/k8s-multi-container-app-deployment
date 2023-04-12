docker build -f Dockerfile.dev -t imran19977/multi-client .

docker run -it -p 3000:3000 imran19977/multi-client


docker build -f Dockerfile.dev -t imran19977/multi-server .

docker run -it -p 5000:5000 imran19977/multi-server

docker push imran19977/multi-client:latest