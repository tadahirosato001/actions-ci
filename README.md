# actions-ci
  
#### Github Actions Workflowにて、nginxコンテナのビルド、imageをGithub Pakage RegistoryへのPushを行う。


### 1. 構成

```
./github
└── workflows
    └── test.yml
./
├── docker
    ├── Dockerfile
    └── Makefile
└── docker-compose.yml
```