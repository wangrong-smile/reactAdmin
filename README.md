1.1项目描述
    1) 此项目为一个前后台分离的后台管理的SPA,包含前端PC应用和后端应用
    2) 包括用xxx等功能模块
    3) 前端：使用 React全家桶 + Antd +Axios + ES6 + Webpack 等技术
    4) 后端：使用 Node + Express + Mongodb 等技术
    5) 采用模块化、组件化、工程化的模式开发

1.2技术选型
    1) 前台数据展示/交互/组件化：react + react-router-dom + antd + redux
    2) 后台应用：node + mongodb + mongoose + multer + blueimp-md5
    3) 前后交互： ajax请求 ： axios + jsonp + promise / async / await
                 接口测试工具： postman
    4) 模块化：Es6 + CommonJs
    5) 项目构建： webpack + create-react-app + eslint
    6) 其他 ： 富文本编辑器 ： react-draft-wysiwyg + draft-js + draftjs-to-html
               图表库： echarts + echarts-for-react

2.1开起项目开发
2.1.1  使用create-react-app(脚手架搭建项目)
    1) create-react-app是creat 官网提供的用于搭建基于react+wepack+es6项目的脚手架
    2) 操作： npm install -g create-react-app(全局下载工具)
              create-react-app react-admin_client(下载模板项目)
              cd react-admin
              npm start
              访问：localhost:3000
2.1.2   编码测试与打包发布项目
    1)  编码测试
        npm start:http://localhost:3000
    2)  打包发布
        npm run build
        npm install -g serve
        serve build
        访问：http://localhost:5000
             