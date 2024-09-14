# Machine_Learning
记录自学机器学习,希望能坚持下去！
## 环境配置
### 1.安装miniconda
官网下载适合操作系统的miniconda，执行如下命令,-b表示默认选择所有参数，关闭交互式

```sh Miniconda3-py39_4.12.0-MacOSX-x86_64.sh -b```
### 2.安装后的miniconda路径添加到PATH中
mac:.bash_profile.sh  
    ```export PATH="/Users/xxxxx/miniconda3/bin:$PATH"```
### 3.导入miniconda的路径
```source ~/.bash_profile```
### 4.初始化终端shell
 ```~/miniconda3/bin/conda init # 初始化终Shell```
### 5.创建环境
创建一个名为"d2l"的新环境，并在这个环境中安装Python 3.9版本

```conda create --name pyml python=3.9 -y```
### 6.激活环境
```conda activate pyml # 激活环境```