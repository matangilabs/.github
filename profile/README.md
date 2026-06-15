<div align="center">

# Matangi Labs

### Building AI coworkers that live where your team works.

<img src="matangi-banner.png" alt="Matangi, goddess of speech and the inner word, playing the veena, rendered in the Matangi Labs emerald and gold instrument style" width="100%" />

[![Website](https://img.shields.io/badge/Website-matangilabs.com-047857?style=for-the-badge)](https://matangilabs.com)
[![Kortny](https://img.shields.io/badge/Kortny-kortny.ai-047857?style=for-the-badge)](https://kortny.ai)
[![Stars](https://img.shields.io/github/stars/matangilabs/kortny?style=for-the-badge&color=047857&logo=github&logoColor=white&label=Star%20Kortny)](https://github.com/matangilabs/kortny)
[![License](https://img.shields.io/github/license/matangilabs/kortny?style=for-the-badge&color=047857)](https://github.com/matangilabs/kortny/blob/main/LICENSE)
[![Discord](https://img.shields.io/badge/Discord-join-047857?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/pW2t5UfAtE)

</div>

---

We build AI coworkers, not chatbots.

A chatbot answers when spoken to and forgets you the moment the tab closes. A coworker remembers what your team is working on, notices what needs doing, and acts inside the tools you already live in. That gap, judgment and memory and presence, is the whole product.

We are named for Matangi, the goddess of speech, music, and the inner word. The name fits the work: software whose job is to listen well, hold context, and respond in language that helps.

## Kortny

[**Kortny**](https://kortny.ai) is our first coworker: a self-hosted, Slack-native AI teammate.

Mention it in a thread and it plans, runs real work across the 100+ tools your team already uses, executes code in a sandbox, remembers how your team works, and posts the result back to the thread it came from. Underneath sit the things that make it feel less like a bot and more like a colleague: a workspace memory, a knowledge graph, ambient channel observation, and proactive suggestions.

It is open source and yours to run. Your data stays in your infrastructure, your approvals gate every outward action, and you own the whole stack.

[![Kortny repo](https://github-readme-stats.vercel.app/api/pin/?username=matangilabs&repo=kortny&hide_border=true&bg_color=0C0F0E&title_color=10B981&icon_color=C9A227&text_color=9CA3A0)](https://github.com/matangilabs/kortny)

### How it compares

|  | **Kortny** | Hosted AI coworkers | Generic Slack bots |
|---|:---:|:---:|:---:|
| Where your data lives | **Your servers** | Vendor cloud | Vendor cloud |
| Runs on your infrastructure | ✅ | ❌ | ❌ |
| Executes real code & ships files | ✅ | sometimes | ❌ |
| Long-term memory + knowledge graph | ✅ | varies | ❌ |
| Full audit log: every step & cost | ✅ | ❌ | partial |
| Bring-your-own LLM keys (no markup) | ✅ | ❌ | ❌ |
| License | **Apache-2.0** | Proprietary | Proprietary |

### Run it in three commands

```sh
git clone https://github.com/matangilabs/kortny
cd kortny
cp .env.example .env   # add Slack + LLM keys, then:
docker compose up -d --force-recreate
