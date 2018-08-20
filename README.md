# docker-circleci-php
Customized PHP image for CircleCI

Customized from the php71-browser image in [CircleCI's image repo](https://github.com/circleci/circleci-images)

# Updating the DockerHub image:

In this directory:

```
docker build -t alavida/circleci-php .

docker login   (<-- as alavida)

docker push alavida/circleci-php
```


