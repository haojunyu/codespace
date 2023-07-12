# 代码空间

## 背景

写了很多代码，学了不少语言，如何系统化的整理自己的代码。

## 涉及领域
### 内功
#### 刷题

#### 算法

#### 设计模式

### 外功
#### 基础库

#### 项目研读

#### 自研小黑屋
checker
haojunyu/checker C 测试代码
learncpp

### 成品

#### 博客

#### devops


## 常用命令
### git子模块
```bash
# 拉取包含子模块的仓库
git clone --recursive https://github.com/caffe2/caffe2.git
# 如果子模块没有拉取成功，可以单独拉
git submodule update --init --recursive
# 拉取子模块
git submodule add https://github.com/haojunyu/hugo-theme-hjy.git
# 更新子模块
git submodule update

# 删除子模块
rm -rf #子模块目录 删除子模块目录及源码
vi .gitmodules #删除项目目录下.gitmodules文件中子模块相关条目
vi .git/config #删除配置项中子模块相关条目
rm .git/module/* #删除模块下的子模块目录，每个子模块对应一个目录，注意只删除对应的子模块目录即可
```

## 参考

1. [haoel的leetcode仓库][github_haoel_leetcode]


[usaco_web]: https://train.usaco.org/usacogate

