# Quantumult-X


### Sub-Store.rewrite.quanx.conf：
* 目的：无需HTTP Backend，订阅远程重写访问Sub-Store
* 订阅后浏览器访问：https://sub-store.vercel.app/#/
* 原作者：@Peng-YM

### Bili_Auto_Regions.rewrite.quanx.conf：
* 目的：针对NobyDa的Bili_Auto_Regions.js中的[rewrite_local]进行远程订阅化。
* 用法：
* 1. 重写中订阅本脚本
* 2. 分流中订阅B站和豆瓣流媒体：
* `[filter_remote]
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/StreamingMedia/StreamingSE.list, tag=B站流媒体：DivineEngine-StreamingSE.list, force-policy=B站媒体, update-interval=2592000, opt-parser=false, enabled=true`
* 3. 创建自定义策略“B站媒体”及旗下子策略“香港节点”“台湾节点”
* 4. 订阅NobyDa的BoxJS按上一条设置对应关系
* 原作者：@NobyDa
