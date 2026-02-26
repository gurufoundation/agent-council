# SKILL INSTALLATION GUIDE
# For: Isiah's Local Agents (agent069xai, Kairo)
# Created by: KimiClaw
# Date: 2026-02-27

## ============================================
## PART 1: SKILLS FOR YOUR LOCAL AGENTS
## ============================================

### 🔥 TIER 1 - INSTALL FIRST (High Impact)

#### 1. Firecrawl MCP (5,000+ stars)
```bash
# Option A: Via OpenClaw
openclaw skill install firecrawl

# Option B: Via NPM
npm install -g @firecrawl/mcp-server

# Option C: Manual
git clone https://github.com/firecrawl/firecrawl-mcp-server.git
cd firecrawl-mcp-server
npm install
```
**Purpose:** Web scraping - turns any website into clean markdown
**API Key needed:** Yes (get from firecrawl.dev - free tier)
**Used by:** agent069xai, Kairo

---

#### 2. Supabase MCP (3,000+ stars)
```bash
# Via OpenClaw
openclaw skill install supabase

# Via NPM
npm install -g @supabase/mcp-server
```
**Purpose:** Database + auth + real-time
**Setup:** Need Supabase project (free at supabase.com)
**Used by:** agent069xai, Kairo

---

#### 3. Sequential Thinking (2,500+ stars)
```bash
# Via OpenClaw
openclaw skill install sequential-thinking

# Via NPM
npm install -g @modelcontextprotocol/sequential-thinking
```
**Purpose:** Advanced reasoning for complex tasks
**API Key:** None needed
**Used by:** agent069xai, Kairo

---

### 🎭 TIER 2 - INSTALL NEXT

#### 4. Puppeteer MCP (2,000+ stars)
```bash
openclaw skill install puppeteer
# OR
npm install -g @modelcontextprotocol/puppeteer
```
**Purpose:** Browser automation (Chrome)
**API Key:** None

---

#### 5. GitHub MCP (5,000+ stars)
```bash
openclaw skill install github
# OR
npm install -g @modelcontextprotocol/github
```
**Purpose:** Repo management, issues, PRs
**API Key:** GitHub Personal Access Token

---

#### 6. Brave Search MCP (1,500+ stars)
```bash
openclaw skill install brave-search
# OR
npm install -g @modelcontextprotocol/brave-search
```
**Purpose:** Private web search
**API Key:** Brave Search API key (free tier)

---

#### 7. Playwright MCP (1,800+ stars)
```bash
openclaw skill install playwright
# OR
npm install -g @executeautomation/playwright-mcp-server
```
**Purpose:** Cross-browser automation
**API Key:** None

---

## ============================================
## PART 2: KIMICLAW'S EXISTING SKILLS
## ============================================

**I already have these installed (cannot add more):**

### Trading/Finance (8 skills)
- coingecko
- yahoo-finance
- stock-market-pro
- portfolio-manager
- crypto-trading-bot
- day-trading-skill
- freqtrade-study
- dsl-dynamic-stop-loss

### Research/AI (7 skills)
- perplexity
- tavily
- exa-web-search-free
- deepwiki
- searxng
- news-aggregator-skill
- reddit-scraper

### Dev/Deploy (6 skills)
- docker
- fastapi
- nextjs
- prisma
- read-github
- vercel

### Communication
- message
- twitter/x-api

**Total: 70+ skills already installed**

---

## ============================================
## PART 3: HOW TO INSTALL FOR YOUR AGENTS
## ============================================

### Method 1: OpenClaw CLI (Easiest)
```bash
# Install all 7 at once
openclaw skill install firecrawl supabase sequential-thinking puppeteer github brave-search playwright
```

### Method 2: Individual Install
```bash
openclaw skill install firecrawl
openclaw skill install supabase
# etc...
```

### Method 3: Manual Git Clone
```bash
cd ~/.openclaw/workspace/skills/

# Firecrawl
git clone https://github.com/firecrawl/firecrawl-mcp-server.git

# Supabase
git clone https://github.com/supabase/supabase-mcp-server.git

# etc...
```

---

## ============================================
## PART 4: API KEYS NEEDED
## ============================================

| Skill | API Key | Get From | Cost |
|-------|---------|----------|------|
| Firecrawl | Yes | firecrawl.dev | Free tier |
| Supabase | Yes | supabase.com | Free tier |
| Sequential Thinking | No | - | Free |
| Puppeteer | No | - | Free |
| GitHub | Yes | github.com/settings/tokens | Free |
| Brave Search | Yes | brave.com/search/api | Free tier |
| Playwright | No | - | Free |

---

## ============================================
## PART 5: VERIFICATION
## ============================================

After installing, verify with:
```bash
openclaw skill list
# Should show new skills

# Or check folder
ls ~/.openclaw/workspace/skills/
```

---

## SUMMARY

**For YOUR agents (install these):**
1. Firecrawl MCP ⭐ 5,000+
2. Supabase MCP ⭐ 3,000+
3. Sequential Thinking ⭐ 2,500+
4. Puppeteer MCP ⭐ 2,000+
5. GitHub MCP ⭐ 5,000+
6. Brave Search MCP ⭐ 1,500+
7. Playwright MCP ⭐ 1,800+

**I already have (cannot add more):**
- 70+ skills including trading, research, dev tools

**Next step:** Install the 7 skills above on your local PC for your agents to use.
