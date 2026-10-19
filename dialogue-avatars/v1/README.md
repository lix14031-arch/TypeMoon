# 型月对白头像 · 第一批

10 个角色，每人六种真实表情差分。顺序为喜 happy、怒 angry、哀 sad、乐 laugh、平静 neutral、迷惑 confused。普通角色均为 JP 第一灵基；玛修为 2026-08-12 实装的常夏泳装 Ver.03（8002100）。

每角色的 avatars.webp 是六张128×128头像组成的横向图集；portraits.webp 是六张512×384完整半身图组成的横向图集。CSS 根据 data-face 自动定位，不需要手动切换控件，也不需要聊天时请求 Atlas API。

manifest.json 逐项保存原始图片来源、faceId、坐标、哈希与近似说明。≈ 类别只表示最接近的原始表情，不代表原游戏明确标注这一情绪。原始素材版权归各权利方；此仓库不改变其归属。

直接打开 index.html 可预览。say-avatar.css 使用本仓库 raw 图片直链；say-avatar.local.css 使用相对路径用于本地预览。作品完整 JSON 未上传到本公共仓库。

## 输出样例

`<say class="npc" data-speaker="玛修" data-portrait="mash" data-face="happy"><button type="button" class="say-avatar" aria-label="查看角色立绘"></button>“前辈，大家都回来了。”</say>`

图片仅影响UI，不改变剧情人物设定。未知身份和未登记角色不输出专属头像。
