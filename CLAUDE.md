This repo is keneticon.com, the Kenetic Consulting website. It is not kcorriveau.com, Vista or Evolvium. If a request mentions those, stop and confirm with Ken before touching anything.

## Rules

- Purpose: advisory practice site. Audience is CEOs, boards, PE sponsors and holding companies. It sells four project offers: AI strategy and readiness; AI governance, security and risk; technology due diligence; board and executive advisory. Fractional and interim CIO roles are not sold here. Those go to Fortium Partners.
- Structure: all website files live in /docs, the GitHub Pages publishing folder. CLAUDE.md and README.md stay outside /docs.
- Tech: plain HTML and CSS with minimal vanilla JavaScript. No framework, no build step, no npm. Keep an empty .nojekyll in /docs.
- Links and asset paths must be relative, because the preview runs at https://kenadman.github.io/keneticon.com/ until the domain cutover.
- Do not create a CNAME file or set a custom domain. Ken will call the cutover.
- The repo is public. Never commit drafts, notes, contact lists, credentials or anything private.
- Content comes only from Ken. Never invent clients, testimonials, metrics, team members or credentials.
- Contact: booking link https://app.reclaim.ai/m/kencorriveau/flexible-quick-meeting, email ken@keneticon.com, LinkedIn https://www.linkedin.com/in/kennethcorriveau/. No phone number and no contact form.
- Fortium profile URL pending. Every Fortium link points to https://fortiumpartners.com and carries data-placeholder="fortium-profile".
- Writing rules: no em dashes, no en dashes, no exclamation points, no emoji, never the word "excited". No HTML comments.

## Design tokens

Same family as kcorriveau.com and evolvium.ai. Type scale, spacing and component shapes follow ~/sites/kcorriveau.com/docs/css/site.css (reference only, never edit it).

- Fonts: Outfit for headings, DM Sans for body, from Google Fonts.
- Navy #162842: headings, the nav, dark bands.
- Ink #1F3553: body text.
- Muted #4A5670.
- Page background #F7F9FC. Cards #FFFFFF. Soft panels #EDF3FA. Borders #DCE5F0.
- Accent, vivid orange #F97316: buttons and fills, always with navy #162842 text on it (5.3:1). Also accent text on navy backgrounds.
- Deep orange #C2410C: links and accent text on light backgrounds (4.9:1).
- Never use copper #A9521C (kcorriveau.com) or magenta (Evolvium).
- Wordmark: "Kenetic" in Outfit semibold navy, "CONSULTING" in small spaced capitals beneath, orange forward chevron to the left. The chevron alone is the favicon (docs/images/favicon.svg).
- Feel: confident, calm, generous white space, one idea per section. Mobile first. Subtle motion only, and respect prefers-reduced-motion.
