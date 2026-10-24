
# GPT-6 Astra PCB Art

> **ChatGPT, 与无限智慧交流的良伴**

>视频演示【[开源]谁不想要一个带NFC的GPT龙娘PCB呢-哔哩哔哩】 https://b23.tv/rteeCtj
## ⭐ Star History

[![Star History](https://raw.githubusercontent.com/alsunmengy/GPT-PCB-Art/main/.github/star-history/chart.svg)](https://github.com/alsunmengy/GPT-PCB-Art/stargazers)

[![Star this repo](https://img.shields.io/badge/⭐_Star_this_repo-点击支持-blue?style=for-the-badge)](https://github.com/alsunmengy/GPT-PCB-Art/stargazers)

> 🐉 GPT 拟人化龙娘「六 Astra」艺术纪念 PCB，嘉立创EDA开源硬件项目，双面彩色丝印 + 沉金描边，圆角卡片外形，无电气功能，纯收藏向工艺板。

## ⚠️ 购买 / 获赠前必读

> **这块板子不是商品，开源也不是卖货。** 在想要一块、或者打算买 / 收下之前，请先看完这条说明：
> **[关于我做出来的 PCB：赠送 / 售卖 / 开源](https://b23.tv/tJhAZ84)**
>
> - **开源协议**：CC BY-NC-SA 4.0 —— 个人可免费下载、学习、修改、自己打样，**禁止商用**。真的要卖，最多也就像我这样收个成本价。
> - **赠送**：第一批打样板我留一张，线下送朋友几张，其余放闲鱼「到付」——用闲鱼只是为了不暴露收货地址，到手可以直接申请仅退款，闲鱼标价只当作打赏（现在 10 元，早期 5 元，因为总有人不付邮费让我垫付）。
> - **想买**：送完之后还有人要，我会再订一批。成本约 10 元一张，闲鱼含邮费 20 元（邮费我出）。
> - **图片出处**：有一部分来自网络、有一部分自制，README 里都标注了原作者与原帖。
> - **找到我**：闲鱼 `alsun梦游` ｜ GitHub [`alsunmengy`](https://github.com/alsunmengy) ｜ Star 可选，不点也能用。

## 📖 项目简介
本项目为**纯艺术纪念PCB**，不具备电路功能，无走线、无电气网络，仅利用PCB板厂工艺实现双面精美图案输出。
主题角色：GPT 拟人化白龙少女「六 Astra」——白龙与智能核心共生的幻想域居民。正面为完整人设卡牌（金色 Logo + 金色边框花纹 + 角色档案 + 白龙娘立绘），背面为像素世界河畔夕阳下的白龙娘插画，采用**双面彩色丝印 + 金色沉金描边**实现边框花纹、Logo与文字信息，横向圆角卡片外形，可作为收藏摆件、挂件、桌面装饰。

板子规格：
- 建议使用5*8的CUID
- <img src="https://raw.githubusercontent.com/alsunmengy/GPT-PCB-Art/main/Screenshot_2026-10-17-21-36-10-919_com.xunmeng.pinduoduo-edit.jpg" width="480">
- 工程软件：嘉立创EDA专业版
- 基板材质：FR-4
- 板厚：1.6mm
- 外形：100mm × 60mm 横向圆角矩形卡片（R6 圆角）
- 工艺：双面彩色丝印，沉金描边/Logo/文字
- 功能：无电气电路，纯工艺艺术板

**工艺组合**
- 彩色丝印承载正反面全彩插画主体；
- 铜层 + 阻焊开窗 + 沉金实现金属质感的金色边框花纹、OpenAI Logo、标题与角色档案文字，区分普通丝印，成品有金属光泽；
- 横向圆角卡片外形，手感圆润，适合做桌面摆件、展示收藏。

完整开源工程，可直接导入嘉立创EDA，一键下单打样，也可自行修改图案、配色、文字进行二次创作。

## 📂 文件说明
```
GPT-PCB-Art/
├─ 素材/                           # 设计源素材（插画原图，可二次编辑）
├─ preview/                        # 成品预览图（正面 / 背面 2D 仿真）
├─ LICENSE                         # 开源协议（CC BY-NC-SA 4.0 全文）
└─ README.md                       # 项目说明文档
```

> 📦 工程源文件（`.epro2`）与 Gerber 压缩包统一在 [Releases](https://github.com/alsunmengy/GPT-PCB-Art/releases) 页面下载，请取最新版本。

## 🛠️ 使用方式
### 方式1：嘉立创EDA源工程
1. 打开嘉立创EDA专业版；
2. 文件 → 导入，选择从 [Releases](https://github.com/alsunmengy/GPT-PCB-Art/releases) 下载的 `.epro2` 工程文件（推荐最新版本）；
3. 核对：板厚、丝印工艺、阻焊层颜色；
4. 直接提交打样。

> ⚠️ 重要打样提醒
> 1. 需要在下单页开启**彩色丝印工艺**；
> 2. 金色边框、Logo、标题与档案文字依靠**沉金镀层**实现金属效果；
> 3. 本板无任何器件、无电气网络，下单时忽略“无走线”告警；
> 4. 彩色丝印存在轻微色彩偏差属于工厂正常现象。

### 方式2：Gerber生产文件
在 [Releases](https://github.com/alsunmengy/GPT-PCB-Art/releases) 下载对应版本的 Gerber 压缩包提交 PCB 工厂生产，注意和工厂确认支持**双面彩色丝印 + 沉金**工艺。

## 📋 打样参数（嘉立创下单页参考值）

板子为 2 层横向圆角卡片，下单时逐项核对下表即可：

| 参数 | 取值 |
|------|------|
| 板材类别 | FR-4 |
| 板子尺寸 | 10 cm × 6 cm |
| 板子层数 | 2 层 |
| 板子数量 | 按需选择（常见 5 / 10 片） |
| 成品板厚 | 1.6 mm（也可以更薄） |
| 外层铜厚 | 1 oz |
| 阻焊颜色 | 白色 |
| 字符颜色 | 黑色 |
| 阻焊覆盖 | 过孔盖油 |
| 焊盘喷镀 | 沉金（金色，1 u"，收费项） |
| 最小孔径 | 0.3 mm |
| 线路测试 | AOI 全测 + 飞针全测 |
| 交期 | 正常 3 天 |

> 💡 **彩色丝印**与**沉金**是本板效果的关键项（详见上方「重要打样提醒」）；其余为嘉立创默认选项，下单页如与本表有出入，以页面实际显示为准。

## 🎨 修改二次创作
你可以自由修改：
- 替换正反面插画素材；
- 修改角色档案文本、Logo排版；
- 修改板子尺寸、圆角大小；
- 调整镀层颜色、配色方案。

二次分发请遵守开源协议。

## 📜 开源协议
[![CC BY-NC-SA 4.0](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

本项目采用 **CC BY-NC-SA 4.0** 协议开源，协议全文见 [LICENSE](https://github.com/alsunmengy/GPT-PCB-Art/blob/main/LICENSE)，**无附加条款**。

- ✅ 允许：查看、学习、修改、本地打样、非商用分享、个人自用、无偿赠与；
- ❌ 禁止：任何形式的商业性生产、销售与分销；用于广告、品牌推广、商业引流；
- ℹ️ 衍生修改版本须**沿用相同协议**（SA），并**注明原项目来源与作者**（BY）。

## 🖼️ 预览

| 正面（顶层） | 背面（底层） |
| :---: | :---: |
| <img src="https://raw.githubusercontent.com/alsunmengy/GPT-PCB-Art/main/preview/front-2d.jpg" width="480"> | <img src="https://raw.githubusercontent.com/alsunmengy/GPT-PCB-Art/main/preview/back-2d.jpg" width="480"> |
<img src="https://raw.githubusercontent.com/alsunmengy/GPT-PCB-Art/main/IMG_20261017_211446.jpg" width="480">
<img src="https://raw.githubusercontent.com/alsunmengy/GPT-PCB-Art/main/IMG_20261017_211503.jpg" width="480">
<img src="https://raw.githubusercontent.com/alsunmengy/GPT-PCB-Art/main/IMG_20261017_211506.jpg" width="480">

**正面**：白龙少女「六 Astra」人设档案卡牌——金色 OpenAI Logo、金色边框花纹，右侧白龙娘立绘，左侧档案栏内容：

- **NAME**：六 Astra
- **SPECIES**：白龙与智能核心共生
- **AFFILIATION**：幻想域
- **AFFILIATION**：OpenAI 幻想域
- **ROLE**：高难度任务冲浪手
- **BIRTHDAY**：2025.12.16
- **INTRODUCE**：擅长把复杂任务拆解成风一样的步骤，推理、编码、研究与电脑操作都不在话下，反应快。

**背面**：像素世界河畔夕阳插画——白龙娘坐于水边，配木屋、竹林、苦力怕气泡等像素场景元素，金色礼服纹样呼应正面沉金线条。

## 📌 致谢
- 插画作者：B站 [@ZipZipPipe](https://b23.tv/oK72DdM)
- PCB 作者：B站 [@Alsun梦游](https://b23.tv/ZnkaGRq)
- PCB制作平台：嘉立创EDA

## README由爱弥斯/我共同编写
