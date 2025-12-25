# 一些服务器有关的常见疑难杂症归档处

本贴皆在收集一些常见的且不好分类的疑难杂症问题及其解释与解决方式:)

## 服务器加入时

- Q: 我确认自己拥有白名单，但是我在加入服务器时提示“You are not whitelistd on this server.”或“发生一个内部错误”？
- A: 一般是白名单插件联网校验异常，联络运维组即可；

---

- Q: 我在加入服务器后立刻断开连接？
- A: 一般是因为你使用的不是 **Java Edition 1.20.4** 版本客户端，或者您在其他版本使用了跨版本模组（如viafabric） 尝试加入游戏；
- 请改用 1.20.4 版本客户端加入游戏即可

## 服务器加入后

- Q：为什么我加入游戏后一说话就被踢出游戏？
- A: 你需要安装 [No Chat Reports](https://modrinth.com/mod/no-chat-reports?version=1.20.4&loader=fabric#download) 模组。

---

- Q：为什么我在创造&镜像服使用投影粘贴原理图时粘出来的容器没有容器？我确信我的投影原理图内该容器已被填充；
- A: 你需要安装 [Litematica Server Paster](https://modrinth.com/mod/litematica-server-paster?version=1.20.4#download) 模组即可解决。
- 
---

- Q：为什么我在服内使用 /music 或他人使用 /music 点歌后没有听到声音？
- A: 你需要从 雨&雪群 群文件内检索 “Allmusic-client” 模组并将其安装至你的客户端。
