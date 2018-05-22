#   文件划分
*   image
    *   image图片进行压缩，拷贝到dist/中
    *   图片可以直接放到image根目录下
*   lib文件夹
    *   放置公用的js脚本，例如：jquery等
    *   该文件直接拷贝到dist/
*   font文件夹
    *   放置字体
    *   该文件直接拷贝到dist/
*   js文件夹
    *   index.js是登录页面的脚本
    *   tmpl是模板自动生成的脚本（不要修改该文件夹）
    *   各模块js脚本
        *   student(学生端)
        *   system（后台系统）
        *   teacher（教师端）
    *   .json
*   main文件
    *   放置requeir 配置文件
*   style文件
    *   各模块
        *   student(学生端)
        *   system（后台系统）
        *   teacher（教师端）
    *   main.css自动生成（gulp style:dev）
    *   .json
    *   style->编译sass->加前缀->合并->压缩->打版本
*   template(模板)
    *   自定义模板
    *   如文件夹header，文件header.html
*   view(页面.html)
    *   各模块
            *   student(学生端)
            *   system（后台系统）
            *   teacher（教师端）
#   执行
*   npm run dev
    *   打开服务器-》链接浏览器-》监听style：dev和template模板变化
    npm run build
    *	打包成dist

    注意：各文件不能重名
