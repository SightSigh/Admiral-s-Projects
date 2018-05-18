# Admiral-s-Projects
# 提督的改修规划表

该表使用的数据资料均来源于[KC日文wiki](https://wikiwiki.jp/kancolle/%E6%94%B9%E4%BF%AE%E5%B7%A5%E5%BB%A0 "改修工廠")，表格改造由我独立完成，所有内容均无加密，支持使用者自行维护以及开发。  
因能力有限，既不能以KC辅助工具的插件及独立应用等形式将其呈现，恐怕也难以提供进一步的技术支持，还请谅解。
    
    此位置待补充规划表的截图
    
    备注：该表格默认为2560*1440分辨率优化，请在高分辨率的设备上使用以获得最佳效果。
    显示效果可以根据使用设备的条件进行自行调整，详见后文“自行维护”部分的相关说明。
    如果每日长期规划多个改修项目，请自行尝试改造及扩展表格。
    
### 注意！
此表格不适合新手使用！  
它只能记录使用者自身的想法，但无法代替使用者创建规划！  
如果使用者不知道自己需要改什么，使用本规划表亦将无济于事！  
    
    使用者必须要安装OFFICE2010版本以上的表格工具方能正常使用该表格。
    经测试验证，新版本WPS中的表格工具也可以作为替代。
    （Excel的下拉菜单只能在滚动条上使用滚轮，而WPS可以直接在栏目中滚动，使用体验更佳）
    
## 简称
#### 此工具将使用某些简称代指游戏中的以下内容

    齿轮=开发资材
    螺丝=改修资材
    水桶=高速修复材
    喷枪=高速建造材
    助手=以明石（改）为旗舰的第一舰队中二号位的舰娘
    低阶=装备改修等级0~6
    高阶=装备改修等级7~10
    
## 助手相关说明
* 红色样式为当前装备含有换日前改修的助手，该助手前以★标识  
    例：20.3cm(3号)連装砲 月 ★三隈

* 当前装备在助手各种改造形态都可以进行的改修，该助手以其改造最低形态的名称显示，并且末尾无数字标识  
    例：381mm/50 三連装砲改 日 Littorio

* 当前装备在助手限定的改造形态才可以进行的改修，该助手以其限定的形态名称显示，末尾数字代表其受限形态的改造阶段，以[限]为标识  
    例：15.5cm三連装副砲改 日 武蔵1[限]
  * 为简化显示效果，限定形态为该船最低改造形态时，该[限]标识将省略  
    例：32号対水上電探改 土 ★伊勢、日向0
  * 并且当限定形态是该助手的最终改修形态时，该[限]标识亦将省略  
    例：203mm／53 連装砲 日 Zara2

* 本表默认使用者拥有所有助手的最高改造形态，当助手在低级形态可以全日改修，但高级形态只适用换日改修时，该高级形态将以★标识  
    例：46cm三連装砲 日 武蔵0、★武蔵1

* 有少数装备存在升级限制，当指定助手可进行升级，而其余助手无法升级时，可进行升级的助手将以[更]标识  
    例：8cm高角砲 日 阿賀野、能代、矢矧[更]
  * 当遇到该日所有指定助手都不能进行升级的情况，每位助手将以[更×]标识  
    例：8cm高角砲 土 阿賀野[更×]、能代[更×]
  * 两种情况一起出现时，特定情况更少发生的形态才有标识  
    例：25mm三連装機銃 水 五十鈴2、村雨2、(摩耶0、1[限])[更×]、摩耶2、皐月2

* 有少数装备存在升级分支，当指定助手可向特定分支升级时，该助手将以[支]标识  
    此表格的升级分支设定如下：  
    九三式水中聴音機→四式水中聴音機  
    94式高射装置→12.7cm高角砲＋高射装置  
    大発動艇→特大発動艇  
    例：大発動艇 日 あきつ丸、皐月2、阿武隈2、鬼怒2[支]
    
## 自行维护说明
#### 关于数据更新
    
作者直到弃游/停运/改修工厂机制出现重大变化，致使此工具失效为止，都会持续进行数据部分的更新  
——因为我自己就要用。

#### 关于内容更新
    
如果你觉得现有界面不需调整即可适用，更新时直接下载新版本的文件，删除旧文件即可。  
    
如果你调整过表格格式，重新设定了字号、行列宽等样式，则先下载新版本文件，  
再打开新旧两个表格，复制旧表格中你修改过的区域（如果架构和内容没变，直接全选），  
粘贴到新版本文件中对应的区域，选择只粘贴格式，即可完成更新。  
    
如果你还修改了表格内容，则需要自行考虑适配的方法。  
    
你也可以自行维护数据，数据表格初始为隐藏状态，解除隐藏后可见。  
    
最后，由于这个表格不是命令行敲出来的，所以放到Github上也没办法做diff对比（是这样吗？），  
只能用上版本控制，加上这个项目也是半路出家，一开始就没打算放在github上，  
所以有兴趣使用的请自行下载。  
（至于怎么fork，pull我是不懂的，我不是程序员，第一次用Github，就这样凑合吧）
