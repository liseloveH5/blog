### hexo安装
```
$ npm install -g hexo //安装
$ hexo init //初始化
$ hexo clean  //清理public文件夹
$ hexo g //生成 
$ hexo s //启动服务 本地访问：http://localhost:4000
```
>  在public文件夹生成目标文件，提交GitHub

### 下载主题
```
$ git clone https://github.com/litten/hexo-theme-yilia.git themes/yilia

```
> 下载主题在theme文件夹里
> 引用方法：修改_config.yml中的theme: landscape改为theme: yilia，重新执行生成命令