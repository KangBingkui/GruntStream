# GruntStream
Grunt自动化流程，以及watch文件监听插件的使用
###文件目录结构

---GruntStream          //项目根目录 <br>
&nbsp;&nbsp;&nbsp;&nbsp;|---dest              //存放合并后的文件和压缩后的文件<br>
&nbsp;&nbsp;&nbsp;&nbsp;|---src               //源代码存放路径<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|---css          //存放css文件<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|---js           //存放js文件<br>
&nbsp;&nbsp;&nbsp;&nbsp;|---Gruntfile.js     //grunt配置文件<br>
&nbsp;&nbsp;&nbsp;&nbsp;|---package.json     //配置json文件<br>
&nbsp;&nbsp;&nbsp;&nbsp;|---.csslint         //css扫描配置<br>
&nbsp;&nbsp;&nbsp;&nbsp;|---.jshint          //js扫描配置<br>

###运行步骤

- 进入项目根目录
- 执行`npm install` 安装所有依赖的库
- 安装完后，执行`grunt`运行脚本
- 然后改变src/css文件夹（或者src/js文件夹）下的内容，保存后，监听程序自动执行扫描
