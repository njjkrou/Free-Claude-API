<div align="center">

<img src="assets/hero.svg" width="100%" alt="AIFamily — 全球 AI 模型免费统一接入"/>

<br/>

[![🚀 免费注册，立即领取](https://img.shields.io/badge/🚀%20免费注册%20立即领取-%2300ff88?style=for-the-badge&labelColor=07070f&color=00ff88&logoColor=000)](https://api.aifamily.vip/)&nbsp;&nbsp;[![📖 查看文档](https://img.shields.io/badge/📖%20查看文档-3b82f6?style=for-the-badge&labelColor=07070f)](https://api.aifamily.vip/)&nbsp;&nbsp;[![💬 Discord](https://img.shields.io/badge/Discord-社区-5865F2?style=for-the-badge&logo=discord&logoColor=white&labelColor=07070f)](https://discord.gg/CT6apeE3M6)

</div>

---

<img src="assets/stats.svg" width="100%" alt="平台数据"/>

---

## 🎁 不是试用，是真·免费

<img src="assets/free.svg" width="100%" alt="三重免费额度"/>

<br/>

<div align="center">

| 🚫 无需绑定信用卡 | ♾️ 免费访问所有模型 | 📊 透明消费明细 | 🔄 额度每日自动刷新 |
|:---:|:---:|:---:|:---:|
| 注册即用，零门槛开始 AI 之旅 | GPT、Claude、Gemini 全部免费 | 每一笔调用详细记录 | 明天重新发放，长期稳定可用 |

</div>

---

## ✨ 为什么选择 AIFamily

<img src="assets/features.svg" width="100%" alt="核心优势"/>

---

## 📡 API 实时状态

<img src="assets/status.svg" width="100%" alt="实时状态"/>

---

## 🤖 全部模型 · 全部免费

<img src="assets/models.svg" width="100%" alt="模型列表"/>

---

## 🚀 5 分钟完成接入

**API Base URL**

```
https://api.aifamily.vip/v1
```

<details>
<summary><b>🐍 Python（推荐）</b></summary>

```python
# pip install openai
from openai import OpenAI

client = OpenAI(
    api_key="sk-your-api-key",
    base_url="https://api.aifamily.vip/v1"
)
response = client.chat.completions.create(
    model="gpt-4o",
    messages=[{"role": "user", "content": "Hello!"}],
    stream=True
)
for chunk in response:
    print(chunk.choices[0].delta.content, end="")
```

</details>

<details>
<summary><b>⚡ cURL</b></summary>

```bash
curl https://api.aifamily.vip/v1/chat/completions \
  -H "Authorization: Bearer sk-your-api-key" \
  -H "Content-Type: application/json" \
  -d '{"model":"claude-sonnet-4-6","messages":[{"role":"user","content":"Hi!"}]}'
```

</details>

<details>
<summary><b>🟨 Node.js</b></summary>

```javascript
import OpenAI from 'openai';

const client = new OpenAI({
    apiKey: 'sk-your-api-key',
    baseURL: 'https://api.aifamily.vip/v1'
});

const res = await client.chat.completions.create({
    model: 'gpt-4o',
    messages: [{ role: 'user', content: 'Hello!' }]
});
```

</details>

<details>
<summary><b>🔧 环境变量</b></summary>

```env
OPENAI_API_KEY=sk-your-api-key
OPENAI_BASE_URL=https://api.aifamily.vip/v1
```

</details>

---

## 🔌 兼容应用

<div align="center">

`ChatGPT-Next-Web` &nbsp; `LobeChat` &nbsp; `OpenCat` &nbsp; `ChatBox` &nbsp; `Cursor` &nbsp; `LangChain` &nbsp; `Dify` &nbsp; `FastGPT` &nbsp; `沉浸式翻译` &nbsp; `Continue.dev` &nbsp; `Open WebUI` &nbsp; `BotGem` &nbsp; 更多...

</div>

---

## 💬 用户评价

> ⭐⭐⭐⭐⭐ **"终于不用为每个 AI 平台单独维护接口了！AIFamily 让我的项目代码简洁了 80%，免费额度也完全够用。"**
>
> — **张明**，全栈开发者 · 深圳

> ⭐⭐⭐⭐⭐ **"响应速度真的很快！Claude 和 GPT-4 切换使用毫无压力，客服响应也很及时。强烈推荐！"**
>
> — **李婷**，AI 产品经理 · 北京

> ⭐⭐⭐⭐⭐ **"作为独立开发者，成本控制很重要。AIFamily 每天 $150 的免费额度让我能充分测试各种模型！"**
>
> — **王浩**，独立开发者 · 杭州

---

## 💎 订阅方案

<img src="assets/pricing.svg" width="100%" alt="订阅方案"/>

---

## ❓ 常见问题

<details>
<summary><b>Q：免费版真的完全免费吗？有什么限制？</b></summary>

是的，完全免费！每天可获得 $50 基础额度 + $50 签到 + 无上限邀请奖励。限制主要在于 API 请求速率（RPM/TPM），无需绑定信用卡。

</details>

<details>
<summary><b>Q：需要修改代码吗？支持哪些 API 格式？</b></summary>

不需要！100% 兼容 OpenAI 官方 API 格式，只需修改 `base_url` 和 `api_key` 两个参数即可，5 分钟完成迁移。

</details>

<details>
<summary><b>Q：如何保证 API 稳定性和数据安全？</b></summary>

多节点负载均衡，SLA 可用性达 99.9%，全程 HTTPS 加密，不存储任何对话内容。

</details>

<details>
<summary><b>Q：邀请奖励有上限吗？API 有地域限制吗？</b></summary>

邀请无上限，每成功邀请一位好友注册，双方各得 $50。API 无地域限制，全球任意地区均可访问。

</details>

<details>
<summary><b>Q：可以用于商业项目吗？</b></summary>

当然可以！建议商业生产环境使用付费套餐以获得更高稳定性和速率保障。

</details>

---

<img src="assets/footer.svg" width="100%" alt="AIFamily"/>

<div align="center">

[![Telegram](https://img.shields.io/badge/Telegram-加入频道-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://api.aifamily.vip/)&nbsp;&nbsp;[![Discord](https://img.shields.io/badge/Discord-加入社区-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/CT6apeE3M6)&nbsp;&nbsp;[![QQ](https://img.shields.io/badge/QQ群-465290922-EB1923?style=flat-square&logo=tencentqq&logoColor=white)](https://api.aifamily.vip/)&nbsp;&nbsp;[![Docs](https://img.shields.io/badge/文档-查看-3b82f6?style=flat-square)](https://api.aifamily.vip/)

</div>
