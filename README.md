# SEO Content Machine
## AI-Powered SEO Automation & Content Generation

> **"Research, write, optimize—all powered by AI."**

This is **Dead Man Posts'** fork/integration of [SEOmachine by Craig Hewitt](https://github.com/TheCraigHewitt/seomachine)—a Claude Code workspace with custom commands and specialized agents for AI-powered SEO content workflows.

---

## 🎯 What is SEOmachine?

SEOmachine is a **Claude Code workspace** that turns Claude into a specialized SEO content assistant with:

**Custom Slash Commands:**
- `/research` - Deep keyword and topic research
- `/write` - AI-powered content generation with SEO optimization
- `/optimize` - Content analysis and improvement recommendations
- `/analyze` - Competitor content analysis

**Specialized Agents:**
- **Research Agent:** Keyword research, search intent analysis, competitor analysis
- **Writing Agent:** Long-form content generation, outline creation, SEO optimization
- **Optimization Agent:** Readability scoring, keyword density, meta tag optimization

**Why It's Valuable:**
- Automate 80% of SEO research and writing
- Maintain consistent quality and optimization
- Scale content production without sacrificing quality
- Data-driven decisions based on search data

---

## 🔗 Original Repository

**Source:** [https://github.com/TheCraigHewitt/seomachine](https://github.com/TheCraigHewitt/seomachine)

**Credit:** Created by Craig Hewitt (@TheCraigHewitt)

**License:** MIT (check original repo for latest)

**This Repository:** Dead Man Posts' integration and customization for our content workflows

---

## 🚀 How Dead Man Posts Uses SEOmachine

### Use Case 1: Blog Content for Algorithm Intelligence
**Workflow:**
1. `/research` - "TikTok algorithm 2025 updates"
2. Review keyword opportunities and search intent
3. `/write` - Generate 2000-word guide with SEO optimization
4. `/optimize` - Refine readability, keyword placement, meta tags
5. Publish to blog, distribute to social media

**Expected Outcome:**
- SEO-optimized content in 30 minutes vs. 4+ hours manual
- Data-backed keyword targeting
- Readability optimized for audience

---

### Use Case 2: YouTube Video Scripts
**Workflow:**
1. `/research` - "Sora 2 prompting techniques"
2. Identify trending search queries and questions
3. `/write` - Generate video script optimized for keywords
4. Adapt script for YouTube SEO (title, description, tags)
5. Record video, optimize metadata

**Expected Outcome:**
- SEO-informed content topics (not guessing)
- Script structure optimized for retention
- Keyword-rich metadata for discoverability

---

### Use Case 3: Competitive Analysis
**Workflow:**
1. `/analyze` - Competitor's top-performing content
2. Identify what's working (keywords, structure, topics)
3. `/research` - Gap analysis (what they're missing)
4. `/write` - Create better version with gaps filled
5. Outrank competitor with superior content

**Expected Outcome:**
- Strategic content that targets competitor weaknesses
- Data-driven topic selection
- Higher search rankings

---

## 📋 Core Commands

### `/research [topic]`
**Purpose:** Deep keyword and topic research

**What It Does:**
- Keyword research (volume, competition, intent)
- Search intent analysis
- Related topics and questions
- Competitor analysis

**Example:**
```
/research AI video generation tools 2025
```

**Output:**
- Primary keywords and search volumes
- Long-tail keyword opportunities
- Questions people are asking
- Content gap analysis

---

### `/write [outline or topic]`
**Purpose:** AI-powered content generation

**What It Does:**
- Generate long-form content (500-3000+ words)
- SEO-optimized structure
- Keyword integration (natural, not stuffed)
- Readability optimization

**Example:**
```
/write
Topic: Complete Guide to Sora 2 Prompting
Target Keywords: sora 2 prompts, ai video generation, prompt engineering
Tone: Expert but accessible
Length: 2000 words
```

**Output:**
- Fully written article with proper structure
- Keywords naturally integrated
- Meta title and description
- Internal linking suggestions

---

### `/optimize [content]`
**Purpose:** Content analysis and improvement

**What It Does:**
- Readability scoring (Flesch-Kincaid)
- Keyword density analysis
- SEO best practices check
- Improvement recommendations

**Example:**
```
/optimize
[Paste your content here]
Target keyword: TikTok algorithm
```

**Output:**
- Readability score and suggestions
- Keyword optimization recommendations
- Structure improvements
- Meta tag suggestions

---

### `/analyze [URL or content]`
**Purpose:** Competitor content analysis

**What It Does:**
- Analyze competitor content structure
- Keyword usage analysis
- Content quality assessment
- Gap identification

**Example:**
```
/analyze https://competitor.com/article
```

**Output:**
- What's working in their content
- Keywords they're targeting
- Gaps you can exploit
- Strategic recommendations

---

## 🛠️ Setup & Installation

### Prerequisites
- Claude Code installed
- Git installed
- Basic command line knowledge

### Installation Steps

**Option 1: Clone This Fork** (with Dead Man Posts customizations)
```bash
git clone https://github.com/DeadManOfficial/SEO-Content-Machine.git
cd SEO-Content-Machine
```

**Option 2: Clone Original** (vanilla SEOmachine)
```bash
git clone https://github.com/TheCraigHewitt/seomachine.git
cd seomachine
```

**Open in Claude Code:**
```bash
claude-code .
```

**Test Commands:**
```bash
/research AI content creation
```

---

## 🎨 Dead Man Posts Customizations

### Custom Agents Added

#### 1. **Thirst-Gravity SEO Agent**
**Purpose:** Optimize content using the Thirst-Gravity framework

**What It Does:**
- Analyzes content for Thirst (attention) and Gravity (value) balance
- Suggests improvements for hook strength
- Ensures value delivery meets search intent
- Optimizes for both engagement and SEO

**Usage:**
```
/thirst-gravity-optimize [content]
```

---

#### 2. **Algorithm-Aware Content Agent**
**Purpose:** Create content optimized for platform algorithms

**What It Does:**
- Considers TikTok, YouTube, Instagram algorithm preferences
- Optimizes for both search and social
- Suggests cross-platform distribution strategies
- Keyword research with platform-specific intent

**Usage:**
```
/algorithm-content [topic] [platform]
```

---

#### 3. **Creator Intelligence SEO Agent**
**Purpose:** SEO for creator-focused content

**What It Does:**
- Research what creators are searching for
- Optimize for creator keywords (high commercial intent)
- Structure content for creator audience
- Suggest content upgrades (templates, tools, resources)

**Usage:**
```
/creator-seo [topic]
```

---

## 📊 SEO Strategy Integration

### Dead Man Posts SEO Pillars

**Pillar 1: AI Media Engineering**
- Target keywords: "sora 2 prompts", "ai video generation", "prompt engineering"
- Content types: Guides, tutorials, case studies
- SEO strategy: In-depth technical content, long-form

**Pillar 2: Algorithm Intelligence**
- Target keywords: "tiktok algorithm", "youtube algorithm 2025", "viral content strategy"
- Content types: Analysis, frameworks, data reports
- SEO strategy: Timely updates, data-backed content

**Pillar 3: Brand Architecture**
- Target keywords: "content creator branding", "personal brand strategy", "archetype marketing"
- Content types: Frameworks, case studies, guides
- SEO strategy: Thought leadership, original frameworks

**Pillar 4: Creator Tools & Resources**
- Target keywords: "ai tools for creators", "video editing automation", "content calendar"
- Content types: Tool reviews, comparisons, tutorials
- SEO strategy: Commercial intent, affiliate potential

---

## 📈 Content Production Workflow

### Step-by-Step Process

**1. Topic Research (15 min)**
```bash
/research [topic idea]
```
- Validate search volume
- Identify keyword opportunities
- Understand search intent
- Check competition

**2. Content Brief (10 min)**
```bash
/write-brief [topic] [target keywords]
```
- Generate content outline
- Define structure
- Set word count target
- Identify required sections

**3. Content Creation (30-60 min)**
```bash
/write [brief]
```
- Generate full article
- SEO-optimized structure
- Natural keyword integration
- Compelling introduction and conclusion

**4. Optimization (15 min)**
```bash
/optimize [content]
```
- Readability improvements
- Keyword density check
- Meta tags optimization
- Internal linking

**5. Platform Adaptation (15 min)**
- Create social media excerpts
- Generate YouTube script version
- Design thumbnail concepts
- Plan distribution strategy

**Total Time:** ~90 minutes for fully optimized content
**Manual Process:** 4-6 hours

---

## 🎯 Performance Metrics

### SEO KPIs to Track

**Search Performance:**
- Organic traffic growth
- Keyword rankings (target top 3)
- Click-through rate (target >5%)
- Average position improvement

**Engagement Metrics:**
- Time on page (target >3 min for long-form)
- Bounce rate (target <50%)
- Pages per session
- Social shares

**Conversion Metrics:**
- Email signups from content
- Link clicks to other repositories
- Tool downloads/uses
- Consultation inquiries

**Content Quality:**
- Readability score (target 60-70 Flesch-Kincaid)
- Keyword coverage (target 3-5 primary, 10+ secondary)
- Content depth (target 2000+ words for guides)
- Update frequency (quarterly refresh)

---

## 🔬 Advanced Techniques

### Technique 1: Programmatic SEO
**Use Case:** Generate multiple similar pages at scale

**Example:**
- "[City] video editing services" for 100 cities
- "How to use [Tool] for [Use Case]" for 50+ combinations

**Implementation:**
```bash
# Research template
/research [City] video editing services

# Generate batch with Python script
for city in cities:
    content = seo_machine.write(f"{city} video editing services", template)
    publish(content, f"{city}-video-editing")
```

---

### Technique 2: Search Intent Optimization
**Use Case:** Match content to user intent (informational, commercial, navigational, transactional)

**Implementation:**
```bash
/research [keyword]  # Identifies intent
/write [content] --intent=[type]  # Optimizes for intent
```

**Intent Types:**
- **Informational:** "what is", "how to", "guide"
- **Commercial:** "best", "top", "review", "vs"
- **Transactional:** "buy", "price", "discount", "tool"
- **Navigational:** Brand/product names

---

### Technique 3: Content Cluster Strategy
**Use Case:** Build topical authority

**Implementation:**
1. **Pillar Content:** Comprehensive guide (3000+ words)
2. **Cluster Content:** 10-15 related articles linking to pillar
3. **Internal Linking:** Connect all content in cluster

**Example Cluster:**
- **Pillar:** "Complete Guide to AI Video Generation"
- **Cluster:** "Sora 2 vs Runway", "Best Sora 2 Prompts", "Sora 2 Pricing", etc.

---

## 📚 Resources

### SEO Learning
- [Ahrefs Blog](https://ahrefs.com/blog/) - SEO strategies and research
- [Backlinko](https://backlinko.com/) - SEO techniques and case studies
- [Search Engine Journal](https://www.searchenginejournal.com/) - Industry news

### Keyword Research Tools
- [Google Keyword Planner](https://ads.google.com/home/tools/keyword-planner/) - Free keyword data
- [Ahrefs](https://ahrefs.com/) - Comprehensive SEO tool (paid)
- [Ubersuggest](https://neilpatel.com/ubersuggest/) - Free keyword tool

### Content Optimization
- [Hemingway Editor](https://hemingwayapp.com/) - Readability checker
- [Yoast SEO](https://yoast.com/) - WordPress SEO plugin
- [Surfer SEO](https://surferseo.com/) - Content optimization (paid)

---

## 🤝 Contributing

### How to Contribute
1. **Report Issues:** Found a bug or have a suggestion?
2. **Submit Agents:** Create custom agents for specific use cases
3. **Share Workflows:** Document your content production process
4. **Improve Docs:** Help make this guide better

### Custom Agent Template
```markdown
## [Agent Name]
**Purpose:** [What problem does this solve?]

**What It Does:**
- [Feature 1]
- [Feature 2]
- [Feature 3]

**Usage:**
/[command] [parameters]

**Example Output:**
[What users can expect]
```

---

## 🔗 Related Repositories

- [Dead Man Posts Portfolio](https://github.com/DeadManOfficial/Portfolio) - Main portfolio
- [Algorithm-Intelligence](https://github.com/DeadManOfficial/Algorithm-Intelligence) - Content optimization frameworks
- [AI-Media-Tools](https://github.com/DeadManOfficial/AI-Media-Tools) - Complete toolkit

---

## 📄 License

**Original SEOmachine:** MIT License (see original repo)

**Dead Man Posts Customizations:** MIT License

**Attribution:** When using this fork, please credit both:
- Craig Hewitt (@TheCraigHewitt) - Original SEOmachine creator
- Dead Man Posts (@DeadManOfficial) - Customizations and integrations

---

## 🎯 Quick Start Checklist

**Day 1: Setup**
- [ ] Clone repository
- [ ] Open in Claude Code
- [ ] Test basic commands (/research, /write)
- [ ] Review original SEOmachine docs

**Week 1: Learn**
- [ ] Complete 5 research exercises
- [ ] Write 3 articles with /write
- [ ] Optimize 5 existing articles
- [ ] Analyze 3 competitor articles

**Week 2: Integrate**
- [ ] Set up content calendar
- [ ] Define SEO strategy for each pillar
- [ ] Create content templates
- [ ] Build keyword tracking system

**Month 1: Optimize**
- [ ] Track SEO performance
- [ ] Refine workflows based on data
- [ ] A/B test content approaches
- [ ] Scale to consistent production

---

## 💡 Pro Tips

### Tip 1: Batch Your Work
Run multiple `/research` commands at once, then batch write. More efficient than one-at-a-time.

### Tip 2: Create Templates
Save common content structures as templates. Speeds up generation significantly.

### Tip 3: Update Regularly
SEO changes constantly. Refresh high-traffic content quarterly to maintain rankings.

### Tip 4: Don't Over-Optimize
Write for humans first, search engines second. Over-optimization hurts readability.

### Tip 5: Track Everything
Use Google Search Console and Analytics. Data drives decisions.

---

<div align="center">

**SEO Content Machine** | *AI-Powered SEO Automation*

*Research faster. Write better. Rank higher.*

**Original by:** [@TheCraigHewitt](https://github.com/TheCraigHewitt)
**Customized by:** [@DeadManOfficial](https://github.com/DeadManOfficial)

[![GitHub Stars](https://img.shields.io/github/stars/DeadManOfficial/SEO-Content-Machine?style=social)](https://github.com/DeadManOfficial/SEO-Content-Machine)

</div>
