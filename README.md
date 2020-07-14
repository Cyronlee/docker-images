# 常用Docker镜像
## 构建方法
. 使用当前目录的 Dockerfile 创建镜像，-t 设置名称及标签为 name:tag
```bash
docker build -t name:3.5.2 .
```
使用 URL 的 Dockerfile 创建镜像
```bash
docker build https://github.com/Cyronlee/docker-images/tree/master/esbot-python
```
也可以通过 -f 指定 Dockerfile 文件的位置
```bash
docker build -f /foo/bar/Dockerfile .
```
# esbot-python
依赖项
```
rasa-nlu == 0.13.4
rasa-core == 0.12.3
rasa-core-sdk == 0.12.1
jieba == 0.39
scikit-learn == 0.19.2
scipy == 1.2.1
sklearn-crfsuite == 0.3.6
tensorflow == 1.10.0
keras == 2.2.4
```
构建
```bash
docker docker build -t env:3.5.2 .
```
# jdk8-font
使用北京时间，引入中文字体

构建
```bash
docker docker build jdk8-font .
```
