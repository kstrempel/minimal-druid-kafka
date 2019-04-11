helm install --name zookeeper incubator/zookeeper --values zookeeper/values.yaml

helm install --name kafka incubator/zookeeper --values kafka/values.yaml
