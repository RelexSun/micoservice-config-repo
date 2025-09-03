# Example structure of my environment repository

Below is just an example of a microservice environment repository and every subdir grouped all environment profiles based on each services.
<br></br>

```bash
config-repo/
├── application.yml                 # global defaults
├── eureka-server/
│   ├── application.yml             # base config for eureka server
│   ├── application-dev.yml
│   ├── application-prod.yml
├── order-service/
│   ├── application.yml             # base config for order service
│   ├── application-dev.yml
│   ├── application-prod.yml
├── user-service/
│   ├── application.yml
│   ├── application-dev.yml
│   ├── application-prod.yml

```
