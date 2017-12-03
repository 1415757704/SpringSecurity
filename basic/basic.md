* 认证方式
    * SpringSecurity提供的认证（浏览器:是基于服务器Session的方式进行认证）   
        * 用户名密码认证 
        * 手机验证码认证
    * SpringSocial认证（浏览器）
        * 第三方认证：微信、qq登陆
    * Spring Security OAuth（App认证：由于App请求的时候每次都会创建一个新的Session、无法使用服务器的Session进行认证、所以采用token认证）
        * App基于上面三种的认证
![image](img/OAuth.jpg)
* Restful API
    * 用URI描述资源：不管是GET、PUT请求都是用一样的URI，URI中携带要操作的对象（例如id），所以是标识一种资源.
    * 用请求行为描述各种行为（GET描述查操作、POST描述增操作...）、使用返回状态码表示访问的状态
    * 使用JSON格式进行交互
* 使用JsonView，在某个接口中对于一个对象不想显示出来的字段来做显示
![image](img/JsonView.jpg)
