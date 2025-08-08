# Social Hook + CTA Engine (Free)

Generate 10 hooks, 3 CTAs, and 15 hashtags for Instagram, TikTok, LinkedIn, X, and YouTube Shorts. Zero backend; deploy in minutes to Cloudflare Pages.

## Why this works
- Evergreen need for short-form content frameworks
- Distinct value: platform-persona aware outputs
- Monetization path: $9 Pro pack (niche hook banks + CTAs + hashtags)

## One-time setup
1) Deploy to **Cloudflare Pages**
   - New Project → Connect to Git or Upload
   - Framework: None; Build: none; Output dir: `/`
2) Create a **Tally** email capture form
   - Replace the Tally URL inside `index.html`
3) Create a **Gumroad** product for the Pro Pack ($9)
   - ZIP contents idea:
     - 300 niche hooks (JSON/CSV)
     - CTA swipe file
     - Hashtag banks by niche
   - Replace the Gumroad URL in `index.html`

## Local preview
```bash
python3 -m http.server 5511
# open http://localhost:5511/index.html
```

## Marketing launch checklist
- Record a short demo GIF of generating outputs
  - Tool: https://video2gif.vercel.app/
- Post to 3 communities with the live link
  - e.g., r/InstagramMarketing, r/ContentMarketing, relevant FB groups, X #buildinpublic
- Optional embed/badge inspiration: https://github.com/savirsingh/ProfilePop

## License
MIT (or your choice)
