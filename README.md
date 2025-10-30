# AI Agents: Your New Security Team Members or Biggest Threat?

**BSides Toronto 2025**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![BSides Toronto](https://img.shields.io/badge/BSides-Toronto%202025-blue)](https://bsidesto.ca/)

## About This Talk

This repository contains materials from my BSides Toronto 2025 presentation on AI agents in security operations. The talk explores whether AI can effectively defend against AI-powered attacks, combining research synthesis from IBM, Ponemon, and Hoxhunt studies with hands-on experimentation using open-source tools.

**🎥 Watch the Talk:** https://youtu.be/XGJJBYr7W9g  
**📖 Read the Full Story:** [My First BSides Talk: Lessons from Speaking About AI Security at BSides Toronto](https://michaelifeanyi.com/cloud-security/my-first-bsides-talk-lessons-from-speaking-about-ai-security-at-bsides-toronto/)

---

## Repository Contents
```
bsides-toronto-2025-ai-security/
│
├── presentation/          # Slide deck and speaker notes
├── dashboard/            # Live conceptual dashboard demo
├── research/             # Research sources and citations
└── docs/                 # Talk abstract and documentation
```

---

## Live Dashboard Demo

🔗 **[View Live Dashboard](https://github.com/miifeanyi/bsides-toronto-2025-artifacts/blob/main/dashboard/index.html)**

The dashboard demonstrates:
- **Real-time threat detection** visualization with confidence scoring
- **Email analysis** with AI-powered phishing detection
- **Alert escalation queue**: AI handling 1000+ routine alerts while escalating 12 complex threats to humans
- **Implementation reality**: Shows the "AI augments, doesn't replace" philosophy in action

### Running Dashboard Locally
```bash
# Clone the repository
git clone https://github.com/miifeanyi/bsides-toronto-2025-ai-security.git

# Navigate to dashboard directory
cd bsides-toronto-2025-ai-security/dashboard

# Option 1: Open index.html directly in your browser

# Option 2: Use Python's built-in HTTP server
python -m http.server 8000
# Then visit: http://localhost:8000
```

---

## Key Findings

### AI-Powered Threat Landscape
- **67%** of phishing attacks used AI in 2024 (CybelAngel)
- **55%** more effective than human-created phishing (Hoxhunt)
- **95%** cost reduction for attackers using AI tools

### AI Defense Capabilities
- **97.2%** accuracy in threat detection (Wazuh ML)
- **2-3 months** timeline to operational maturity
- **40-50%** false positives in Month 1, improving to **5-10%** by Month 3

### Implementation Reality
- AI augments human analysts, doesn't replace them
- Data quality is the primary bottleneck
- Requires ongoing tuning and feedback loops
- Best suited for high-volume, routine tasks

**Full citations:** See [`research/sources.md`](research/sources.md)

---

## Talk Structure

1. **The AI Threat Landscape** - Current state of AI-powered attacks
2. **Defense Capabilities** - What AI can (and can't) do in security
3. **Live Dashboard Demo** - Visualizing AI security operations
4. **Implementation Reality** - Honest assessment of deployment challenges
5. **Open Discussion** - Community experiences and Q&A

---

## Tools & Technologies

**Dashboard Built With:**
- HTML5/CSS3/JavaScript
- No external frameworks or dependencies
- Designed for clarity and educational purposes

**Research & Testing:**
- Wazuh (open-source SIEM with ML capabilities)
- Open-source threat intelligence feeds
- Academic research from IBM, Ponemon, Hoxhunt

---

## About the Speaker

**Michael Ifeanyi**  
Technical Solutions Engineer, Google

I support enterprise customers with Kubernetes networking and security. This was my first conference talk, combining two months of research into AI security with hands-on experimentation to answer: Can AI actually defend against AI-powered attacks?

**Connect:**
- 🔗 [LinkedIn](https://www.linkedin.com/in/mifeanyi/)
- 🌐 [Website](www.michaelifeanyi.com)
- 📧 [Email](michael@michaelifeanyi.com)

---

## Research Sources

All statistics and claims are sourced from peer-reviewed research and industry reports:

- IBM Security: Cost of a Data Breach Report 2024
- Hoxhunt: AI Phishing Research 2025
- CybelAngel: External Threat Report 2024
- Ponemon Institute: State of Cybersecurity 2024
- Wazuh: Machine Learning for Threat Detection

**Full citations with methodology:** [`research/sources.md`](research/sources.md)

---

## Files in This Repository

### `/presentation/`
- `slides.pdf` - Full presentation deck
- `speaker-notes.md` - Detailed notes and talking points

### `/dashboard/`
- `index.html` - Main dashboard file
- `css/styles.css` - Dashboard styling
- `js/dashboard.js` - Dashboard functionality
- `assets/screenshots/` - Dashboard preview images

### `/research/`
- `sources.md` - Complete citations and methodology
- `statistics.md` - Key stats with context

### `/docs/`
- `talk-abstract.md` - Original CFP abstract
- `implementation-guide.md` - Getting started with AI security

---

## License

**Code (Dashboard):** MIT License - see [LICENSE](LICENSE)

**Content (Slides, Documentation):** Creative Commons Attribution 4.0 International ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/))

You are free to:
- ✅ Use the dashboard code in your own projects
- ✅ Modify and adapt the materials
- ✅ Share with attribution

---

## Acknowledgments

- **BSides Toronto** organizing team for the opportunity
- **Security community** for thoughtful questions and post-talk discussions
- **Research teams** at IBM, Hoxhunt, CybelAngel, and Ponemon
- **Open-source contributors** to Wazuh and related security tools

---

## Questions or Feedback?

- 🐛 [Report issues](https://github.com/miifeanyi/bsides-toronto-2025-ai-security/issues)
- 💡 Submit pull requests for improvements
- 💬 Connect via [LinkedIn](https://www.linkedin.com/in/mifeanyi/) or [email](michael@michaelifeanyi.com)

---

## For Aspiring Conference Speakers

If this repository is helpful for preparing your first talk:
1. Fork this structure for your own presentation
2. Read my [blog post](link-to-blog) on preparing for your first conference talk
3. Feel free to reach out - happy to share what I learned

---

**⚠️ Important:** This dashboard is a conceptual demonstration for educational purposes. For production AI security implementations, conduct thorough security reviews and consult with security professionals.

**🌟 If this was helpful, please star the repo!**
