## 本仓库存放一些平时生活工作中自己写的Alfred Workflows

### Any-rule1.0.0

any-rule是一个快速查询正则表达式的workflow，数据源参考来自[any86/any-rule](https://github.com/any86/any-rule)，原作者初始版本是`vscode`的插件版，目前已拓展出web在线版，以及IDEA插件版。

本人习惯使用Alfred，也为了方便其他不写前端和java的大佬们使用，遂自己写了个workflow。

**核心命令：**

- zz {query}：根据关键字搜索正则表达式标题
- zzweb：跳转至Web在线版any-rule
- zzupdate：更新最新正则表达式数据到本地，下载需要几秒钟，请等待几秒后再重新查询

**注意：**

- 由于初始数据原作者存放在github仓库中，查询github接口数据请求较慢，效果不大行，因此将正则表达式数据下载至本地，以提高查询效率，基本可以达到实时过滤查询。
- 基于上一点，你使用时本地的正则表达式数据有可能不是最新的，可以执行`zzupdate`进行更新本地数据。
