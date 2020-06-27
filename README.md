# Remove-web-limits- 网页限制解除
在线安装 [Greasy Fork](https://greasyfork.org/zh-CN/scripts/28497-remove-web-limits-modified)

可以解除禁止复制、剪切、选择文本、右键菜单的限制, 通杀大部分网站.

安装后会在网页右上角出现一个半透明的小方框，虽然脚本已经内置了部分网站，但是如果您浏览的网站无法生效，可以将鼠标滑动至此，点击选框即可对该网站生效。 无效的情况下可以在此反馈

原作者 [cat73](https://cat7373.github.io/remove-web-limits/) , 已停止维护，其相关链接 [Greasy Fork](https://greasyfork.org/zh-CN/scripts/14146) , [GitHub](https://github.com/Cat7373/remove-web-limits) ,因为和 [搜索跳转脚本](https://greasyfork.org/zh-CN/scripts/27752-searchenginejump) 有 [冲突](https://greasyfork.org/zh-CN/forum/discussion/21298/x?locale=zh-CN#) ,遂进行了改动。

因为原作者因工作关系已停止维护，所以如果反馈的话，务必在我的 [GitHub](https://github.com/qxinGitHub/Remove-web-limits-/issues) 或者 [Greasy Fork](https://greasyfork.org/zh-CN/scripts/28497-remove-web-limits-modified) 下进行反馈，并提供相关网址。 如果是感谢的话可以去 [原作者的GitHub](https://github.com/Cat7373/remove-web-limits) 感谢。  

## 相关说明
1. flash页面上的文字无法复制
2. 链接上的文字可以通过按住alt键进行选择复制
3. 如果对视频网站使用，会使视频拖动条无法使用。 请在复制完成后关掉对视频网站的规则使用。

## 更新历史
  > v4.3.5 2020-02-23 
  - 删除注释
  - 增加www.change.tm 网站方便某校内学生使用
  > v4.3.3 2020-02-23 
  - 增加清空设置按钮
  - 增加 www.uslsoftware.com 网站
  > v4.3.3 2020-02-23 
  - 修复可能导致无法隐藏的问题
  > v4.3.2 2020-02-21 
  - 内部参数错误  导致新用户无法正常使用. 4.3.0 版本导致
  > v4.3.1 2020-02-20 
  - 样式微调
  > v4.3.0 2020-02-19 
  - 更改设置菜单，可以隐藏按钮
  > v4.2.0 2020-02-16  之前的版本历史在[Greasy Fork](https://greasyfork.org/zh-CN/scripts/28497-remove-web-limits-modified)
  - 获取所有节点 包括iframe中的节点
  - 修正 [海棠文化小说网站](https://www.myhtlmebook.com/)
  > v4.1.4 2018-07-02 
  - 移除广告
  > v4.1.3 2018-06-30 
  - 百度页面翻页后，会占用网页内容，感谢评论区 Gem Tre 反馈
  > v4.1.2 2018-06-29 
  - 更新了广告
  > v4.1.1 2018-06-26 
  - 增加了设置菜单
  - 增加了广告
  > v4.0.0 2018-06-11 
  - 4.0.0版本，整理了代码
  > v3.2.3 2018-06-05 
  - 感谢评论区 JsonBorn 的帮助，目前对于b站，仅排除视频区和番剧区
  > v3.2.2 2018-05-18 
  - 无法复制 b站的动态 问题，感谢反馈区 peter17ji 的反馈
  > v3.2.1 2018-05-10 
  - 注释掉脚本会无法生效的问题，感谢评论区Fengyifu 反馈
  - 改变窗口大小，按钮若离开可视窗口，会自动挪到最下方
  > v3.2.0 2018-04-18 
  - 增加吸附边缘，可以拖动位置，因为懒得原因，目前只能吸附在左边
  > v3.1.0 2018-04-02 
  - 个别网站会获取到错误的节点对象，导致程序异常终止。感谢评论区 Deleted user 163399 的反馈
  > v3.0.7 2018-03-13 
  - 知乎无法复制的问题，感谢用户 Qun Wang 的反馈
  > v3.0.6 2018-03-09 
  - 修改了英语和日语名字，用于和原脚本做区分
  > v3.0.5 2018-02-15 
  - 增加 beforeunload，去除离开限制，感谢评论区lickety建议，
  > v3.0.4 2018-02-15 
  - 脚本默认排除b站，熊猫直播网站，
  > v3.0.3 2018-02-15 
  - 应用宝等网站选中后透明，让用户产生无法选中的错觉，
  - 同时修正龙腾网（www.ltaaa.com）页面变蓝的情况
  > v3.0.2 2018-01-11 
  - 部分网站页面变成蓝色,感谢评论区Liang_Jinpeng 反馈
  > v3.0.1 2018-01-02 
  - 勾选后不再主动刷新页面；
  - 选中文字后，强制将颜色变为蓝底白字，某些页面选中文字后，背景与字体颜色无变化，给人一种无法选中的更觉
  > v3.0.0 2017-11-28 
  - 此版本开始会将列表上传至我的服务器，用以整合黑名单，
  > v2.4.11 2017-11-21
   - 知乎无法点击搜索框的下拉联想搜索，感谢 w153140 用户反馈
  > v2.4.10 2017-11-20
   - 之前保存数据可能导致保存空的字符串，致使所有完整都能匹配成功
  > v2.4.9 2017-10-17 
  - 增加对mousemove事件的清除，感谢 weijen6 用户反馈
  > v2.4.8.1 2017-10-12 
  - 精简无用的代码
  > v2.4.7 2017-10-11 
  - 发生故障，不知道问题原因，甚至不知道从哪个版本出现的问题。回滚到2.4.3. 在此版本上进行修改。 
  - 在网站city.udn.com中gm_getvalue间歇性无法使用。 
  - Array.from无法将set结构转换为数组，返回值为undefined。感谢评论区的weijen6反馈
  > v2.4.6 2017-09-28 
  - ~~可以简易的查看已屏蔽网站的列表~~
  > v2.4.5 2017-08-31 
  - ~~设置菜单位置偏移现象~~
  > v2.4.4 2017-08-27 
  - ~~黑名单中增加 “ http://bbs.coocaa.com，http://luxmuscles.com”，感谢 zhangbaida 及另一位用户提供。 小更新~~
  > v2.4.3 2017-08-22 
  - 知乎评论会同时删除两个字符的问题，新一轮的更新即将开始
  > v2.4.2 2017-06-04 
  - 完善 rwl-exempt，对于class中含有 “rwl-exempt”的，js事件将不会被覆盖掉
  > v2.4.1 2017-05-20 
  - 黑名单中增加 “ book.hjsm.tom.com；chuangshi.qq.com”，感谢 zhangbaida 提供
  > v2.4.0 2017-05-18 
  - 更改网址匹配规则，一（或多）级域名若在黑名单，则跟在其上面的多级域名同样位于黑名单
  - 本地数据版本更新至1.0， 在storage中使用名称排序，数据更新至25个网站。
  > v2.3.0 2017-05-16 
  - 更新本地数据库，尝试维护防复制网站这么个列表 对于class中含有 rwl-exempt 的元素免杀，若自己的脚本和它冲突，请尝试在元素的class中添加 ”rwl-exempt “
  > v2.2.4 2017-05-15 
  - 百度花语huayu.baidu.com, 原脚本对该网站是有效的，而我的却出了问题，临时先用其他方法解决它，所以单独更新个脚本以便日后排查这个问题
  > v2.2.3 2017-05-15 
  - 修复纵横，起点无选框的问题
  > v2.2.2 2017-05-07 
  - 默认规则中添加清空 mousedown，mouseup 事件
  > v2.2.1 2017-05-02 
  - 更改名字；更改图标；样式修复；去掉凤凰网的新闻分享；
  > v2.2.0 2017-04-26 
  - 对当初 2.1 修改版中一些不合逻辑的地方进行修改
  > v2.1.6 2017-04-26 
  - z-index 调为最大值； 在没有body元素的网页直接插入到html最后；加入图标
  > v2.1.5 2017-04-25 
  - 个别网站使用透明图层覆盖防止复制
  > v2.1.4 2017-04-24 
  - 注释掉 console.log
  > v2.1.3 2017-04-24 
  - 添加基本样式appearance
  > v2.1.2 2017-04-07 
  - 2.1.2 修复iframe也显示的问题
  > v2.1.1 2017-03-31 
  - 样式修改 style fix
  > v2.1.0 2017-03-30

  > v2.1.0 2017-03-30 
  - 大变动，很大的变动
  > v2.0.1 2017-03-29

  > v2.0.1 2017-03-29

  > v2.0.0 2017-03-28
