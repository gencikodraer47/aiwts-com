# ⚡ WTS AI — 200+ Models. One API Key. Built for AI Content Creation.

**The Most Affordable AI Model Relay Hub. Optimized for Short-Drama, Comic & AI Content Creation. China Mainland Direct Connect.**

[![Website](https://img.shields.io/badge/Website-aiwts.com-1E90FF?logo=googlechrome&logoColor=white)](https://www.aiwts.com/) [![Models](https://img.shields.io/badge/Models-200+-00C853?logo=openai&logoColor=white)](https://www.aiwts.com/pricing) [![Pricing](https://img.shields.io/badge/Pricing-Save_70%25+-FF6600?logo=databricks&logoColor=white)](https://www.aiwts.com/pricing) [![Uptime](https://img.shields.io/badge/Uptime-99.99%25_SLA-7B00D4?logo=amazonaws&logoColor=white)](https://www.aiwts.com/)

---

## 🏢 Why WTS AI?

|  | **Other AI Proxies** | **WTS AI** |
|---|---|---|
| **Models** | 50–100 models | **200+ models** from 12+ providers |
| **Pricing** | 20–40% off official | **70%+ cheaper** than direct API |
| **Latest Models** | Lag behind, slow to add new | **GPT-5.6, Grok, Seedance 2.0, Claude 4.5, Gemini 3** — day-one access |
| **China Access** | Requires VPN/proxy | **Mainland China direct connect**, zero latency penalty |
| **Concurrency** | 10–50 concurrent, easy to throttle | **High concurrency** with smart routing & auto scaling |
| **Stability** | Frequent downtime, no SLA | **99.99% uptime SLA** with auto failover |
| **Content Creation** | Generic API relay | **Optimized for short-drama, comic & AI content creation** |
| **Support** | Discord/Telegram only | **Dedicated support** + ticketing + contact form |

---

## ⚡ 200+ Models. One API Key.

Stop managing 12 different API accounts. Access everything through WTS AI:

```
┌─────────────────────────────────────────────────────────────┐
│                    ONE API KEY → 200+ MODELS                │
├──────────────┬──────────────┬──────────────┬───────────────┤
│   OpenAI     │   Anthropic  │   Google     │     Meta      │
│  GPT-5.6     │ Claude 4.5   │ Gemini 3     │  Llama 3.3    │
│  GPT-4o      │ Claude 3.5   │ Gemini 2.0   │  Llama 3 70B  │
│  GPT-4o Mini │ Claude 3     │ Gemini Pro   │               │
├──────────────┼──────────────┼──────────────┼───────────────┤
│   xAI        │  DeepSeek    │  Qwen        │  Mistral      │
│  Grok        │ DeepSeek V3  │  Qwen 2.5    │  Mistral L.   │
│  Grok-2      │ DeepSeek R1  │  Qwen Max    │  Mixtral      │
├──────────────┼──────────────┼──────────────┴───────────────┤
│  Seedance    │  Cohere      │  Moonshot / Zhipu / MiniMax  │
│  Seed 2.0    │  Embed v3    │  ... and more providers      │
│  Video Gen   │              │  Full list at aiwts.com      │
└──────────────┴──────────────┴──────────────────────────────┘
```

### 📊 Model Coverage

| Category | Models | Highlights |
|---|---|---|
| **👑 LLM / Chat** | 80+ | GPT-5.6, Claude 4.5, Gemini 3, Grok, DeepSeek V3/R1, Qwen 2.5, Llama 3.3 |
| **🎨 Image Gen** | 40+ | DALL-E 3, Stable Diffusion, Flux, GPT Image 2 |
| **🎬 Video Gen** | 20+ | Seedance 2.0, Grok Video, text-to-video, image-to-video |
| **🎙️ Audio / TTS** | 30+ | Whisper, TTS, voice cloning |
| **🔢 Embeddings** | 20+ | text-embedding-3, BGE, Cohere Embed |
| **👁️ Vision / Multimodal** | 15+ | GPT-4V, Gemini Pro Vision, Claude Vision |

> 🔥 **Day-one access** to the latest models: GPT-5.6, Grok, Seedance 2.0, Claude 4.5, Gemini 3 — all available immediately upon release.

---

## 💰 Pricing That Actually Makes Sense

Volume discounts + smart routing = prices competitors can't match. **Register and get ¥10 free credits instantly — no credit card required.**

| Model | Official Price (1M tokens) | WTS AI | You Save |
|---|---|---|---|
| **GPT-4o** | $10.00 | **$2.50** | 75% |
| **GPT-4o Mini** | $0.60 | **$0.15** | 75% |
| **Claude 3.5 Sonnet** | $3.00 | **$0.90** | 70% |
| **Gemini 2.0 Pro** | $1.25 | **$0.35** | 72% |
| **DeepSeek V3** | $1.50 | **$0.30** | 80% |
| **Grok-2** | $5.00 | **$1.50** | 70% |
| **Llama 3.3 70B** | $1.00 | **$0.25** | 75% |
| **Seedance 2.0 (Video)** | $0.50/sec | **$0.15/sec** | 70% |

> 💡 Pay-per-token billing. Transparent pricing for all 200+ models at [aiwts.com/pricing](https://www.aiwts.com/pricing). New users get **¥10 free credits** on sign-up.

---

## 🚀 Built for High Concurrency & Low Latency

We run our **own infrastructure** with global edge nodes. No throttling. No "rate limit" games.

| Spec | Detail |
|---|---|
| **Requests / min** | 184,000+ |
| **Online Models** | 217+ |
| **P50 Latency** | 38ms |
| **Cross-Region Latency** | 42ms |
| **Auto Failover** | < 50ms |
| **Global Edge Nodes** | 14 regions worldwide |
| **Uptime SLA** | 99.99% |
| **Protocol** | HTTP/2 + SSE streaming |

```python
# Test concurrency yourself — works out of the box
import asyncio
from openai import AsyncOpenAI

client = AsyncOpenAI(
    api_key="wts-sk-...",
    base_url="https://api.wts.ai/v1"
)

async def send_request(i):
    return await client.chat.completions.create(
        model="gpt-4o",
        messages=[{"role": "user", "content": f"Say {i}"}]
    )

# Fire 500 requests simultaneously — go ahead
results = await asyncio.gather(*[send_request(i) for i in range(500)])
```

---

## 🌐 Global Smart Routing Network

14 edge regions, real-time interconnected. Requests auto-route to the lowest-latency path.

```
┌─────────────────────────────────────────────────────────────┐
│              WTS · Global Anycast Backbone                  │
│           14 Pops · 48 Links · BGP Anycast                  │
├─────────────────────────────────────────────────────────────┤
│  🇨🇳 Beijing   🇨🇳 Shanghai   🇭🇰 Hong Kong   🇯🇵 Tokyo    │
│  🇰🇷 Seoul     🇸🇬 Singapore  🇦🇺 Sydney       🇮🇳 Mumbai    │
│  🇦🇪 Dubai     🇩🇪 Frankfurt  🇬🇧 London       🇺🇸 Virginia  │
│  🇺🇸 Silicon Valley           🇧🇷 São Paulo                 │
├─────────────────────────────────────────────────────────────┤
│  P50 Latency: 38ms │ Failover: <50ms │ Throughput: 18K req/s│
└─────────────────────────────────────────────────────────────┘
```

**China Mainland Direct Connect** — No VPN needed. Low latency from mainland China to all models.

---

## 🏗️ Enterprise-Grade Infrastructure

| Feature | Description |
|---|---|
| 🌐 **Global Edge** | 14 regions worldwide with BGP anycast routing |
| 🔒 **Data Privacy** | Your data is YOUR data. No-log policy. |
| ⏱️ **SLA** | 99.99% uptime guarantee |
| 🔄 **Auto Failover** | If one provider goes down, traffic auto-routes to alternatives |
| 📊 **Dashboard** | Real-time monitoring, usage analytics, cost breakdown |
| 💳 **Billing** | Pay-per-token, transparent pricing, multiple payment methods |
| 🔑 **API Key Management** | Secure key generation and management |
| 🎬 **Content Creation** | Optimized for short-drama, comic & AI content generation |
| 🇨🇳 **China Access** | Mainland China direct connect — no VPN required |

---

## 🔌 Instant Integration

Fully compatible with the OpenAI SDK format. **Zero migration effort — change ONE line.**

```python
# 1. Install OpenAI SDK
pip install openai

# 2. Change ONE line — that's it
from openai import OpenAI

client = OpenAI(
    api_key="wts-sk-...",                    # ← Your WTS API key
    base_url="https://api.wts.ai/v1"         # ← Only this changes
)

# 3. Everything else stays exactly the same
stream = client.chat.completions.create(
    model="claude-3.5-sonnet",
    messages=[{"role": "user", "content": "Hello WTS AI!"}],
    stream=True
)

for chunk in stream:
    print(chunk.choices[0].delta.content or "", end="")
```

### Works with Everything You Already Use

| SDK / Framework | Compatible? | How |
|---|---|---|
| OpenAI Python SDK | ✅ | Change `base_url` |
| OpenAI Node.js SDK | ✅ | Change `baseURL` |
| LangChain | ✅ | Set `openai_api_base` |
| LlamaIndex | ✅ | Set `api_base` |
| Vercel AI SDK | ✅ | Change `baseURL` |
| LiteLLM | ✅ | Set `custom_llm_provider: openai` |
| Anything OpenAI-compatible | ✅ | Change endpoint URL |

### cURL — No SDK Needed

```bash
curl https://api.wts.ai/v1/chat/completions \
  -H "Authorization: Bearer wts-sk-YOUR_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "gpt-4o",
    "messages": [{"role": "user", "content": "Write a startup pitch in 3 sentences"}]
  }'
```

---

## 🎬 Optimized for AI Content Creation

WTS AI is specifically tuned for **short-drama (短剧), comic (漫剧), and AI content creation** workflows:

- **🎬 Short-Drama Generation** — Integrated with [wtsdj.mom](https://www.wtsdj.mom/) for AI-powered drama production
- **🎨 Image Generation** — Built-in image gen at [wtsgf.mom](https://www.wtsgf.mom/)
- **🗣️ Voice & TTS** — Voice cloning, multi-language dubbing
- **📹 Video Generation** — Seedance 2.0, Grok Video, text-to-video & image-to-video
- **📝 Script Writing** — LLM-powered script generation with GPT-5.6, Claude 4.5

---

## 🚀 Getting Started

### 1. Sign Up

Visit **[aiwts.com](https://www.aiwts.com/)** and create an account in 30 seconds.

### 2. Get Free Credits

New users receive **¥10 free credits** to test any model — no credit card required.

### 3. Get Your API Key

Navigate to the dashboard → API Keys → Generate Key.

### 4. Make Your First Call

```python
from openai import OpenAI

client = OpenAI(
    api_key="wts-sk-YOUR_KEY",
    base_url="https://api.wts.ai/v1"
)
response = client.chat.completions.create(
    model="gpt-4o",
    messages=[{"role": "user", "content": "Hello!"}]
)
print(response.choices[0].message.content)
```

That's 4 lines of code. You're live. 🚀

---

## 🔗 Links

| Link | Description |
|---|---|
| 🌐 **[aiwts.com](https://www.aiwts.com/)** | Official website & model playground |
| 📖 **[API Docs](https://aiwts.apifox.cn/)** | Full API documentation |
| 💰 **[Pricing](https://www.aiwts.com/pricing)** | Transparent pricing for all 200+ models |
| 🎬 **[Short-Drama Gen](https://www.wtsdj.mom/)** | AI-powered short-drama production platform |
| 🎨 **[Image Gen](https://www.wtsgf.mom/)** | Online AI image generation tool |
| 📧 **[Contact](https://www.aiwts.com/contact)** | Enterprise inquiries & support |

---

## 📄 License

MIT License — see [LICENSE](./LICENSE) for details.

---

### ⚡ Access 200+ AI Models. Save 70%+. China Mainland Direct Connect.

**[Start Building for Free →](https://www.aiwts.com/sign-up)**

*WTS AI — Smart AI Gateway. Real infrastructure. Real savings. Built for creators.*
