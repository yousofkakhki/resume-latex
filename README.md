# 💼 Yousef Kakhki - LaTeX Resume

Automated LaTeX resume with GitHub Actions compilation and MCP-powered AI editing.

## 🎯 Features

- **Automated PDF Compilation**: GitHub Actions automatically compiles LaTeX to PDF on every commit
- **AI-Powered Editing**: Use Cursor + Perplexity MCP or GitHub MCP for intelligent resume optimization
- **Version Control**: Every resume update is tracked with Git and released automatically
- **Telegram Integration**: Get compiled PDFs delivered directly to Telegram
- **ATS-Optimized**: Structured for Applicant Tracking System compatibility

## 🚀 Quick Start

### 1. Setup GitHub Secrets (Optional - for Telegram notifications)

Go to **Settings → Secrets and variables → Actions** and add:

- `TELEGRAM_BOT_TOKEN`: Your Telegram bot token
- `TELEGRAM_CHAT_ID`: Your Telegram chat ID

### 2. Edit Resume

#### Option A: Direct Edit (Manual)

```bash
git clone https://github.com/yousofkakhki/resume-latex.git
cd resume-latex
# Edit resume.tex
git add resume.tex
git commit -m "✅ Update experience section"
git push
```

**Result**: GitHub Actions automatically compiles PDF and creates a release!

#### Option B: AI-Powered Edit (Using Cursor + GitHub MCP)

In Cursor Composer:

```
Using GitHub MCP:
1. Read resume from github.com/yousofkakhki/resume-latex/resume.tex
2. Optimize the Capitalino section with more quantified metrics
3. Commit changes with message "AI optimization: quantified impact"
```

Cursor will automatically read, optimize, and commit!

#### Option C: Perplexity Research + Edit

```
Using GitHub MCP and Perplexity:
1. Research latest backend engineering keywords trending in job postings
2. Read my resume from github.com/yousofkakhki/resume-latex/resume.tex
3. Update skills section to include relevant new keywords
4. Commit changes
```

### 3. Download Compiled PDF

**Latest Version**: https://github.com/yousofkakhki/resume-latex/releases/latest

Or check Telegram if you configured the bot!

## 📄 Resume Structure

### Current Optimization (v2.0)

✅ **Positioning**: System Design Specialist with Leadership Experience  
✅ **STAR Format**: Key achievements formatted with Situation-Task-Action-Result  
✅ **Quantified Impact**: All major accomplishments include metrics  
✅ **EU Blue Card Ready**: Clearly states eligibility and openness to relocation  
✅ **ATS Keywords**: Optimized for backend, DevOps, FinTech, system design roles  

### Sections

1. **Profile**: Hook with system design expertise, quantified achievements, and career goals
2. **Education**: Master's in System Design from Amirkabir University (top-tier)
3. **Experience**:
   - **Capitalino** (Technical Lead): Team leadership, Agile, microservices, DevOps
   - **Batna** (Systems Engineer): Embedded Linux, OTA systems, kernel optimization
   - **Avin Avisa** (Backend Developer): P2P crypto exchange, matching engine, blockchain
4. **Skills**: Organized by priority (Core Expertise → Leadership → FinTech → Infrastructure)
5. **Certifications**: TensorFlow + CEO recommendation letter
6. **Languages**: English (IELTS 7.5), French (B2), Persian (Native)

## 🤖 AI Optimization Guide

### Using Cursor Composer

**Task**: Add new skill
```
Using GitHub MCP:
- Add "Kubernetes" to the Infrastructure & DevOps section
- Commit with message "Add Kubernetes skill"
```

**Task**: Optimize for specific job
```
Using Perplexity + GitHub MCP:
1. Research the company [Company Name] and job posting [URL]
2. Read my resume from GitHub
3. Tailor the Profile section to match their tech stack
4. Commit changes
```

**Task**: Weekly keyword refresh
```
Using Perplexity:
1. Research trending backend/DevOps keywords in job postings this week
2. Compare with my current resume keywords
3. Suggest additions (don't auto-commit, let me review)
```

## 📊 Metrics & Impact

**Current Resume Stats** (as of Jan 2026):
- **Quantified Achievements**: 15+ metrics (revenue, uptime, performance improvements)
- **STAR Format Examples**: 3 major projects
- **Keywords**: 50+ ATS-optimized technical terms
- **Target Markets**: EU Remote, Visa Sponsorship, Senior/Lead roles

## 🔧 Technical Details

**LaTeX Class**: `moderncv` (classic style, blue color scheme)  
**PDF Compilation**: GitHub Actions using `xu-cheng/latex-action`  
**Version Control**: Semantic releases with date-based tags  
**Automation**: GitHub Actions + MCP integration  

## 📝 Resume Configuration

See `resume-config.json` for:
- Target roles and markets
- Positioning strategy
- Key technologies to emphasize
- Optimization goals and rules

## 🎓 About Me

**Yousef Kakhki**  
System Design Specialist & Technical Lead  
📧 me@kakhki.ir  
🌐 [kakhki.ir](https://kakhki.ir)  
🐔 [LinkedIn](https://linkedin.com/in/yousefkakhki)  

**Open to**:
- 🇩🇪 Remote roles in EU (Germany, Netherlands, France)
- ✈️ Relocation with visa sponsorship (EU Blue Card eligible)
- 🇮🇷 Senior/Lead positions in Iran

## 📜 License

This resume structure and automation is open-source. Feel free to fork and adapt!

---

**Last Updated**: January 22, 2026  
**Optimized By**: Perplexity AI + Human Review  
**Version**: 2.0 (System Design Focus)
