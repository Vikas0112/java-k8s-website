### Java Website with Jenkins + Kubernetes

#### Run locally
mvn spring-boot:run

#### Build Docker
docker build -t java-website .

#### Kubernetes deploy
kubectl apply -f k8s/

#### CI/CD
Push code to GitHub → Jenkins auto builds → K8s auto deploys
