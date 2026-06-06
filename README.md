# Business Email (Hermes Agent Skill)

A skill for Hermes Agent that helps you write professional English emails — concise, direct, and culturally aware. Two modes: Casual (for colleagues) and Formal (for clients, bosses, elders).

Built with Japanese business culture in mind, but works for any professional setting.

## Features

- **Two modes** — Casual for teammates, Formal for clients/bosses/elders
- **Concise by design** — No weather talk, no fluff. Every sentence earns its place.
- **Japanese business culture aware** — "San" honorifics, indirect politeness, 和 (wa)
- **Simple English** — Plain words, short sentences. No "utilise" or "herein."
- **Templates included** — Openings, requests, closings, apologies, thank-yous, declining
- **Self-check list** — Quick tone check before sending

## Installation

### Via Hermes Skills Hub

```bash
hermes skills install Biw69-dev/business-email
```

### Manual

```bash
# Clone to your Hermes skills directory
git clone https://github.com/Biw69-dev/business-email.git ~/.hermes/skills/email/business-email
```

Then reload skills:

```bash
hermes skills reload
# or in-session: /reload-skills
```

## Usage

Just tell Hermes what you need:

> "Write an email to Tanaka-san to follow up on the AIP project."

The skill will ask you:
1. Formal or casual?
2. Who is the recipient?
3. What is the purpose?
4. What details?

Then produce a clean, ready-to-send email.

## Modes

| | Casual | Formal |
|---|--------|--------|
| **For** | Colleagues, daily team, follow-ups | Clients, bosses, senpai, first contact, serious topics |
| **Sentences** | 4–8 | 6–10 |
| **Opening** | 0–1 line or skip | Short greeting ("Hope you've been well.") |
| **Request** | "Could you…?" | "I would appreciate it if you could…" |
| **Closing** | "Thanks," | "Thank you for your time," |

## Examples

### Casual

```
Dear Tanaka-san,

Following up on the AIP timeline. Could you check if the spec is ready?

Thanks,

Biw
```

### Formal

```
Dear Yamamoto-san,

Hope you've been well. I'm reaching out regarding the PLC controller documentation.

I understand you are busy, but I would appreciate it if you could share the latest MC Protocol specs for the T20A firmware.

Thank you for your time,

Biw
```

## Structure

```
[Subject] Short, clear

Dear [Name]-san,

[One sentence opening — skip if casual]

[Context — 1-2 sentences]

[Main point — 1 sentence]

[Closing line],

[Name]
```

## Author

**Biw69-dev** — via Hermes Agent, Nous Research

## License

MIT
