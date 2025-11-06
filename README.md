# 🌴 Devon Loves Jamaica

### Support and Aid Following Hurricane Melissa

**A community-led fundraising and information website connecting Devon and Jamaica through culture, music, and solidarity.**

---

## 🎯 Purpose

**Devon Loves Jamaica** is a transparent, grassroots digital campaign raising awareness and funds for communities in Jamaica affected by **Hurricane Melissa**.

We aim to:

* Provide **verified, clear information** about the hurricane’s impact and relief needs.
* Create a **trusted digital space** for fundraisers, sponsors, venues, and local organisations.
* Encourage **community participation** through music, food, and cultural events in Devon.
* Maintain **transparency** in how funds are collected and distributed.

---

## 🌍 Project Goals (MVP)

1. **Inform** — concise summary of Hurricane Melissa’s impact and relief needs.
2. **Fundraise** — embed links to reputable fundraising platforms (see list below).
3. **Engage** — allow users to register interest as sponsors, venues, or volunteers via simple forms.
4. **Unite** — show solidarity between Devon and Jamaica through shared culture, events, and stories.
5. **Comply** — avoid unnecessary personal data collection; use existing tools for fundraising and mailing.

---

## 🧩 Free Fundraiser & Mailing Platforms (no data collection burden)

To simplify and avoid handling donations or personal data directly, this project will **link to or embed** existing free/low-fee fundraising platforms:

| Purpose                    | Recommended Tools                                                                                             | Notes                                              |
| -------------------------- | ------------------------------------------------------------------------------------------------------------- | -------------------------------------------------- |
| **Donations**              | [JustGiving](https://www.justgiving.com/), [GoFundMe](https://www.gofundme.com/), [Ko-fi](https://ko-fi.com/) | Easy setup, public transparency pages.             |
| **Event Ticketing**        | [Eventbrite](https://www.eventbrite.co.uk/)                                                                   | Free for free events; handles ticketing, QR codes. |
| **Volunteer/Sponsor Form** | [Google Forms](https://forms.google.com/) or [Formspree.io](https://formspree.io/)                            | No backend; submissions to email or Sheets.        |
| **Email Sign-ups (MVP)**   | [Mailchimp Free Tier](https://mailchimp.com/)                                                                 | GDPR-compliant; replaceable later.                 |
| **QR & Link Management**   | [Linktree Free](https://linktr.ee/)                                                                           | Collects all links in one page.                    |

Later, if needed, integrate via embedded widgets instead of storing data manually.

---

## 👥 User Personas (10)

1. **Devon-based Jamaican descendant** — wants to support authentic causes.
2. **Music lover in Devon** — wants event info and cultural connection.
3. **Venue manager** — needs safe event info, hosting guidance.
4. **Local charity coordinator** — checks transparency and collaboration opportunities.
5. **Corporate sponsor** — looks for branding & sponsorship options.
6. **Local press/blogger** — needs assets, press release, contact.
7. **Volunteer** — wants simple sign-up and tasks overview.
8. **One-off donor** — wants fast and trusted donation route.
9. **Long-term supporter** — expects updates and proof of impact.
10. **Jamaica-based NGO** — needs verified communication and fund routing.

---

## 🧠 User Stories (examples)

* As a *Jamaican-descendent in Devon*, I want to see where donations go so that I can trust the fundraiser.
* As a *music fan*, I want to know event dates so I can attend and share.
* As a *venue manager*, I want safety and sponsorship info so I can host confidently.
* As a *donor*, I want a quick, mobile-friendly donation flow so I can contribute easily.
* As a *press contact*, I want a media pack and contact so I can cover the story accurately.

*(See `/docs/user-stories.md` if expanded later.)*

---

## ⚙️ MoSCoW Prioritisation

**Must Have**

* Clear call-to-action buttons (Donate / Get Involved).
* Transparent “Where Funds Go” section.
* Links to verified donation platforms (no direct collection).
* Event info and press contact.
* Accessibility compliance (WCAG AA).

**Should Have**

* Responsive one-page Bootstrap layout.
* Wall of Solidarity (logos/names of supporters).
* Embedded sign-up forms (volunteer/sponsor).
* Social links and Linktree integration.

**Could Have**

* QR codes for printed materials.
* Spotify playlist or stories section.
* Recipe e-book or local art fundraiser.

**Won’t Have**

* Complex backend or database.
* Paid subscription services (MVP to remain free).

---

## 🎨 Design & Branding

**Tone:** Warm, hopeful, professional.
**Style:** Jamaican vibrancy + Devon heritage — clean, ethical, inclusive.

**Colour Palette (Bootstrap variables):**

```css
--bs-primary: #009B3A;   /* Jamaica green */
--bs-secondary: #00824A; /* Devon green */
--bs-accent: #FED100;    /* Gold */
--bs-dark: #000000;      /* Text / contrast */
--bs-light: #FFFFFF;     /* Backgrounds */
```

**Typography:**

* Headings — *Poppins / Montserrat*
* Body — *Inter / system sans-serif*

**Imagery:**

* Heart-shaped icon merging the Jamaica and Devon flags (AI-generated).
* Community event photos, flags, and textures (free stock or provided by partners).

---

## 💡 Suggested AI Image Generator

For the **heart-shaped combined-flag icon**, try:

* [**DALL·E 3 (Bing Image Creator)**](https://www.bing.com/create) – free, clean vector-style icons.
* [**Adobe Firefly**](https://firefly.adobe.com/) – ideal for logo/flat graphics with brand colours.
* [**Leonardo.Ai**](https://leonardo.ai/) – for more polished stylistic options.

**Prompt example:**

> “Flat vector icon of a heart combining the Jamaican and Devon flags in equal halves. Bold colours #009B3A, #00824A, #FED100, #000000, #FFFFFF. Minimalist, respectful, transparent background.”

---

## 🧱 Technical Setup

**Stack:** HTML5 • Bootstrap 5 • CSS • minimal JS
**Host:** GitHub Pages (free)

### 🪜 Setup Instructions

1. **Fork or clone this repo**

   ```bash
   git clone https://github.com/[your-username]/devon-loves-jamaica.git
   cd devon-loves-jamaica
   ```

2. **Create a new branch for local edits**

   ```bash
   git checkout -b dev
   ```

3. **Open locally in VS Code**

   ```bash
   code .
   ```

4. **Run on localhost**

   * Install the *Live Server* extension.
   * Right-click `index.html` → **Open with Live Server**.

5. **Commit and push changes**

   ```bash
   git add .
   git commit -m "Add homepage skeleton"
   git push origin dev
   ```

6. **Deploy to GitHub Pages**

   * Go to **Settings → Pages**
   * Under *Source*, select **Deploy from branch → main → /root**
   * Visit your live site at `https://your-username.github.io/devon-loves-jamaica`

---

## 🔍 Accessibility & Transparency

* Use semantic HTML (`<main>`, `<section>`, `<nav>`, `<footer>`).
* Ensure 4.5:1 text contrast, alt text, focus outlines, skip links.
* No cookies or tracking scripts beyond embedded third-party tools.
* Clearly display fund destination and charity partner names.

---

## 📅 Timeline (2–3 Weeks)

| Week | Focus             | Deliverables                                   |
| ---- | ----------------- | ---------------------------------------------- |
| 1    | Discovery & setup | Research, branding, README, GitHub Pages setup |
| 2    | Build MVP         | HTML structure, donate links, event info       |
| 3    | Testing & launch  | Accessibility check, go-live, social promo     |

---

## 📣 Community & Collaboration

Want to get involved?

* Email: **[contact@devonlovesjamaica.org](mailto:contact@devonlovesjamaica.org)** *(placeholder)*
* Submit PRs or design suggestions via GitHub Issues.
* Follow social links once live for event updates.

---

## 🧾 Licence

This project is open source under the [MIT Licence](LICENSE).

---

> **Devon Loves Jamaica** — Standing together in hope, culture, and community.
> *“Out of many, one people.”*
