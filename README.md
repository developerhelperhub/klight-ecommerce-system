# Build the maven module "klight-ecommerce-system"

We have to build the maven module initial time / whenever any changes happen on the module. Following command install module into maven local repository `com.developerhelperhub.klight.microservices:klight-ecommerce-system:1.0.0-SNAPSHOT`. 

Note: We have build this maven module before build child module if we have any change in the main module. We have to configure the CICD pipeline accordingly
```shell
cd klight-ecommerce-system/

mvn clean install
```

Note: clean all modules of developerhelperhub from maven repository
```shell
rm -rf ~/.m2/repository/com/developerhelperhub/
```