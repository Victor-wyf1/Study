## 自定义title和logo
在前端寻找 env.development, production, staging三个文件，把里面的vite app title改掉，后端在ui里replace all修改掉
## 遇到redis无法启动或者双击redus.exe文件闪退问题 
检查redis默认端口6379是否被占用
使用cmd查看redis是否已经启动
在redis-windows.conf文件里查看是否绑定了bind 127.0.0.1，还有tcp-keepalive 300 的值是否为0
一般来说bind有可能缺失
## 针对新增自定义功能，前端出现模块名，但是增删改查按钮消失的问题 
例如新增模块名“酒店管理”
正常放置完sql，main和vue后。把api里的info.js和view里的index.vue放入到ry-vue3前端里的 src-api-system-info.js和
src-view-system-info的index.vue里
