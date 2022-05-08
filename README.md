# spring-petclinic-msa

微服务spring-petlinic Kubernetes版

<img src="doc/images/micro-service_petclinic_arch.png" alt="aliyun k8s deploy arch" style="zoom:80%;" />

本地镜像构建

```shell
mvn clean install
```

镜像构建+上传dockerhub

```shell
mvn clean deploy
```

**镜像相关配置可以在父pom.xml中进行修改**

# 在本地部署spring-petclinic

```shell
kubectl apply -f k8s/local/.
```

<img src="doc/images/local_k8s_deploy_arch.png" alt="aliyun k8s deploy arch" style="zoom: 80%;" />