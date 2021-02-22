
<p align="center">
  <a href="https://zwtdyhm.github.io/nav/?g">
    <img src="src/assets/logo.png" width="130" />
  </a>
  <br />
  <b>导航</b>
  <p align="center">一个纯静态、支持SEO、在线编辑的强大导航网站，希望您会喜欢</p>
  <p align="center">内置收录多达 800+ 优质网站， 助您工作、学习和生活</p>
  <p align="center">
    <img src="https://img.shields.io/github/v/release/zwtdyhm/nav" />
    <a href="https://github.com/zwtdyhm/nav/stargazers"><img src="https://img.shields.io/github/stars/zwtdyhm/nav" alt="Stars"/></a>
    <img alt="Angular" src="https://img.shields.io/static/v1.svg?label=&message=Angular11&style=flat-square&color=C82B38">
    <img src="https://img.shields.io/github/license/zwtdyhm/nav" />
    <a href="https://hits.dwyl.com/zwtdyhm/nav">
      <img src="https://hits.dwyl.com/zwtdyhm/nav.svg" />
    </a>
  </p>
</p>

<br />
<br />


## 预览
**主题**

- [Sim 在线预览](https://zwtdyhm.github.io/nav/#/sim)
- [Light 在线预览](https://zwtdyhm.github.io/nav/#/light)
- [Side 在线预览](https://zwtdyhm.github.io/nav/#/side)
- [App 在线预览](https://zwtdyhm.github.io/nav/#/app)

![Preview](https://raw.githubusercontent.com/zwtdyhm/public/gh-pages/nav/1.png)
![Preview](https://raw.githubusercontent.com/zwtdyhm/public/gh-pages/nav/2.png)
![Preview](https://raw.githubusercontent.com/zwtdyhm/public/gh-pages/nav/3.png)
![Preview](https://raw.githubusercontent.com/zwtdyhm/public/gh-pages/nav/4.png)
![Preview](https://raw.githubusercontent.com/zwtdyhm/public/gh-pages/nav/5.png)





## 特性
`导航` 的理念就是做一款无需依赖后端服务既简单又方便，没有繁杂的配置和数据库等配置概念, 做到开箱即用。

- 🍰 内置 `800+` 实用网站。
- 🍰 支持 SEO。
- 🍰 完全纯静态, 提供自动化部署功能。
- 🍰 三叉树分类、结构清晰、分类清晰。
- 🍰 支持一个网站关联多个网址
- 🍰 颜值与简约并存，不再是杀马特时代。
- 🍰 完全开源，轻松定制化。
- 🍰 支持多种浏览模式，创新。
- 🍰 支持足迹记忆。
- 🍰 支持移动端浏览。
- 🍰 支持搜索查询。
- 🍰 支持自定义引擎搜索。
- 🍰 多款主题切换。
- 🍰 支持暗黑模式。
- 🍰 支持快捷键操作，一步到位。
- 🍰 支持后台管理, 无需部署。
- 🍰 支持从Chrome书签导入



## 部署
推荐使用 `github pages` 服务, 这样就不需要提供服务器, 并且项目里自带了自动化部署服务，像数 `321` 一样简单。

1、Fork 当前项目。

2、[https://github.com/settings/tokens](https://github.com/settings/tokens) 申请 token, 勾选相应的权限, 如果不懂就全部选中，复制并保存Token。

3、https://github.com/用户名/nav/settings/secrets/actions/new  添加申请的token， name填写 `TOKEN` 大写。

4、打开 https://github.com/用户名/nav/actions 点击 `绿色按钮`

5、务必修改项目配置文件 [nav.config.ts](nav.config.ts)

6、5分钟后打开 https://用户名.github.io/nav 就能看到一个非常强大的导航网站了。


注：如果想部署到自己的域名，那么以上教程同样适合，因为它提供了自动化部署， 之后可以通过 `CNAME` 或 `反向代理` 实现：

```conf
# nginx

server {
    listen       80;
    server_name  www.nav3.cn nav3.cn;

    location / {
        proxy_pass https://zwtdyhm.github.io/nav/;
    }
}
```


## 书签导入
支持从 Chrome 书签导入（WebKit内核应该都是支持的~），会自动检测满足三级分类的导航，其他一律跳过：

![](https://raw.githubusercontent.com/zwtdyhm/public/gh-pages/nav/import.png)

浏览器打开 [chrome://bookmarks/](chrome://bookmarks/) 导出书签得到 html 文件, 接着从导航网站后台导入即可。





## 升级
在升级之前请备份根目录下的 `data` 文件夹和 `nav.config.ts`, 升级完后替换即可。

点击右上角 `Watch` 按钮第一时间跟踪版本升级。



## 更新日志
[CHANGELOG](CHANGELOG.md)




## 快捷键
mac下是 `Command`，windows 下是 `Ctrl`

- `ctrl+v` 查看信息
- `ctrl+d` 开启或关闭暗黑模式

如对快捷键有特殊要求请发起 [issues](https://github.com/zwtdyhm/nav/issues)





## 开发构建
``` bash
# 下载
git clone --depth=1 https://github.com/zwtdyhm/nav.git

# 安装依赖
npm i

# 启动
npm start

# 打包
npm run build
```



## 贡献
[点击这里](https://github.com/zwtdyhm/nav/tree/master/data)

Thank you for your [contribution](https://github.com/zwtdyhm/nav/issues), men.

<a href="https://github.com/YutHelloWorld">
  <img src="https://avatars1.githubusercontent.com/u/20860159?s=460&v=4" width="30px" height="30px" />
</a>
<a href="https://github.com/JJJTHuang">
  <img src="https://avatars3.githubusercontent.com/u/22817432?s=460&v=4" width="30px" height="30px" />
</a>
<a href="https://github.com/Fechin">
  <img src="https://avatars1.githubusercontent.com/u/2541482?s=460&v=4" width="30px" height="30px" />
</a>
<a href="https://github.com/setdiaoyong">
  <img src="https://avatars1.githubusercontent.com/u/62551864?s=460&v=4" width="30px" height="30px" />
</a>






## 建议
如果有任何功能上的建议可通过 [issue](https://github.com/zwtdyhm/nav/issues) 发起, Thank you.



## 支持
项目成立于 2018 年到至今一直坚持维护和开源, 经过N次的迭代与优化, 如果项目能帮到您是我的荣幸。

您可以请作者喝杯咖啡，继续战斗下去（请备注Github名字）~

<img src="https://raw.sevencdn.com/zwtdyhm/public/gh-pages/img/32.png" width="600">

感谢您的认可：
| 姓名    | 支持金额              |
| --------------------------------------- |----------- |
| [aiyou9](https://github.com/aiyou9)     | ￥20.00     |
| 路人甲     | ￥50.00     |

