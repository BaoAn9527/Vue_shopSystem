Vue项目: 电商管理系统
项目描述: 是用于管理用户账号、商品分类、商品信息、订单、数据统计等业务功能。
前端技术栈: Vue、Vue-router、Element-UI、Axios、Ec harts
后端技术栈: Node.js、Express、Mysql
技术实现:
通过sessionStorage在服务端记录状态，通过axios拦截器的请求头添加token验证来维持登录/退出状态
使用axios发起数据请求并接收响应信息获取数据动态渲染界面，并配置请求根路径baseURL，方便统一修改
通过element-UI中的c ontainer容器布局来实现页面的基本布局
通过路由的形式展示用户列表，在sessionStorage中保存左侧菜单栏的激活状态，同时利用 vue-router 的子路由完成不
同组件的跳转
需要填写信息的模块使用了双向数据绑定输入框，并用elementui的rules验证对输入的数据进行验证
后端运用Node JS，express开发框架搭建web服务器，操作数据库 ,为前端提供接口