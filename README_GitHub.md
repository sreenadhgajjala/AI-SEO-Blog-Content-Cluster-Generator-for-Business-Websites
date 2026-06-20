# SEO Content Pack — Digital Marketing Agency, Hyderabad
### Prompt Engineering Task 3 · Future Interns · 2026

---

## 📌 Overview

A **complete SEO content cluster** built using structured prompt engineering — ready to publish on a real business website or hand to a digital marketing client.

**Business Type:** Digital Marketing Agency  
**Location:** Hyderabad, India (Local SEO focus)  
**Created with:** Claude (Anthropic), Google Search Autocomplete, AnswerThePublic, Google Trends

---

## 📁 Repository Structure

```
seo-content-pack-digital-agency-hyderabad/
│
├── README.md
│
├── prompts/
│   ├── 01_strategy_prompt.md         # Content cluster strategy generator
│   ├── 02_pillar_blog_prompt.md      # Long-form pillar blog generator
│   ├── 03_cluster_blog_prompt.md     # Supporting blog generator
│   ├── 04_local_seo_prompt.md        # Local SEO adaptation prompt
│   └── 05_meta_tags_prompt.md        # Meta title & description generator
│
├── content/
│   ├── pillar_blog.md                # "Best Digital Marketing Agency in Hyderabad" (~2,200w)
│   ├── cluster_01_what_is_seo.md     # "What is SEO and Why Do Hyderabad Businesses Need It?"
│   ├── cluster_02_ads_vs_seo.md      # "Google Ads vs SEO – Which is Right for You?"
│   ├── cluster_03_pricing_guide.md   # "How Much Does Digital Marketing Cost in Hyderabad?"
│   ├── cluster_04_social_media.md    # "Social Media Marketing for Small Businesses in Hyderabad"
│   └── cluster_05_how_to_choose.md   # "How to Choose the Right Digital Marketing Agency"
│
├── keywords/
│   └── keyword_map.csv               # Full keyword list with volume, difficulty, intent
│
└── docs/
    └── SEO_Content_Pack.docx         # Complete formatted deliverable document
```

---

## 🔑 Keyword Map

| Keyword | Est. Volume | Difficulty | Intent |
|---|---|---|---|
| digital marketing agency Hyderabad | 2,400/mo | Medium | Commercial / Local |
| SEO services in Hyderabad | 1,900/mo | Medium | Commercial |
| best digital marketing company Hyderabad | 1,300/mo | Medium | Transactional |
| social media marketing Hyderabad | 880/mo | Low | Commercial |
| Google Ads agency Hyderabad | 720/mo | Low-Med | Transactional |
| content marketing services Hyderabad | 480/mo | Low | Commercial |
| how to grow business online Hyderabad | 390/mo | Low | Informational |
| digital marketing for small business India | 1,100/mo | Medium | Informational |

---

## 🗂️ Content Cluster Architecture

```
PILLAR BLOG
└── Best Digital Marketing Agency in Hyderabad – Services, Results & How to Choose
    │
    ├── CLUSTER 1: What is SEO and Why Do Hyderabad Businesses Need It? (Informational)
    ├── CLUSTER 2: Google Ads vs SEO – Which is Right for Your Business? (Commercial)
    ├── CLUSTER 3: How Much Does Digital Marketing Cost in Hyderabad? (Commercial)
    ├── CLUSTER 4: Social Media Marketing for Small Businesses in Hyderabad (Informational)
    └── CLUSTER 5: How to Choose the Right Digital Marketing Agency in Hyderabad (Transactional)
```

**Internal Linking Rule:** Every cluster blog links back to the Pillar Blog and to at least one other cluster blog. The Pillar Blog links to all 5 cluster blogs.

---

## 🧠 The Prompt System

### PROMPT 1 — SEO Content Strategy Generator
```
You are an expert SEO strategist. Design a content cluster strategy for a [BUSINESS TYPE] in [CITY], India.

Business: [BUSINESS NAME] — a [SIZE] [BUSINESS TYPE] serving [TARGET CUSTOMERS].
Primary service keywords: [LIST 3–5 SERVICES].

Generate:
1. 8–10 primary and secondary keywords with search volume and intent
2. Content cluster map: 1 pillar + 5 supporting blogs
3. For each blog: H1 title, primary keyword, intent, target word count
4. Internal linking structure
```

### PROMPT 2 — Pillar Blog Generator
```
You are a professional SEO content writer. Write a long-form pillar blog for a [BUSINESS TYPE] in [CITY].

H1 Title: [TITLE]
Primary Keyword: [KEYWORD]
Secondary Keywords: [LIST]
Target Word Count: 2,000–2,500 words

Requirements:
- H1, H2, H3 heading structure
- Primary keyword in first 100 words
- Internal link suggestions to 5 supporting blogs
- Include a comparison table or checklist
- Local [CITY] references throughout
- End with a strong CTA
- Tone: helpful and direct, not salesy
```

### PROMPT 3 — Supporting Blog Generator
```
Write a cluster blog for a [BUSINESS TYPE] in [CITY].

H1 Title: [TITLE]
Primary Keyword: [KEYWORD]
Search Intent: [informational / commercial / transactional]
Target: [900–1,200 words]

Requirements:
- Keyword in H1 and first 100 words
- Internal link to pillar blog + 1 cluster blog
- Answer the core question in first 2 paragraphs
- Include a list, comparison, or callout box
- End with CTA to contact [BUSINESS NAME]
```

### PROMPT 4 — Local SEO Adaptation
```
Adapt this blog for local SEO targeting [CITY], [AREA].

[PASTE BLOG]

Instructions:
- Include [CITY] and [AREA] in H1, 2+ H2s, and meta description
- Add local context paragraph specific to [CITY]
- Include 2–3 local references
- Add 'near me' keyword variants naturally
- Keep word count within 5% of original
```

### PROMPT 5 — Meta Tags Generator
```
Generate SEO meta tags for this blog:

Title: [TITLE]
Primary Keyword: [KEYWORD]
City: [CITY]

Output:
1. Meta Title (max 60 characters)
2. Meta Description (max 155 characters)
3. 5 alternative meta titles for A/B testing
4. URL slug suggestion
```

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Claude (claude.ai) | Content generation, strategy, outlining |
| Google Search Autocomplete | Keyword discovery, PAA questions |
| AnswerThePublic | Long-tail and question-based keywords |
| Google Trends | Validating keyword interest over time |

---

## ✅ Deliverable Checklist

- [x] Business chosen (specific, real-world)
- [x] 1 Pillar Blog — full long-form (~2,200 words)
- [x] 5 Cluster Blogs — unique keyword and search intent each
- [x] Keyword + intent map (8+ keywords)
- [x] 5 reusable prompt templates
- [x] GitHub repository structure documented
- [x] Local SEO: Hyderabad mentioned naturally across all content
- [x] Internal linking strategy defined
- [x] Content formatted as if live on a business website
- [x] Full SEO Content Pack document ready to share with a client

---

## 🔁 How to Reuse This for Any Client

1. Replace `[BUSINESS TYPE]` → e.g., dental clinic, coaching institute, salon
2. Replace `[CITY]` → e.g., Bangalore, Chennai, Pune
3. Replace `[KEYWORD]` → run Prompt 1 to generate keywords first
4. Run Prompt 2 for the pillar blog
5. Run Prompt 3 (×5) for each cluster blog
6. Run Prompt 4 to localise all content
7. Run Prompt 5 to generate meta tags for each piece

This system can generate a full SEO content pack for a new client in under 2 hours.

---

*Prompt Engineering Task 3 · Future Interns · 2026*
