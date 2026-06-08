# Back LLM Radar - AI API Status Badges

Live AI API status badges for OpenAI, Claude, Gemini, DeepSeek, Groq and Mistral.

Use these badges in your GitHub README, developer docs, API gateway dashboards, internal runbooks, status pages, or monitoring pages.

[Website](https://backllmradar.com/) ·
[README Badges](https://backllmradar.com/github-readme-badges/) ·
[API Status](https://backllmradar.com/status/) ·
[Latency Ranking](https://backllmradar.com/ai-api-latency-ranking/) ·
[Token Cost Calculator](https://backllmradar.com/calculator/)

---

## Live Badges

[![OpenAI API Status](https://backllmradar.com/api/v1/badge/openai.svg)](https://backllmradar.com/openai-api-status/)
[![Claude API Status](https://backllmradar.com/api/v1/badge/anthropic.svg)](https://backllmradar.com/claude-api-status/)
[![Gemini API Status](https://backllmradar.com/api/v1/badge/gemini.svg)](https://backllmradar.com/gemini-api-status/)
[![DeepSeek API Status](https://backllmradar.com/api/v1/badge/deepseek.svg)](https://backllmradar.com/deepseek-api-status/)
[![Groq API Status](https://backllmradar.com/api/v1/badge/groq.svg)](https://backllmradar.com/groq-api-status/)
[![Mistral API Status](https://backllmradar.com/api/v1/badge/mistral.svg)](https://backllmradar.com/mistral-api-status/)

---

## Copy Badge Markdown

### OpenAI

```markdown
[![OpenAI API Status](https://backllmradar.com/api/v1/badge/openai.svg)](https://backllmradar.com/openai-api-status/)
```

### Claude

```markdown
[![Claude API Status](https://backllmradar.com/api/v1/badge/anthropic.svg)](https://backllmradar.com/claude-api-status/)
```

### Gemini

```markdown
[![Gemini API Status](https://backllmradar.com/api/v1/badge/gemini.svg)](https://backllmradar.com/gemini-api-status/)
```

### DeepSeek

```markdown
[![DeepSeek API Status](https://backllmradar.com/api/v1/badge/deepseek.svg)](https://backllmradar.com/deepseek-api-status/)
```

### Groq

```markdown
[![Groq API Status](https://backllmradar.com/api/v1/badge/groq.svg)](https://backllmradar.com/groq-api-status/)
```

### Mistral

```markdown
[![Mistral API Status](https://backllmradar.com/api/v1/badge/mistral.svg)](https://backllmradar.com/mistral-api-status/)
```

---

## What is Back LLM Radar?

Back LLM Radar is a lightweight public monitoring and intelligence tool for AI API providers.

It tracks AI API status, endpoint reachability, probe latency, token cost references, and embeddable provider status badges for developers building AI applications, API gateways, agent frameworks, dashboards, and internal runbooks.

Back LLM Radar currently focuses on major AI API providers including:

* OpenAI
* Anthropic Claude
* Google Gemini
* DeepSeek
* Groq
* Mistral

---

## Use Cases

Back LLM Radar badges can be used in:

* GitHub README files
* AI application documentation
* LLM gateway dashboards
* Agent framework docs
* Internal API runbooks
* Developer monitoring pages
* Provider status pages
* Multi-provider AI infrastructure projects

Example use cases:

* Show OpenAI or Claude API reachability in your project README.
* Add live AI provider status badges to internal documentation.
* Compare AI API probe latency before choosing a fallback provider.
* Link your project users to public AI API status pages.
* Monitor whether a provider endpoint is reachable from the current Back LLM Radar probe region.

---

## Public API Endpoints

Back LLM Radar also provides public read-only API endpoints.

```bash
curl https://backllmradar.com/api/v1/status
curl https://backllmradar.com/api/v1/status/overview
curl https://backllmradar.com/api/v1/latency/ranking
curl https://backllmradar.com/api/v1/provider/openai
curl https://backllmradar.com/api/v1/provider/anthropic
curl https://backllmradar.com/api/v1/badge/openai.svg
```

These endpoints are designed for public status display, monitoring references, developer tools, and README badges.

---

## More Tools

* AI API Status Monitor: https://backllmradar.com/status/
* AI API Latency Ranking: https://backllmradar.com/ai-api-latency-ranking/
* AI Token Cost Calculator: https://backllmradar.com/calculator/
* LLM API Cost Comparison: https://backllmradar.com/llm-api-cost-comparison/
* GitHub README Badges: https://backllmradar.com/github-readme-badges/
* All Resources: https://backllmradar.com/resources/

---

## Related Provider Pages

* OpenAI API Status: https://backllmradar.com/openai-api-status/
* Claude API Status: https://backllmradar.com/claude-api-status/
* Gemini API Status: https://backllmradar.com/gemini-api-status/
* DeepSeek API Status: https://backllmradar.com/deepseek-api-status/
* Groq API Status: https://backllmradar.com/groq-api-status/
* Mistral API Status: https://backllmradar.com/mistral-api-status/

---

## Roadmap

* [x] Live AI API status badges
* [x] OpenAI, Claude, Gemini, DeepSeek, Groq and Mistral badge support
* [x] GitHub README Markdown snippets
* [x] Public badge SVG endpoints
* [x] AI API status monitor
* [x] AI API latency ranking
* [x] Token cost calculator
* [x] LLM API cost comparison
* [ ] Multi-region probe nodes
* [ ] Provider historical charts
* [ ] Badge usage analytics
* [ ] Webhook notifications
* [ ] BackGuard AI risk scanner integration

---

## Notes on Latency

Back LLM Radar measures **probe latency**.

Probe latency means the HTTP response time from the active Back LLM Radar probe node to each provider endpoint.

It does **not** represent full model inference latency, full chat completion time, time to first token, output generation speed, queueing time, or application-side processing time.

For production AI systems, provider selection should also consider:

* Model quality
* Token cost
* Error rate
* Timeout behavior
* Context length
* Fallback support
* Rate limits
* Gateway routing rules
* Budget controls

---

## Disclaimer

Status, latency and pricing data are provided for reference and monitoring purposes only.

Always verify official provider pricing, official service status, production API behavior, billing rules, and legal requirements before production billing, customer quotation, or operational decisions.

Back LLM Radar is a public monitoring and developer utility project. It is not an official status page for OpenAI, Anthropic, Google, DeepSeek, Groq, Mistral or any other provider.

---

## License

MIT License.
