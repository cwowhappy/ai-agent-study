# ai-agent-study

AI Agent学习仓库，基于LangChain实践

## 本地环境安装
### Python开发环境安装
#### 第一步：安装anaconda
anaconda是一个Python环境管理工具，具体安装步骤：在官网下载对应的安装包，本地执行安装
#### 第二步：创建Python环境
具体指令：
```shell
conda create -n ai-agent python=3.12

conda activate ai-agent
```
#### 第三步：使用anaconda安装langchain
具体指令：
```shell
# 安装langchain基础库：
conda install langchain -n ai-agent -c conda-forge
# 安装langchain附加库：
conda install langchain-community -n ai-agent
```
常用库介绍
|python库|作用|备注|
|--|--|--|
|langchain|||
|langchain-community|||

其它
#### 第三步：使用anaconda安装jupyter
具体指令：
```shell
conda install jupyterlab -n ai-agent -c conda-forge
```
运行jupyter：`nohup jupyter lab > jupyter-lab.log 2>&1 &`

### 本地模型安装
#### 第一步：安装ollama
具体指令：`brew install ollama`

### 参考文档
