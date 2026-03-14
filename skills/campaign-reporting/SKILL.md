# Campaign Reporting

Cross-channel reporting and attribution reference.

## KPI Definitions

Define metrics consistently across all channels:

| Metric | Definition | Source |
|--------|-----------|--------|
| MQL | [Your definition — e.g., lead with score >50] | [CRM/MAP] |
| SQL | [Your definition] | [CRM] |
| CAC | Total marketing spend / new customers acquired | [Finance + CRM] |
| LTV | [Your calculation method] | [Product/Finance] |
| ROAS | Revenue attributed / ad spend | [Ad platforms + CRM] |
| Engagement rate | (Likes + comments + shares) / impressions | [Social platforms] |

<!-- TODO: Align these definitions with your team. -->

## Attribution Model

We use **[first-touch / last-touch / linear / data-driven]** attribution.

<!-- TODO: Pick your model and explain why. -->

- **First-touch**: Credit to the channel that first brought the lead
- **Last-touch**: Credit to the last interaction before conversion
- **Linear**: Equal credit across all touchpoints
- **Data-driven**: Algorithmic weighting based on actual conversion paths

## Report Templates

### Weekly snapshot
- Channel-by-channel: spend, leads, conversion rate, CPA
- Pacing vs. monthly targets
- Top & bottom performing campaigns
- Action items for the week ahead

### Monthly review
- Full funnel: impressions > clicks > leads > MQLs > SQLs > customers
- Channel performance comparison
- Budget vs. actual spend
- Content performance (top 5 by engagement, top 5 by conversions)
- Recommendations for next month

### Campaign post-mortem
- Objective vs. result
- What worked, what didn't, what we'd change
- Cost per outcome vs. benchmark
- Learnings to apply to future campaigns

## UTM Standards

Reminder (defined in root CLAUDE.md):
```
utm_source=[channel]&utm_medium=[type]&utm_campaign=[campaign-slug]
```

Consistent UTM usage is the foundation of accurate attribution. Every link in every channel must have UTMs.

## Data Quality Rules

- Never combine data from different date ranges without noting it
- Always specify the date range and timezone in reports
- Round percentages to one decimal place
- Use consistent currency formatting
- Flag any known data gaps or tracking issues
