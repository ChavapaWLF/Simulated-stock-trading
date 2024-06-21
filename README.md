<p style="font-size: 26px; font-weight: bold" align="center">模拟炒股</p>
    <div align="center">
        <a>
            <img src="https://img.shields.io/badge/Version-1.0.0-00CC00">
        </a>
        <a href="https://t.me/chavapawlf" target="_blank">
            <img src="https://img.shields.io/badge/Telegram-chavapawlf-26A5E4?logo=Telegram">
        </a>
        <a href="https://github.com/ChavapaWLF" target="_blank">
            <img src="https://img.shields.io/badge/Github-ChavapaWLF-FC6D26?logo=github">
        </a>
        <a>
            <img src="https://img.shields.io/badge/QQ-3404420230-1EBAFC?logo=tencentqq">
        </a>
        <a>
            <img src="https://img.shields.io/badge/license-MIT-FF0000">
        </a>
    </div>
    <div align="center">
        <img src="https://s21.ax1x.com/2024/06/21/pkDUNrt.md.jpg" alt="“A股是全世界最大的知识付费平台”" title="ChatHistory" width="350">
    </div>

### 简介

欢迎来到~~全世界最大的~~模拟知识付费平台（bushi）。

你将拥有由 UCASer 自主研发的一只开放价格冒险股票。股票在一个被称作 **「A股」** 的幻想市场上流通，在这里，被机构选中的题材将被授予 **「涨停板」**，引导资金抱团。你将扮演一位名为 **「韭菜」** 的神秘角色，在剧烈的主升浪中邂逅精神失常、频繁操作的散户们，和他们一起被主力收割，见证连板的秘密——同时，逐步发掘 **「A股」** 的历史低点。

*~~注：以上为虚构背景，如与现实雷同纯属巧合。~~*

### 操作说明

本模拟器`1.0.0`版本支持三种游戏模式：

- **新手模式**：股票波动较小，波动值符合正态分布，无市场因素影响，单日涨跌幅限制为 $5\%$ ，适合从未接触过股市的初级投资者

- **进阶模式**：贴近实战，股票波动较大，波动值易受市场因素和宏观政策影响，单日涨跌幅限制为 $10\%$ ，适合对实盘有一定经验的投资者

- **末日模式**：股票波动极大，易受市场极端情绪影响出现暴涨和暴跌，无单日涨跌幅限制

主页面下方将会显示实时[日K线图](https://zh.wikipedia.org/wiki/K%E7%BA%BF)，在操作面板中输入相应份额进行“买入”或“卖出”操作即可（或直接点击“全仓买入”“全仓卖出”）。

### 机制说明

在本模拟器的 **新手模式** 中，每日波动值依据 *Box-Muller* 方法随机生成，符合正态分布；而在 **进阶模式** 和 **末日模式** 中，股价将受随机生成的新闻事件影响而出现异常波动。

若股价超过连续 $20$ 个交易日低于一元，股票将会被**强制退市**，游戏结束。

### Thanks

感谢github项目[stock-simulator](https://github.com/az13js/stock-simulator)提供的灵感

感谢[Shields.io](https://shields.io/)提供的徽标支持

感谢Wikipedia关于[Box-Muller](https://en.wikipedia.org/wiki/Box%E2%80%93Muller_transform)方法的介绍
