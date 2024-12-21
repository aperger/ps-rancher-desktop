# Installation
1st step to create Secrets with name 'postgres-secrets' which conatins the password of `postgres` user

kubectl create secret generic postgres-secrets --from-literal='postgres_password=Passw0rd'