# RH KPO Services — Naya Blog Kaise Add Karo
## (Bilkul Simple — Copy Paste Karo!)

---

## STEP 1 — GitHub pe jao
👉 github.com/rhkposervices-droid/rhkpo-website

## STEP 2 — index.html open karo
`index.html` file pe click karo → phir **pencil icon ✏️** (Edit) click karo

## STEP 3 — 2 jagah copy-paste karo

---

### JAGAH 1 — Blog List mein Card add karo
(Line ~923 pe dhundo: `<div class="blog-grid-outer">`)

Sabse pehle wale blog card SE PEHLE yeh paste karo:

```html
<!-- ═══ BLOG 6 — NAYA BLOG ═══ -->
<div class="bcard aos" onclick="showBlog('blog6')">
  <div class="bcard-thumb bt1"><span class="bcard-thumb-icon">📋</span></div>
  <div class="bcard-body">
    <span class="btag">Tax Tips</span>
    <h3>YAHAN APNA BLOG TITLE LIKHO</h3>
    <p class="bexcerpt">Yahan 1-2 line ka short summary likho jo blog ke baare mein bataye.</p>
    <div class="bcard-meta"><span class="bdate">21 March 2026</span><span class="bread">Read More →</span></div>
  </div>
</div>
```

**Emoji options (bcard-thumb color):**
- `bt1` = Orange | `bt2` = Green | `bt3` = Blue | `bt4` = Purple | `bt5` = Yellow

**Emoji options:**
- 📋 📊 📅 🗓️ 📝 ⚠️ 💡 🏢 💼 📈 🧾

---

### JAGAH 2 — Blog Post Content add karo
(Line ~1165 ke baad, `<!-- end blog page -->` SE PEHLE paste karo)

```html
<!-- ═══ BLOG 6 POST ═══ -->
<div id="page-blog6" class="page">
<div style="background:var(--off-white);min-height:80vh;padding-top:20px;">
<div class="blog-post">
  <div class="bp-back" onclick="showPage('blog')">← Back to Blog</div>
  <span class="bp-tag">Tax Tips</span>
  <h1 class="bp-title">YAHAN APNA BLOG TITLE LIKHO</h1>
  <div class="bp-meta">Published 21 March 2026 &nbsp;·&nbsp; By RH KPO Services</div>
  <div class="bp-content">

    <p>Yahan apna pehla paragraph likho — introduction.</p>

    <h2>Section 1 Heading</h2>
    <p>Yahan section 1 ka content likho.</p>

    <h2>Section 2 Heading</h2>
    <p>Yahan section 2 ka content likho.</p>

    <div class="highlight-box">
      <p><strong>Important Note:</strong> Koi important point yahan likho highlighted box mein.</p>
    </div>

    <h2>Section 3 Heading</h2>
    <ul>
      <li>Point 1</li>
      <li>Point 2</li>
      <li>Point 3</li>
    </ul>

    <div class="bp-cta">
      <h3>Need Help?</h3>
      <p>RH KPO Services helps UK accounting firms stay compliant and grow.</p>
      <a href="#" onclick="showPage('contact')" class="btn-orange">Contact Us Today →</a>
    </div>

  </div>
</div>
</div>
</div>
```

---

## STEP 4 — Commit karo
Neeche **"Commit changes"** click karo → **"Commit directly to main"** → **"Commit changes"** ✅

## STEP 5 — Done! 🎉
2-3 minute mein site automatically update ho jaayegi!

---

## IMPORTANT RULES:

| Rule | Detail |
|------|--------|
| Blog number | Har naye blog mein `blog6`, `blog7`, `blog8`... badhate jao |
| `showBlog('blog6')` | Card mein aur page ID dono match hone chahiye |
| `id="page-blog6"` | Har blog ka alag number hona chahiye |

---

## Naya Blog — Claude se likhwao (New Chat mein):

```
Mujhe RH KPO Services website ke liye ek naya blog post
banana hai. Topic: [APNA TOPIC YAHAN]. 
UK accounting firm audience ke liye.
Format: HTML, existing blog jaisa.
Blog number: blog6
```

Claude sirf woh 2 HTML snippets dega — 
aap bas copy-paste karke GitHub pe commit karo! ✅
