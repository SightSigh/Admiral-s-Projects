# Admiral-s-Projects
# 提督的改修课题
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/ "License: CC BY-NC 4.0")  
## 简介
用于规划并记录使用者近期改修需求的EXCEL表格。  
该表使用的数据资料均来源于[KC日文wiki](https://wikiwiki.jp/kancolle/%E6%94%B9%E4%BF%AE%E5%B7%A5%E5%BB%A0 "改修工廠")，表格改造由本人独立完成，所有公式均无加密，支持使用者二次开发与维护。  
因能力有限，既不能以KC辅助工具的插件及独立应用等形式将其呈现，恐怕也难以提供进一步的技术支持，还请谅解。  
个人使用过功能相似的项目整理如下：

项目名称|形式|依存关系|数据更新状况|关联个人数据|蓝图模式|消耗统计|记载改修进度|支持换日改修|
:-------:|:----:|:----------:|:----------:|:------------:|:-------:|:-------:|:-------:|:-------:|
装备改修+星级争霸|POI预装插件|以POI联网进行游戏|续更|√|有|每级纸面数据及装备耗材余量查询，无统计|总体目标|√|
明石工具箱（舰百）|手机应用|无特别依赖|已断更|×|无|仅每级纸面数据，无统计|×|×|
AKASHI-LIST|网页|以浏览器联网|续更|×|无|选择特定级别起应用必成模式计算理论消耗|×|×|
此表格|XLSX文件|本地兼容EXCEL2010以上软件或微软云端EXCEL应用（OneDrive可）|续更|×|暂不实装|统计装备耗材以外的实际消耗，附加可行性验证|具体目标|√|


    该表格默认为2560*1440分辨率优化，请在高分辨率的设备上使用以获得最佳效果。  
    显示效果可以根据使用设备的条件进行自行调整，详见末尾“维护说明”部分的相关说明。  
    如果每日长期需要进行多个项目的改修，请自行尝试改造及扩展表格，  
    当前仅适用于每日以特定模式处理单个项目。  
    使用者必须要安装OFFICE2010版本以上的表格工具方能正常使用该表格。  
    经测试验证，最新版本WPS中的表格工具也可以作为替代。  
    （Excel的下拉菜单只能在滚动条上使用滚轮，而WPS可以直接在栏目中滚动，使用体验更佳）

![改修规划](https://github.com/SightSigh/Admiral-s-Projects/blob/master/%E6%94%B9%E4%BF%AE%E8%A7%84%E5%88%92.png "改修规划")
![当期统计](https://github.com/SightSigh/Admiral-s-Projects/blob/master/%E5%BD%93%E6%9C%9F%E7%BB%9F%E8%AE%A1.png "当期统计")
![预期收入](https://github.com/SightSigh/Admiral-s-Projects/blob/master/%E9%A2%84%E6%9C%9F%E6%94%B6%E5%85%A5.png "预期收入")
    
### 注意！
此表格不适合新手使用！  
它只能记录使用者自身的想法，但无法代替使用者创建规划！  
如果使用者不知道自己需要改什么，使用本规划表亦将无济于事！  

### 刁钻Q&A

    Q：为什么要采用这种每天只改一个项目的改修模式？  
    A：除了蹭每日任务的改修补贴，更主要的是为了逐步提高装备质量，以此提升舰队的实力。
    
    Q：每日就补贴1个螺丝，有什么用？  
    A：每年累计补贴365个螺丝，价值25550日元，按发稿时汇率16.32计算，相当约1565人民币。
    
    Q：改饭团薅每日羊毛不就得了，需要这么复杂么？  
    A：螺丝只有转化为出击装备的改修等级才算提升实力，你每天炒饭，推图时也是塞满它们出击的吗？
    
    Q：那我买几千个螺丝直接毕业不就好了？还用得着记录？  
    A：不用受制于螺丝可以随意改修的人，不需要记录。顺带提一下，你可能还要掏钱买齿轮，它的消耗比螺丝多。
    
    Q：每天一项进度太慢了，我一天想改多项，但项目数不固定，也想做记录，怎么办？  
    A：依照目前的框架，你可以按需扩展表格，比较简单的方法是将每周的完整结构复制多次，后面统计页面修改一下统计位置即可。  
       复杂点可以把结构由横向改为纵向，幅度拉长，减少同一页面中的元素，这样方便浏览。
    
    Q：好麻烦啊，我只想用现成的，你不能同时维护几个版本吗？  
    A：我只有时间维护我使用的版本。
    
    Q：就不能做成程序么？让它带自适应功能岂不美哉？  
    A：按照授权你可以自行演绎此项目。
    
    Q：我看不懂规划表，能不能加个指示器来显示装备开始的时候是几星，结束时是几星？
    A：在规划时选择表格中的装备阶段标签，并运用二十以内加减法进行计算即可。
    
    Q：我弄不懂改修优先级，按照大佬的方案来不会错吧？
    A：非表格问题，恕我无可奉告。

    
## 简称说明
#### 此表格将使用某些简称代指游戏中的以下内容

    齿轮=开发资材
    螺丝=改修资材
    水桶=高速修复材
    喷枪=高速建造材
    助手=以明石（改）为旗舰的第一舰队中二号位的舰娘
    低阶=装备改修等级0~6
    高阶=装备改修等级7~10
    
## 使用技巧

活用“delete”键清除内容及创建当前的改修进度标记，凡是能够下拉单元格都可以运用此方法。

简易可行性可以参考预期收益表中的日均消耗线。

由于齿轮还可以用于开发、建造，无法由此规划表统计消耗量，故不可作为可行性参考。

如果不需进行可行性预测，首先清空预期收益表中的计数器，再将可折叠部分的下拉单元格清空并隐藏明细，即可停用此部分功能。

    
## 助手说明

换日改修，即在日本时间（UTC+9）零时至四点五十九分之间进行改修，其可改修内容已更换为下一天的项目，本表已经为适配此项设定进行了改造。

* __本表默认使用者拥有所有助手的最高改造形态__，故当一个项目出现某助手只能换日改修，但还有其他助手可以进行正常改修时，只能换日改修的助手将不予标注  
    例：15.2cm連装砲 日 能代、~~★矢矧~~ ←不予标注

* 红色样式表示当前装备的可改修日含有换日改修的助手，该助手前以★标识  
    例：20.3cm(3号)連装砲 月 ★三隈  
  * 当助手在低级形态可以全日改修，但高级形态只适用换日改修时，该高级形态将以★标识  
    例：46cm三連装砲 日 武蔵0、★武蔵1

* 当前装备在助手各种改造形态都可以进行的改修，该助手以其改造最低形态的名称显示，并且末尾无数字标识  
    例：381mm/50 三連装砲改 日 Littorio

* 当前装备在助手限定的改造形态才可以进行的改修，该助手以其限定的形态名称显示，末尾数字代表其受限形态的改造阶段，以[限]为标识  
    例：15.5cm三連装副砲改 日 武蔵1[限]
  * 为简化显示效果，限定形态为该船最低改造形态时，该[限]标识将省略  
    例：32号対水上電探改 土 ★伊勢、日向0 ~~[限]~~ ←不予标注
  * 并且当限定形态是该助手的最终改造形态时，该[限]标识亦将省略  
    例：203mm／53 連装砲 日 Zara2 ~~[限]~~ ←不予标注

* 有少数装备存在升级限制，当指定助手可进行升级，而其余助手无法升级时，可进行升级的助手将以[更]标识  
    例：8cm高角砲 日 阿賀野、能代、矢矧[更]
  * 当遇到该日所有指定助手都不能进行升级的情况，每位助手将以[更×]标识  
    例：8cm高角砲 土 阿賀野[更×]、能代[更×]
  * 两种情况一起出现时，特定情况更少发生的形态才有标识  
    例：25mm三連装機銃 水 五十鈴2、村雨2、(摩耶0、1[限])[更×]、摩耶2、皐月2

* 有少数装备存在升级分支，当指定助手可向特定分支升级时，该助手将以[支]标识  
    此表格的升级分支设定如下：  
    九三式水中聴音機→三式水中探信儀  
    94式高射装置→12.7cm高角砲＋高射装置  
    大発動艇→特大発動艇  
    例：大発動艇 日 あきつ丸、皐月2、阿武隈2、鬼怒2[支]
    
## 维护说明
#### 关于数据更新
    
由于作者自用，故直到弃游/停运/改修工厂机制出现重大变化，致使此工具失效为止，都会持续进行数据部分的更新。  

#### 关于内容更新
    
如果觉得现有界面不需调整即可适用，更新时直接下载新版本的文件，删除旧文件即可。  

如果调整过表格格式，重新设定了字号、行列宽等样式，则先下载新版本文件，  
再打开新旧两个表格，复制旧表格中修改过的区域（如果架构和内容没变，直接全选），  
粘贴到新版本文件中对应的区域，选择只粘贴格式，即可完成更新。  
    
如果还修改了表格内容，则需要自行考虑适配的方法。  
    
也可以自行维护数据，数据表格初始为隐藏状态，解除隐藏后可见。  
