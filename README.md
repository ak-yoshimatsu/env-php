# phpが動く環境をdockerで構築
+ ディレクトリ構成（参考サイト：[https://qiita.com/ucan-lab/items/56c9dc3cf2e6762672f4](https://qiita.com/ucan-lab/items/56c9dc3cf2e6762672f4)）

```
.
├── README.md 
├── docker-compose.yml
├── mysql
│   ├── Dockerfile
│   └── my.cnf
├── nginx
│   └── default.conf
├── php
│   ├── Dockerfile
│   └── php.ini
└── .env (※.gitingore)
```