## Weex Docker版

### 0.docker pull 
	$:docker pull registry.cn-hangzhou.aliyuncs.com/nisang/weextoolkit:v0.5.3



### 1.自己build 

* 1.docker build

	`$:docker build -t node:weex .`

* 2.docker run
* 
	`$:docker run -d -p 8081:8082 -p 8081:8082 node:weex`


### 3.构建项目

    $:RUN weex init

	$:RUN npm install

	$RUN npm install weex-components

### 4.运行Weex
	$:weex main.we

### 5.相关地址
* 访问地址：
* 
    	 http://127.0.0.1:8081/weex_tmp/h5_render/?hot-reload_controller&page=main.js&loader=xhr

* week-toolkit安装
    	 https://www.npmjs.com/search?q=weex-toolkit
