sudo docker run -it --rm -d -p 8080:80 --name web webserver

sudo docker build -t webserver .

sudo k3s kubectl apply -f hello-world-lb.yaml

sudo k3s kubectl apply -f hello-world-deployment.yaml
