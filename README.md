# gcr.io
for gcr.io images

编写Dockerfile，然后提交到Github。Dockerfile只需用一行代码：
也就是你要真正拉取的镜像名称，把该镜像作为一个基础镜像即可。

使用Docker Hub的Automated Build来进行构建，把自动构建的仓库设置为Github的仓库地址即可。

选择自动构建
然后在右侧选择你在Github中gcr仓库地址即可,
然后Docker Hub就会帮你自动构建了,
目前该镜像的仓库地址为：https://hub.docker.com/r/chenyufeng/gcr/
可以直接通过以下命令拉取：
docker pull zhoulf1006/gcr.io


通过以上命令拉取的镜像其实就是一开始被墙的“gcr.io/google_containers/<imagename>”镜像。其他的镜像也可以通过该种方式替代。
