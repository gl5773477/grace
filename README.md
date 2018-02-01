# grace
grace无损升级，支持supervisor管理。目前内容还很简陋，可根据需要修改。

# 升级默认端口为8999，接口为/up
例：http://localhost:8999/up

# 使用
grace.ListenAndServe(addr,handler)
替换
http.ListenAndServe(addr,handler)
