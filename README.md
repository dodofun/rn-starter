## Android 设备的CPU类型(通常称为”ABIs”)
````
armeabiv-v7a	第7代及以上的 ARM 处理器。2011年15月以后的生产的大部分Android设备都使用它
arm64-v8a	第8代、64位ARM处理器，很少设备，三星 Galaxy S6是其中之一
armeabi	第5代、第6代的ARM处理器，早期的手机用的比较多
x86	平板、模拟器用得比较多
x86_64	64位的平板
````

## React-native 相关库
````
react-navigation
https://github.com/react-navigation/react-navigation

react-native-firebase
https://github.com/invertase/react-native-firebase

lottie-react-native
https://github.com/react-native-community/lottie-react-native

WatermelonDB
https://github.com/Nozbe/WatermelonDB

rxdb
https://github.com/pubkey/rxdb

react-native-webview
https://github.com/react-native-webview/react-native-webview

react-native-swiper
https://github.com/leecade/react-native-swiper

react-native-vector-icons
https://github.com/oblador/react-native-vector-icons

react-native-gifted-chat
https://github.com/FaridSafi/react-native-gifted-chat

appcenter
https://appcenter.ms/

react-native-code-push
https://github.com/Microsoft/react-native-code-push

react-native-push-notification
https://github.com/zo0r/react-native-push-notification

react-native-wechat
https://github.com/yorkie/react-native-wechat

react-native-animatable
https://github.com/oblador/react-native-animatable

react-native-web
https://github.com/necolas/react-native-web

expo
https://docs.expo.io/
````

## Git相关
````
初始化
git init

关联远程仓库
git remote add origin https://github.com/dodofun/rn-starter.git

git push -u origin master
````

## 代码规范

### Commitlint
https://segmentfault.com/a/1190000017790694

````
定制提交规范
提交格式（注意冒号后面有空格）
<type>: <subject>
常用的type类别
upd：更新某功能（不是 feat, 不是 fix）
feat：新功能（feature）
fix：修补bug
docs：文档（documentation）
style： 格式（不影响代码运行的变动）
refactor：重构（即不是新增功能，也不是修改bug的代码变动）
test：增加测试
chore：构建过程或辅助工具的变动
例子：

git commit -m 'feat: 增加 xxx 功能'
git commit -m 'bug: 修复 xxx 功能'
subject
subject是 commit 目的的简短描述，可以做一些配置，如最大长度限制。

````


# eslint + prettier + commitlint