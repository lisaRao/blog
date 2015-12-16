title: echo
thumbnailImage: http://7xp5hh.com1.z0.glb.clouddn.com/vintage-140.jpg
autoThumbnailImage: yes
tags:
    -前端构建
    -gulp
categories: 前端构建
---

> [gulp官网](http://gulpjs.com/)

**基本入门**

1. 全局安装`gulp.js`

```
		npm install -g gulp
```

<!-- more -->

2. 为项目目录安装`gulp.js`库文件

```
		#cd c://myproject/demo1
		npm install --save-dev gulp
```

3. 在项目根目录创建`gulpfile.js`文件并写入以下模板。

```
		var gulp = require('gulp');

		gulp.task('default', function(){
			// code
		});

```

4. 运行`gulp`任务。

```
		gulp

```    

基本入门就4步可以完成，比起`grunt`各种配置简单许多。
