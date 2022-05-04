# jxc-front-end
## 1. 弹框不能正常显示问题
* 试着将 `:forceRender="true"` 删除，此方法为原gitee项目issues提供：
[新增界面无法正常显示](https://gitee.com/FINERME/psi/issues/I2A3CL)
## 2. 查询规则
* 星号+内容  左模糊查询
* 内容+星号  右模糊查询
* 星号+内容+星号 全模糊查询
* 逗号分隔内容（不支持模糊）  多值查询
* 叹号+内容  不等于查询
## 3. 加载登陆页面慢
* ``vue.config.js`` 文件中压缩``js/css``没有开启，环境配置为``production``模式