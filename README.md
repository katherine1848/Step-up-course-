# Sales Foundations — On‑Demand Course Site

Deployed initially at: https://yourproject.onrender.com

---

## Files
- `index.html` — Home page with pricing & contact form
- `thankyou.html` — Post‑checkout access page (add your course links)
- `styles.css` — Basic responsive styles
- `README.md` — Instructions

---

## 1) Deploy on GitHub + Render
1. Create a GitHub repo and **upload all files** in this folder (root level).
2. In Render → **New → Static Site** → connect the repo.
   - **Build Command:** *(leave blank)*
   - **Publish Directory:** `/`
   - Enable **Auto‑Deploy**

---

## 2) Stripe setup
Payment buttons are already linked.

**After Checkout redirect:**
- In Stripe Dashboard → Your Product → **Payment Link → After checkout** →
  **Redirect to:** https://yourproject.onrender.com/thankyou.html

---

## 3) Formspree (contact form)
Already set to post to `https://formspree.io/f/xyzdopzq`.

It also redirects back to:
https://yourproject.onrender.com/thankyou.html

---

## 4) Add course links
Open `thankyou.html` and replace placeholders:
- `YOUR_VIDEO_LINKS_HERE`
- `YOUR_WORKBOOKS_LINKS_HERE`
- `YOUR_KPI_TRACKER_LINK_HERE`
- `YOUR_BONUS_LINKS_HERE`

---

## 5) Test checklist
- Home page loads at https://yourproject.onrender.com
- Each **Enroll** button opens Stripe checkout
- Successful payment redirects to `/thankyou.html`
- Contact form submits and emails you
- All links on thank you page work

---

## 6) Update later
Edit files → commit to GitHub → Render auto‑deploys.
