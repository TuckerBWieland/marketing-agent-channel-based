# Email Channel Guide

Rules and patterns for all email marketing work.

## Platform & Tools

- **ESP**: [Mailchimp / HubSpot / Klaviyo / SendGrid / etc.]
- **Template builder**: [Tool name]
- **List management**: [Where segments are defined]

## Compliance

### CAN-SPAM (US)
- Every email must include a physical mailing address
- Unsubscribe link must be visible and functional
- Subject lines must not be deceptive
- Honor opt-outs within 10 business days

### GDPR (EU)
- Requires explicit opt-in consent
- Must offer easy withdrawal of consent
- Include link to privacy policy

<!-- TODO: Add any industry-specific email regulations. -->

## Email Types

| Type | Purpose | Cadence | Approval needed? |
|------|---------|---------|------------------|
| Newsletter | Regular updates, content roundup | [Weekly/Biweekly] | [Yes/No] |
| Product update | Feature announcements | As needed | [Yes/No] |
| Nurture/drip | Lead education sequences | Automated | [Yes/No] |
| Promotional | Sales, offers, events | [Frequency] | [Yes/No] |
| Transactional | Receipts, confirmations | Triggered | No |

## Subject Lines

### Rules
- **Length**: 40-60 characters (mobile preview cuts at ~35)
- **Preview text**: Always set — don't let it default to "View in browser"
- Never use ALL CAPS
- Limit emoji to one per subject line, if any

### Formulas that work
- **Question**: "Ready to [achieve outcome]?"
- **How-to**: "How to [solve problem] in [timeframe]"
- **Number**: "[Number] ways to [achieve outcome]"
- **Curiosity gap**: "[Relevant topic] — and what it means for [audience]"

<!-- TODO: Add your top-performing subject line examples. -->

## Template Structure

### Newsletter
```
1. Header (logo + navigation)
2. Hero section (one primary story/CTA)
3. 2-3 secondary content blocks
4. Footer (social links, unsubscribe, address)
```

### Promotional
```
1. Header
2. Value proposition headline
3. Supporting details (2-3 bullet points)
4. Primary CTA button
5. Social proof (optional)
6. Footer
```

### Design rules
- Max width: 600px
- Primary CTA button: minimum 44px tap target
- Body font size: 16px minimum
- One primary CTA per email

## Segmentation

| Segment | Definition | Use for |
|---------|-----------|---------|
| [Active customers] | [Purchased in last 90 days] | [Product updates, upsells] |
| [Engaged leads] | [Opened 2+ emails in 30 days] | [Nurture content] |
| [Cold leads] | [No engagement in 90+ days] | [Re-engagement campaigns] |

<!-- TODO: Define your core segments. -->

## A/B Testing

- **Default split**: 20% test / 80% winner
- **Test one variable at a time**: subject line OR send time OR CTA — not multiple
- **Wait time before declaring winner**: [Hours]
- **Priority**: Subject line > Send time > CTA copy > Design

## Send Cadence & Timing

- **Max frequency**: No contact receives more than [N] emails per week
- **Best send times**: [Day(s)] at [Time(s)] [Timezone]
- **Quiet hours**: No sends between [time] and [time]

## Metrics

| Metric | Target | Red flag |
|--------|--------|----------|
| Open rate | [X%] | Below [Y%] |
| Click-through rate | [X%] | Below [Y%] |
| Unsubscribe rate | Below [X%] | Above [Y%] |
| Spam complaint rate | Below 0.1% | Above 0.1% |
