git clone git@github.com:mosip/mosip-infra.git
git checkout tags/v1.2.0.1-B3

minikube config set memory 8192
minikube config set cpus 4
minikube start --force