## 富客户端框架 ##
“富客户端”（Rich Client)简介富因特网应用程序（Rich Internet Applications，RIA）利用具有**很强交互性**的富客户端技术来为用户提供一个更高和更全方位的网络体验。RIA集成了桌面应用的交互性和传统Web应用的部署灵活性与成本分析，以创建单一而完整的用户体验。富客户端技术使创建RIA成为可能，它提供一个运行时的环境以承载被编译的客户端应用程序，该客户端应用程序是一个使用HTTP协议发布的文件。客户端应用程序使用异步的C/S结构连接到现有的应用服务器，这是一种安全的、可升级的、具有良好适应性的面向服务模型，这种模型由当前所采用的Web服务驱动。 


## 1.ExtJs ##
ExtJS可以用来开发RIA也即富客户端的AJAX应用，是一个用javascript写的，主要用于创建前端用户界面，是一个与后台技术无关的前端ajax框架。因此，可以把ExtJS用在.Net、Java、Php等各种开发语言开发的应用中。ExtJs最开始基于YUI技术，由开发人员JackSlocum开发，通过参考JavaSwing等机制来组织可视化组件，无论从UI界面上CSS样式的应用，到数据解析上的异常处理，都可算是一款不可多得的JavaScript客户端技术的精品。


完全用js把全套页面从无到有搭起来。这种做法的缺点就是不直观。另外ExtJS也没有像JQuery那样抽象出 动作和effect这样的概念，panel里甚至有animate这样的属性用来对panel进行淡入淡出。这是把行为和对象绑定的到一起的不好作法。
## 2.DojoJs ##
这东西以前就是以组件全面而出名，不只是UI组件很全，其他非UI组件也很全（比如map之类的），甚至有一些3D啊之类的组件，在以前HTML不支持canvas的时候，Dojo就有这样的组件了。Dojo.require来管理依赖非常有创意。它的缺点就是写起来比较麻烦。
