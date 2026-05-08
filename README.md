# Vapi (vapi)

Vapi is a voice AI agents platform for building, testing, and deploying real-time voice agents across phone, web, and SIP. The Vapi REST API exposes assistants, calls, chats, campaigns, phone numbers, tools, files, squads, sessions, structured outputs, and analytics, plus server/client webhook events.

**APIs.json:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/vapi/refs/heads/main/apis.yml)

## Type
- **x-type:** company

## Tags
- AI, Voice, Agents, Realtime, CPaaS

## APIs
1. **Vapi Platform API** — REST API at `https://api.vapi.ai` for managing assistants, calls, phone numbers, tools, chats, campaigns, and analytics. OpenAPI spec at [`openapi/vapi-openapi.yml`](openapi/vapi-openapi.yml).
2. **Vapi Webhooks API** — Server- and client-side webhook events for end-of-call reports, transcripts, function calls, and tool invocations.

## Common Properties
- [Website](https://vapi.ai/)
- [Documentation](https://docs.vapi.ai/)
- [OpenAPI](openapi/vapi-openapi.yml)
- [Plans](plans/vapi-plans-pricing.yml) — reconciled
- [RateLimits](rate-limits/vapi-rate-limits.yml) — partial (concurrency documented; HTTP RPS not public)
- [FinOps](finops/vapi-finops.yml) — reconciled

## Pricing Snapshot
- Vapi platform fee: ~$0.05/min orchestration only
- Realistic all-in cost (with transcription, LLM, TTS, telephony): $0.07–$0.25/min
- Enterprise: custom contracts with volume discounts

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
