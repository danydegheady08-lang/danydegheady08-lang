<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:3d444d&height=210&section=header&text=Dany%20Degheady&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20automation%20for%20B2B%20sales%20and%20finance%20teams&descSize=18&descAlignY=60" alt="Dany Degheady" />

<a href="https://github.com/danydegheady08-lang">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=1200&color=8B949E&center=true&vCenter=true&width=900&lines=Mechatronics+Engineering+%40+SRH+Hochschule+Berlin;I+turn+call+notes+into+follow-ups+and+CRM+updates;I+turn+raw+finance+data+into+board-ready+summaries;Founder+of+Degheady+Consulting;Open+to+AI+automation+and+GTM+engineering+roles+in+Berlin" alt="Typing animation" />
</a>

<br/>

<a href="https://www.linkedin.com/in/dany-degheady-farhat-a00495224"><img src="https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:dany@degheady.com"><img src="https://img.shields.io/badge/Email-000000?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://degheady.com"><img src="https://img.shields.io/badge/degheady.com-000000?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Website" /></a>

</div>

---

## About

Mechatronics Engineering student at SRH Hochschule Berlin, graduating March 2027. I build AI automation for B2B sales and finance teams and run it under Degheady Consulting. Everything below ships and runs.

## What I build

| Project | What it does | Stack |
|---|---|---|
| [**AI Sales Assistant**](https://danydegheady08-lang.github.io/degheady-consulting-demos/sales_assistant_demo.html) | Turns post-call notes into a follow-up email and a CRM summary | Claude API, JavaScript, Cloudflare Workers |
| [**Financial Reporting AI**](https://danydegheady08-lang.github.io/degheady-consulting-demos/finance_reporting_demo.html) | Turns raw financial data into a board-ready executive summary | Claude API, JavaScript, Cloudflare Workers |
| **HubSpot to Claude pipeline** | Watches a HubSpot deal, sends the call notes to Claude, parses the JSON and writes a follow-up email and a deal risk flag back to the deal | Make.com, Claude API, HubSpot |
| [**Outreach Automation**](https://github.com/danydegheady08-lang/ai-sales-assistant) | Reads a prospect CSV, researches each prospect, drafts a personalized email and queues it as a Gmail draft for human approval | Node.js, Gmail API, Claude API |
| [**API Proxy**](https://github.com/danydegheady08-lang/anthropic-proxy) | Cloudflare Worker that routes browser requests to the Anthropic API so no key sits in client-side code | Cloudflare Workers, Wrangler |

## How the outreach pipeline works

```mermaid
flowchart LR
    A[Apollo CSV export] --> B[Node.js pipeline]
    B --> C[Claude with web search<br/>researches each company]
    C --> D[One personal email<br/>per company]
    D --> E[Gmail draft]
    E --> F{Human review}
    F -->|approve| G[Send]
    F -->|reject| C
```

Nothing is sent automatically. Every email lands as a Gmail draft and a person approves it first.

## How I build

- **A human approves anything that leaves the building.** AI drafts, I decide.
- **No secrets in the browser.** API calls go through a Cloudflare Worker.
- **AI output is checked against the source** before it reaches a prospect.
- **One workflow, one measurable result.** I scope small, ship it, then measure it.

## Work with me

I am running three free pilots with small B2B sales and finance teams: one workflow, one week, one measurable result. In return I ask for short feedback and a testimonial if it saves you time. Message me on [LinkedIn](https://www.linkedin.com/in/dany-degheady-farhat-a00495224) to take a spot.

## Stack

<div align="center">

<img src="https://img.shields.io/badge/JavaScript-000000?style=for-the-badge&logo=javascript&logoColor=white&labelColor=000000" alt="JavaScript" />
<img src="https://img.shields.io/badge/Node.js-000000?style=for-the-badge&logo=nodedotjs&logoColor=white&labelColor=000000" alt="Node.js" />
<img src="https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=white&labelColor=000000" alt="Python" />
<img src="https://img.shields.io/badge/HTML5-000000?style=for-the-badge&logo=html5&logoColor=white&labelColor=000000" alt="HTML5" />
<img src="https://img.shields.io/badge/CSS3-000000?style=for-the-badge&logo=css3&logoColor=white&labelColor=000000" alt="CSS3" />
<img src="https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=white&labelColor=000000" alt="Git" />
<br/>
<img src="https://img.shields.io/badge/Claude-000000?style=for-the-badge&logo=anthropic&logoColor=white&labelColor=000000" alt="Claude" />
<img src="https://img.shields.io/badge/Cloudflare-000000?style=for-the-badge&logo=cloudflare&logoColor=white&labelColor=000000" alt="Cloudflare" />
<img src="https://img.shields.io/badge/Make-000000?style=for-the-badge&logo=make&logoColor=white&labelColor=000000" alt="Make" />
<img src="https://img.shields.io/badge/HubSpot-000000?style=for-the-badge&logo=hubspot&logoColor=white&labelColor=000000" alt="HubSpot" />
<img src="https://img.shields.io/badge/Gmail_API-000000?style=for-the-badge&logo=gmail&logoColor=white&labelColor=000000" alt="Gmail_API" />
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white&labelColor=000000" alt="Notion" />
<img src="https://img.shields.io/badge/Apollo.io-000000?style=for-the-badge&labelColor=000000" alt="Apollo.io" />

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3d444d,100:000000&height=110&section=footer" alt="" width="100%" />
