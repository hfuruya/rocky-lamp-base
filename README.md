# rocky-lamp-base

rocky-lamp-base is base infrastructure with php(v8.1), mysql(v5.7), memcache(v1.6) based on Rocky Linux 9.

# Features

This base uses Rocky Linux, one of the leading OS next to CentOS.

# Requirement

* Docker Desktop 4.19.0

# Installation

https://docs.docker.com/desktop/release-notes/

# Usage

```bash
git clone https://github.com/hfuruya/rocky-lamp-base
cd rocky-lamp-base/docker
docker-compose -p {your-project-name} up -d
```

Please access the following URL.
http://localhost:9081

# License

[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/mit-license.php)
