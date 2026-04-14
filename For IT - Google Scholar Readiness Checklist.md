# ✅ 📋 Google Scholar Readiness Checklist (for OJS)**

Use this like a quick audit for your journal powered by Open Journal Systems.

## 🔓 1. Access & Visibility

- ✅ Articles are **publicly accessible**
- ❌ No login required to view full text
- ❌ No paywall blocking PDFs

👉 If a crawler can't access it, it doesn't exist.

## 🌐 2. Article Landing Pages (VERY important)

Each article must have:

- ✅ A **dedicated URL**
- ✅ HTML page (not just PDF)

Example:

/article/view/123

👉 Google Scholar indexes the **page**, not just the file.

## 🧾 3. Complete Metadata (this is critical)

Every article page must include:

- ✅ Title
- ✅ Full author names
- ✅ Abstract
- ✅ Keywords
- ✅ Publication date
- ✅ Journal name

👉 OJS usually outputs tags like:

&lt;meta name="citation_title" ...&gt;  
&lt;meta name="citation_author" ...&gt;

If these exist → you're in a good place.

## 📄 4. PDF Accessibility

- ✅ Direct link to PDF
- ✅ No JavaScript blockers
- ✅ File loads without login

👉 Scholar parses PDFs for references and citations.

## 📚 5. References Section

- ✅ Articles include a **reference list**
- ✅ Proper formatting

👉 This enables:

- Citation linking
- Citation counting

## 🤖 6. Allow Crawlers

Check your server:

- ✅ robots.txt does NOT block:

/index.php  
/article

- ✅ No firewall rules blocking bots

## ⚙️ 7. Clean URLs & Stability

- ✅ URLs don't change
- ❌ No broken links
- ❌ No duplicate pages

## 🧪 8. Basic Test

Try this:

- Open article in **incognito mode**
- Disable login/session
- If it loads → good

## ⏳ 9. Patience (important)

After publishing:

- Indexing may take **days to weeks**
- No manual "submit" button for Scholar