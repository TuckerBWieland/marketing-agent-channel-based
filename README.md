# Channel-Based

Organize agent guidance around **where the output ships** — email, social, blog, or paid. Each channel gets its own scoped rules because what's true for email (CAN-SPAM, subject line length) is irrelevant for SEO content.

## Who this is for

This template works best for **teams organized around channels** — where you have "the email person," "the social person," and "the SEO person," each with their own platform expertise, compliance requirements, and success metrics. It's a natural fit for agencies managing multiple channels for clients, or in-house teams where each channel has enough nuance that a single set of rules would be too noisy. If your team's org chart maps to marketing channels, your agent guidance should too.

## When to use this

- Your rules are heavily channel-specific
- Your team is organized by channel ("the email person," "the social person")
- You want agents to get deep, relevant context without wading through unrelated rules

## How to Use

1. **Clone this repo** into your project or marketing workspace
2. **Start with the root `CLAUDE.md`** — fill in your brand identity, voice, audiences, and legal rules
3. **Customize each channel's `CLAUDE.md`** in `channels/` — delete channels you don't use, tailor the rest to your platforms and workflows
4. **Update the skill files** in `skills/` — these are cross-channel references for segmentation, testing, competitive intel, and reporting
5. **Use Claude Code from the channel directory** that matches the task — `cd channels/email/` for email work, `cd channels/social/` for social work
6. **Add new channels** as needed — just `mkdir -p channels/new-channel` and create a `CLAUDE.md` in it
7. **Iterate** — when Claude gets something wrong, update the relevant file

## File structure

```
├── CLAUDE.md                              # Universal: brand, voice, legal, audiences
├── channels/
│   ├── email/
│   │   └── CLAUDE.md                      # Email-specific rules & templates
│   ├── social/
│   │   └── CLAUDE.md                      # Platform-specific social rules
│   ├── blog-and-seo/
│   │   └── CLAUDE.md                      # SEO guidelines & content structure
│   └── paid/
│       └── CLAUDE.md                      # Ad copy rules & platform policies
└── skills/
    ├── audience-segmentation/SKILL.md     # Cross-channel segmentation
    ├── ab-testing/SKILL.md                # Testing methodology
    ├── competitor-analysis/SKILL.md       # Competitive intel framework
    └── campaign-reporting/SKILL.md        # Reporting & attribution
```

## How context flows

```
Agent working in channels/email/
  reads: CLAUDE.md (universal rules)
  reads: channels/email/CLAUDE.md (email-specific rules)
  consults: skills/ (only when task requires it)
```

An agent drafting an email campaign gets brand voice + email rules. An agent writing a blog post gets brand voice + SEO rules. Neither gets the other's channel noise.

## Getting started

1. Fill in `CLAUDE.md` with your brand fundamentals
2. Customize each channel guide for your platforms and workflows
3. Delete channels you don't use
4. Add skills as you discover repeated corrections

## Adding a new channel

```bash
mkdir -p channels/new-channel
# Create channels/new-channel/CLAUDE.md with channel-specific rules
```
