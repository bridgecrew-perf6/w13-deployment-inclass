
# 透過 GithHub Action build & deploy image to DockerHub
可以參閱 [main-dockerhub.yml](https://github.com/chgc/w13-deployment-inclass/blob/main/.github/workflows/main-dockerhub.yml)
或是閱讀此[文件](https://docs.github.com/en/actions/publishing-packages/publishing-docker-images#publishing-images-to-docker-hub)


## secrets 設定
```
username: ${{ secrets.DOCKER_USERNAME }}
password: ${{ secrets.DOCKER_PASSWORD }}
```         

可到 settings 的地方設定設定 Secrets -> Actions -> New repository secret
新增 DOCKER_USERNAME 和 DOCKER_PASSWORD 並將對應的值更新進去
