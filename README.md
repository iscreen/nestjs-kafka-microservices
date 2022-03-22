# NestJS Kafka MicroServices

This is a NestJS microservice via Kafka sample code.

[API Gateway] -- order created -> [Billing] -- get user --> [Auth]

## Start Kafka

```bash
cd docker-commpose
docker-compose up -d
```

## Configuration

### Add Submodules

1. Add submodules  

  ```bash
  git submodule add git@github.com:iscreen/nestjs-microservice-api-gateway.git api-gateway
  git submodule add https://github.com/iscreen/nestjs-microservice-auth auth
  git submodule add https://github.com/iscreen/nestjs-microservice-billing billing
  ```

2. Install Packages  

  ```bash
  cd api-gateway && yarn install
  ```

  ```bash
  cd billing && yarn install
  ```

  ```bash
  cd auth && yarn install
  ```

## References

* [NestJS Microservices](https://www.youtube.com/watch?v=JJEKPqSlXvk)  
* [Youtubu](https://www.youtube.com/watch?v=JJEKPqSlXvk)  
  