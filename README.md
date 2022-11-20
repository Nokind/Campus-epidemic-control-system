# Campus-epidemic-control-system
主要技术：Springboot+MyBatisPlus+Redis+SpringSecurity+MySQL+Swagger
	项目地址：https://github.com/Nokind/Campus-epidemic-control-system.git
	独立开发的基于Springboot技术栈的疫情防控管理平台，采用前后端分离架构，方便技术的迭代和升级
	使用SpringSecurity对使用该系统的不同角色进行身份认证和访问控制，并结合JWT技术做访问认证，由于不用在服务器保存Session, 节省了服务器内存资源，
	为了提高程序运行速度，使用Redis缓存实现登录的验证码和SpringSecurity框架验证用户身份时的需要的UserDetail实现类信息
	使用注解框架Swagger3.0生成接口文档，在开发接口时可以通过swagger将接口文档定义好,同时也方便本系统以后的维护管理
	采用时下流行的MyBatisPlus一键自动生成基本的接口映射文件，减少不必要的开发工作，提高工作效率
