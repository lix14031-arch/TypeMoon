# TypeMoon V3-阶段验收

本次登记保留基线的 72 套常规素材，新增 14 套 FSN（UBW/HF）角色；累计 86 套。本批不代表 Fate/Zero 或 Fate/stay night 全部完成。

FZ 中用户明确验收 6 套；另有 27 套按用户委托完成主审及独立复审，最终由用户总览验收。吉尔·德·雷-FZ 已按用户要求逐张重制六种表情，单独列为待用户验收。各类状态分别记录，不将委托复审或重制结果写成用户逐套明确验收。

完整作品 JSON、正文设定和输出提示词仅保留在本地，不在此仓库发布。V2已冻结；后续已审角色的映射写入本地V3。既有图片目录保持稳定。

- 普通六表情角色共 86 套：FGO 10、TSUKI-R 23、FZ 34、FSN 19；另有 1 个仅含 untrusted 的登记键，全部登记键共 87 个。
- 图片共 496 个文件；此次仅新增 FSN 112 个文件（每角色六张 PNG、两个 WebP）。基线原有 384 个图片文件及其角色图片链接均保留。
- 六帧顺序为 happy、angry、sad、laugh、neutral、confused。
- avatars.webp 为 768×128；portraits.webp 为 3072×384；FZ / FSN 表情 PNG 为 512×512；独立单态 PNG 保留锁定的原生尺寸，均保留透明通道。
- data-portrait 使用 manifest.json 的完整角色键。
- untrusted（未获得基础信任）仅登记：兰斯洛特-FZ、莫德雷德-FGO。仅面具/头盔遮面角色可用，眼罩不单独作为理由；六个常规表情露出面容。专用 WebP 重复同一帧六次，沿用原样式默认80%位置。
- 单态登记只提供 untrusted，不表示六个常规表情已经制作；获得基础信任或使用常规表情时 data-portrait 留空。
- 莫德雷德-FGO：FGO Fandom Wiki sprite gallery; actual downloaded source（https://fategrandorder.fandom.com/wiki/Sub:Mordred/Gallery）；https://static.wikia.nocookie.net/fategrandorder/images/7/76/S076_Sheet_Stage1.webp/revision/latest；Mooncell identity and Stage1 appearance cross-check only; not source of this downloaded sprite（https://fgo.wiki/w/莫德雷德）

默认图片链接引用 0e28a7f27af7706acaeda4875ecc94895ca1be1e。仅吉尔·德·雷-FZ 的六张 PNG 与两个派生 WebP 已替换，独立引用 be9b5a31a23d79ad14dc57c8333f295d30f848e7；manifest 中该角色的 assetRef 和图片 URL 以此为准。其他角色素材及图片链接不变。六张新表情逐张生成，仍待用户验收。

|副本|角色登记键|验收状态|
|---|---|---|
|FGO|玛修-FGO|原有素材保留|
|FGO|阿尔托莉雅·潘德拉贡（Saber）-FGO|原有素材保留|
|FGO|卫宫（Archer）-FGO|原有素材保留|
|FGO|库·丘林（Lancer）-FGO|原有素材保留|
|FGO|吉尔伽美什（Archer）-FGO|原有素材保留|
|FGO|贞德-FGO|原有素材保留|
|FGO|玉藻前-FGO|原有素材保留|
|FGO|尼禄-FGO|原有素材保留|
|FGO|冲田总司-FGO|原有素材保留|
|FGO|伊什塔尔-FGO|原有素材保留|
|TSUKI-R|远野志贵-TSUKI-R|原有素材保留|
|TSUKI-R|爱尔奎特（日常）-TSUKI-R|原有素材保留|
|TSUKI-R|爱尔奎特（真祖公主）-TSUKI-R|原有素材保留|
|TSUKI-R|希耶尔-TSUKI-R|原有素材保留|
|TSUKI-R|远野秋叶-TSUKI-R|原有素材保留|
|TSUKI-R|翡翠-TSUKI-R|原有素材保留|
|TSUKI-R|琥珀-TSUKI-R|原有素材保留|
|TSUKI-R|弓冢五月-TSUKI-R|原有素材保留|
|TSUKI-R|乾有彦-TSUKI-R|原有素材保留|
|TSUKI-R|尼禄·卡欧斯-TSUKI-R|原有素材保留|
|TSUKI-R|远野四季-TSUKI-R|原有素材保留|
|TSUKI-R|罗亚-TSUKI-R|原有素材保留|
|TSUKI-R|苍崎青子-TSUKI-R|原有素材保留|
|TSUKI-R|诺艾尔-TSUKI-R|原有素材保留|
|TSUKI-R|马里奥-TSUKI-R|原有素材保留|
|TSUKI-R|弗洛夫-TSUKI-R|原有素材保留|
|TSUKI-R|阿良句博士-TSUKI-R|原有素材保留|
|TSUKI-R|斋木业人-TSUKI-R|原有素材保留|
|TSUKI-R|斋木澪-TSUKI-R|原有素材保留|
|TSUKI-R|安藤裕吾-TSUKI-R|原有素材保留|
|TSUKI-R|卡利乌斯-TSUKI-R|原有素材保留|
|TSUKI-R|远野槙久-TSUKI-R|原有素材保留|
|TSUKI-R|猫姬-TSUKI-R|原有素材保留|
|FZ|远坂时臣-FZ|用户明确验收|
|FZ|吉尔伽美什-FZ|用户明确验收|
|FZ|卫宫切嗣-FZ|用户明确验收|
|FZ|间桐樱-FZ|用户明确验收|
|FZ|间桐脏砚-FZ|用户明确验收|
|FZ|间桐雁夜-FZ|用户明确验收|
|FZ|娜塔莉亚·卡明斯基-FZ|用户委托复审通过，待总览验收|
|FZ|兰斯洛特-FZ|用户委托复审通过，待总览验收|
|FZ|伊斯坎达尔-FZ|用户委托复审通过，待总览验收|
|FZ|远坂葵-FZ|用户委托复审通过，待总览验收|
|FZ|索拉·娜泽莱·索菲亚莉-FZ|用户委托复审通过，待总览验收|
|FZ|阿尔托莉雅·潘德拉贡-FZ|用户委托复审通过，待总览验收|
|FZ|爱丽丝菲尔·冯·爱因兹贝伦-FZ|用户委托复审通过，待总览验收|
|FZ|久宇舞弥-FZ|用户委托复审通过，待总览验收|
|FZ|伊莉雅丝菲尔·冯·爱因兹贝伦-FZ|用户委托复审通过，待总览验收|
|FZ|远坂凛-FZ|用户委托复审通过，待总览验收|
|FZ|韦伯·维尔维特-FZ|用户委托复审通过，待总览验收|
|FZ|雨生龙之介-FZ|用户委托复审通过，待总览验收|
|FZ|吉尔·德·雷-FZ|按用户要求逐张重制，待用户验收|
|FZ|肯尼斯·埃尔梅罗·阿奇博尔德-FZ|用户委托复审通过，待总览验收|
|FZ|迪尔姆德·奥迪那-FZ|用户委托复审通过，待总览验收|
|FZ|言峰绮礼-FZ|用户委托复审通过，待总览验收|
|FZ|言峰璃正-FZ|用户委托复审通过，待总览验收|
|FZ|夏蕾-FZ|用户委托复审通过，待总览验收|
|FZ|卫宫矩贤-FZ|用户委托复审通过，待总览验收|
|FZ|卫宫切嗣（幼年）-FZ|用户委托复审通过，待总览验收|
|FZ|卫宫士郎（幼年）-FZ|用户委托复审通过，待总览验收|
|FZ|格伦·麦肯齐-FZ|用户委托复审通过，待总览验收|
|FZ|玛莎·麦肯齐-FZ|用户委托复审通过，待总览验收|
|FZ|琴音-FZ|用户委托复审通过，待总览验收|
|FZ|间桐鹤野-FZ|用户委托复审通过，待总览验收|
|FZ|尤布斯塔库哈依德·冯·爱因兹贝伦-FZ|用户委托复审通过，待总览验收|
|FZ|西蒙神父-FZ|用户委托复审通过，待总览验收|
|FZ|奥德·波尔扎克-FZ|用户委托复审通过，待总览验收|
|FGO|莫德雷德-FGO|仅 untrusted 单态；用户委托复审通过，待总览验收|

## FSN 本批追加（e93e909f19b4）

本批 5 套已完成主审和独立复审，状态为 `self-reviewed-awaiting-user`，仍待用户验收；不计为用户明确通过。每人六种常规表情、八个图片文件，独立固定引用 `e93e909f19b42f94012b9e712f75081da5dfac23`。旧角色、特殊状态和默认 assetRef 保持基线值。

仅通过 manifest 的完整中文登记键匹配 data-portrait；本批不新增裸姓名、简称或职阶的 data-speaker 回退。映射文件只登记图片变量，不修改正文布局 CSS、world_book 或输出模板。接入作品时需另行验证正文 CSS 的角色门控名单包含这些 FSN 键。

|副本|角色登记键|验收状态|
|---|---|---|
|FSN|卫宫士郎-FSN|自审及独立复审完成，待用户验收|
|FSN|阿尔托莉雅·潘德拉贡-FSN|自审及独立复审完成，待用户验收|
|FSN|远坂凛-FSN|自审及独立复审完成，待用户验收|
|FSN|间桐樱-FSN|自审及独立复审完成，待用户验收|
|FSN|卫宫（弓兵）-FSN|自审及独立复审完成，待用户验收|

## FSN 本批追加（f11bb5e5582a）

本批 14 套已完成主审和独立复审，状态为 `self-reviewed-awaiting-user`，仍待用户验收；不计为用户明确通过。每人六种常规表情、八个图片文件，独立固定引用 `f11bb5e5582aa86ea226c2845f54fa1a307b8576`。旧角色、特殊状态和默认 assetRef 保持基线值。

仅通过 manifest 的完整中文登记键匹配 data-portrait；本批不新增裸姓名、简称或职阶的 data-speaker 回退。映射文件只登记图片变量，不修改正文布局 CSS、world_book 或输出模板。接入作品时需另行验证正文 CSS 的角色门控名单包含这些 FSN 键。

|副本|角色登记键|验收状态|
|---|---|---|
|FSN|伊莉雅丝菲尔·冯·爱因兹贝伦-FSN|自审及独立复审完成，待用户验收|
|FSN|吉尔伽美什-FSN|自审及独立复审完成，待用户验收|
|FSN|库·丘林-FSN|自审及独立复审完成，待用户验收|
|FSN|柳洞一成-FSN|自审及独立复审完成，待用户验收|
|FSN|美杜莎-FSN|自审及独立复审完成，待用户验收|
|FSN|美狄亚-FSN|自审及独立复审完成，待用户验收|
|FSN|葛木宗一郎-FSN|自审及独立复审完成，待用户验收|
|FSN|言峰绮礼-FSN|自审及独立复审完成，待用户验收|
|FSN|间桐慎二-FSN|自审及独立复审完成，待用户验收|
|FSN|赫拉克勒斯-FSN|自审及独立复审完成，待用户验收|
|FSN|佐佐木小次郎-FSN|自审及独立复审完成，待用户验收|
|FSN|藤村大河-FSN|自审及独立复审完成，待用户验收|
|FSN|美缀绫子-FSN|自审及独立复审完成，待用户验收|
|FSN|塞拉-FSN|自审及独立复审完成，待用户验收|
