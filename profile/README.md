<div align="center">

<img src="matangi-profile-hero.png" alt="Matangi Labs banner showing an instrument-style radar, traceable AI coworker artifacts, and the line AI coworkers you can run, inspect, and trust." width="100%" />

[![Website](https://img.shields.io/badge/Website-matangilabs.com-047857?style=for-the-badge)](https://matangilabs.com)
[![Kortny](https://img.shields.io/badge/Kortny-kortny.dev-047857?style=for-the-badge)](https://kortny.dev)
[![Kortny GitHub](https://img.shields.io/badge/GitHub-matangilabs%2Fkortny-047857?style=for-the-badge&logo=github&logoColor=white)](https://github.com/matangilabs/kortny)
[![Stars](https://img.shields.io/github/stars/matangilabs/kortny?style=for-the-badge&color=047857&logo=github&logoColor=white&label=Star%20Kortny)](https://github.com/matangilabs/kortny)
[![License](https://img.shields.io/github/license/matangilabs/kortny?style=for-the-badge&color=047857)](https://github.com/matangilabs/kortny/blob/main/LICENSE)

</div>

---

We build AI coworkers, not chatbots.

A chatbot answers when spoken to and forgets you the moment the tab closes. A coworker remembers what your team is working on, notices what needs doing, and acts inside the tools you already live in. That gap, judgment and memory and presence, is the whole product.

Matangi is the goddess of speech, music, knowledge, arts and learning. The name points us toward software that listens well, holds context, and responds in language that helps.

<img src="lab-standard.png" alt="The Matangi Labs standard: run, inspect, approve, and trust self-hosted AI coworker systems." width="100%" />

## Kortny

[**Kortny**](https://kortny.dev) is a self-hosted, Slack-native AI coworker. The code is open at [matangilabs/kortny](https://github.com/matangilabs/kortny).

Mention it in a thread and it plans, runs real work across the tools your team already uses, executes code in a sandbox, remembers how your team works, and posts the result back to the thread it came from. Underneath sit the surfaces that make it feel less like a bot and more like a colleague: workspace memory, a knowledge graph, ambient channel observation, approvals, and traceable execution.

It is open source and yours to run. Your data stays in your infrastructure, your approvals gate outward action, and you own the stack.

<img src="kortny-proof.png" alt="Kortny proof surface showing a Slack request becoming traceable work with visible plan, read, run, verify, post steps and approval state." width="100%" />

### How it compares

|  | **Kortny** | Hosted AI coworkers | Generic Slack bots |
|---|:---:|:---:|:---:|
| Where your data lives | **Your servers** | Vendor cloud | Vendor cloud |
| Runs on your infrastructure | ✅ | ❌ | ❌ |
| Executes real code and ships files | ✅ | sometimes | ❌ |
| Long-term memory plus knowledge graph | ✅ | varies | ❌ |
| Full audit log: every step and cost | ✅ | ❌ | partial |
| Bring-your-own LLM keys, no markup | ✅ | ❌ | ❌ |
| License | **Apache-2.0** | Proprietary | Proprietary |

### Run it in three commands

```sh
git clone https://github.com/matangilabs/kortny
cd kortny
cp .env.example .env   # add Slack and LLM keys, then:
docker compose up -d --force-recreate
```

**Runtime facts:** Python 3.11+, Docker Compose, Slack-native, Apache-2.0.
