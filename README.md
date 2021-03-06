## 介绍

主要是研发一个微信小程序，方便一些用户收发文件，然后统一管理或是以链接的方式发送给他人。
![qrcode](https://github.com/zeffon/danzhu-mini/raw/master/imgs/cover/qrcode.png)

## 功能点分析

1. 任意小程序用户可以发起收发文件的任务（发起者即为管理员，其有权限修改该任务下的用户的文件名，或是替换他们文件，管理员也可以提交文件）
1. 设定有用户组，可以通过创建一个用户组来邀请用户加入用户组之中。发起者即为管理者，他可以定义一些用户组一些基本字段，也可以修改这个用户组下的用户基本信息。
1. 每个收发作业的任务设定有：用户组(如果不是该用户组无权限提交，所有用户就没有限制了，还有指定用户组时还可以指定到一些人需要提交，一些人可不用提交)、截止时间、提交人数
1. 用户需要完善他所加入用户组的基本信息，之后也可以修改基本信息
1. 创建收集组可以通过小程序分享或是小程序搜索收集组编码的方式通知需要提交的用户加入该收集组。
1. 上传的文件可以是图片格式、word、pdf、zip 压缩包等文件
1. 搜索功能主要搜索收集组编码和用户组编码
1. 收集组的收集情况可以展示给管理员查看
1. 统一打包后 可以压缩包的形式一键下载，也可以转化成 链接+密码（随机密码、自定义密码，链接有效期）
1. 用户界面：我的用户组（分为创建和加入）、我的收集组（分为创建和加入）
