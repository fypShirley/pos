
#### 简单的收银系统
    技术栈："axios"
            "element-ui"
            "vue"
            "vue-router"
            
    内容主要分为4部分：
        （1）利用element-ui布局
        （2）从远端读取数据：
        （3）订单的增加和删除
        （4）模拟结账
        
    最后打包上线:
        打开config/index.js 会看到一个build属性，修改打包的目录，打包的文件名
        最重要的是一定要把绝对目录改为相对目录:	 assetsPublicPath:'./'
        在命令行中用npm run build  进行打包。
        
       
    （PS：学习地址来源：http://jspang.com/2017/05/22/vuedemo/）
        
