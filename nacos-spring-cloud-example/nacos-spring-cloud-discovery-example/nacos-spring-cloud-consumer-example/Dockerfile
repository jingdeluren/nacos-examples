FROM swr.cn-east-3.myhuaweicloud.com/op_svc_cse/openjdk-x86_64:17-1.2.0
WORKDIR /home/app/
ADD nacos-spring-cloud-consumer-example/target/nacos-spring-cloud-consumer-example-0.2.0-SNAPSHOT.jar .
ENTRYPOINT ["java","-jar","-Xmx2048m","./nacos-spring-cloud-consumer-example-0.2.0-SNAPSHOT.jar"]
