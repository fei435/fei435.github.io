# fei435.github.io

## 说明

童小飞的技术博客，使用hexo+archer主题搭建于github平台上。

此为source分支，主要存放hexo工具，用于将markdown写作的`md`文件生成静态html，存放`_config.yaml`/`.travis.yml`等配置,并通过`travis-ci`流程自动将生成后的public目录发布到master分支，发布后的master分支不包含md文件和_config.yml等各种配置。

## 写作环境初始化步骤

换电脑后，需要初始化一个新的写作环境，记录下步骤

```bash
brew install nodejs
node -v

npm install -g hexo-cli
```

## Travis-ci

##
