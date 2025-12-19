# SEO Content Workflow

```
PHANTOM ENGINEER / SEO-Content-Machine
AI-Powered Content Optimization
```

## Overview

Systematic workflow for creating SEO-optimized content using AI agents. From keyword research to published article in 4 phases.

## Phase 1: Research

### Keyword Discovery
1. **Seed Keywords**: Start with 3-5 core topic terms
2. **Expansion**: Use tools to find related keywords
3. **Clustering**: Group keywords by intent

### Keyword Evaluation Matrix

| Factor | Weight | Scoring |
|--------|--------|---------|
| Search Volume | 25% | 1K+ = high, 100-1K = medium, <100 = low |
| Competition | 25% | KD < 30 = easy, 30-50 = medium, 50+ = hard |
| Intent Match | 30% | Informational/Commercial/Transactional fit |
| Trend | 20% | Rising, stable, or declining |

### Competitor Analysis
- Top 5 ranking pages for primary keyword
- Content length and structure
- Backlink profile
- Content gaps and opportunities

## Phase 2: Planning

### Content Brief Template
```markdown
# [Primary Keyword] Content Brief

## Target Keywords
- Primary: [keyword] (volume: X, KD: Y)
- Secondary: [keyword], [keyword], [keyword]
- LSI: [keyword], [keyword], [keyword]

## Search Intent
[Informational/Commercial/Transactional]

## Target Word Count
[Based on competitor average + 20%]

## Required Sections
1. [H2: Section Title]
2. [H2: Section Title]
3. [H2: Section Title]

## Questions to Answer
- [Question from PAA/forums]
- [Question from PAA/forums]
- [Question from PAA/forums]

## Competitor Gaps
- [Topic they missed]
- [Angle not covered]
```

## Phase 3: Creation

### AI Agent Workflow

1. **IDEAGEN**: Generate 30 headline options
2. **SEXYO**: Structure and optimize outline
3. **LANGSTON**: Write long-form content

### Content Structure

```
Title (H1) - Primary keyword, compelling hook
├── Intro - Hook, promise, credibility
├── H2 - Main topic 1
│   ├── H3 - Subtopic
│   └── H3 - Subtopic
├── H2 - Main topic 2
│   ├── H3 - Subtopic
│   └── H3 - Subtopic
├── H2 - Main topic 3
├── FAQ (H2)
│   └── H3 questions (schema markup)
└── Conclusion - Summary, CTA
```

### On-Page Optimization Checklist

**Title Tag:**
- [ ] Primary keyword in first 60 characters
- [ ] Compelling hook or number
- [ ] Brand name (if space)

**Meta Description:**
- [ ] Primary keyword included
- [ ] Clear value proposition
- [ ] Call to action
- [ ] Under 155 characters

**Content:**
- [ ] Primary keyword in first 100 words
- [ ] Keyword density 1-2%
- [ ] LSI keywords naturally distributed
- [ ] Internal links (3-5 minimum)
- [ ] External links to authority sources
- [ ] Images with alt text

**Structure:**
- [ ] Single H1 tag
- [ ] Logical H2/H3 hierarchy
- [ ] Short paragraphs (3-4 sentences max)
- [ ] Bullet points and lists
- [ ] Table of contents for 2000+ words

## Phase 4: Publishing

### Pre-Publish Audit
1. Readability score (aim for Grade 8 or below)
2. Grammar and spelling check
3. Fact verification
4. Link validation
5. Image optimization

### Schema Markup
```json
{
  "@type": "Article",
  "headline": "[Title]",
  "author": {"@type": "Person", "name": "[Author]"},
  "datePublished": "[Date]",
  "image": "[Featured Image URL]"
}
```

### Post-Publish Actions
1. Submit URL to Google Search Console
2. Internal link from existing content
3. Share on social platforms
4. Monitor rankings (24h, 7d, 30d)

## Performance Tracking

### KPIs
- Organic traffic growth
- Keyword position changes
- Click-through rate
- Time on page
- Bounce rate

### Iteration Triggers
- Position 4-10: Optimize title/meta for CTR
- Position 11-20: Add content depth, get backlinks
- Position 20+: Major content refresh or rebuild

---

*Part of the [SEO-Content-Machine](https://github.com/DeadManOfficial/SEO-Content-Machine) workflow*
