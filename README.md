# AutoTest
自动化测试平台，接口自动化、web自动化、app自动化、性能自动化

### 使用说明
下载直接导入到Eclipse或者myEclipse中，项目用到了maven，需要自己配置下仓库源为阿里云仓库。
MySQL版本为5.6

目前仅完成了接口自动化，可能有BUG，欢迎与我联系。

## 注意：请勿商用，就是不要直接拿来给自己公司用，仅限个人学习交流使用，非个人使用请先联系我。

## 2017.8.1更新
修复几个bug
完善定时任务模块

修改httpclient发送http请求的方式
修复了因为提前对连接releaseConnection()操作导致response.getEntity().getContent()无法正常获取返回的问题（这个问题在本地没有任何问题，不知道是什么问题）
