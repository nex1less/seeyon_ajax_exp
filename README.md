# seeyon_ajax_exp

致远OA文件上传漏洞利用脚本,绕过部分url过滤规则waf

版本更新,更新内容：

新增提交方式，绕过部分url过滤规则waf

已知影响版本：致远oa v7,v8

脚本已经打包好，没有任何防护，可直接查看源码，不存在后门。

使用方法：java -jar seeyon_exp.jar 目标地址 上传文件名字 上传文件绝对路径 提交方式

例:      java -jar seeyon_exp.jar 10.10.10.10:8080 shell.jsp C:\Users\nex1less\Desktop\222.txt 1

默认路径为:ip + /seeyon/ + 文件名

有时创建文件成功，验证执行失败是因为验证延时设置太少

