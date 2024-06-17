# SkillFactory-B9-JFrog-Artifactory-MAIN

## [Roles](https://github.com/LanchSloth/B9-Roles.git)



$${\color{yellow}yandex_cloud.ini}$$

```
[artifactory]
morsh-server-centos-7 ansible_host=158.160.53.202 ansible_user=morsh-admin

```

$${\color{yellow}pip.ini|pip.conf}$$

```
[global]
index-url = http://morsh-repo-user:<key>@158.160.53.202:8081/artifactory/api/pypi/pypi-remote/simple
```

$${\color{yellow}.pypirc}$$

```
[private-repository]
repository: http://158.160.53.202:8081/artifactory/api/pypi/pypi-local
username: morsh-repo-user
password: <password>
```
*py setup.py sdist upload -r private-repository*


* [x] - :five: Отправить ментору конфигурационный файл pip.conf, настроенный для работы с Artifactory в качестве репозитория (вместо стандартного pipy.org), и ссылку на Artifactory, развернутую на вашей машине. Интерфейс должен быть доступен из интернета.

# [MyAwsomeJfrog](http://158.160.53.202:8082)

