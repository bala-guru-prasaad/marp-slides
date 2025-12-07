---
marp: true
theme: custom
paginate: true
class: lead
style: |
  /* --- Custom Marp theme CSS --- */
  section {
    font-family: "Inter", "Helvetica Neue", Arial, sans-serif;
    color: #222;
  }
  /* Title slide style */
  section.title {
    background: linear-gradient(180deg, #f7fbff, #ffffff);
  }
  h1 {
    color: #0b5fff;
    letter-spacing: -0.5px;
  }
  h2 {
    color: #0d2b4f;
  }
  footer.marp-email {
    position: absolute;
    left: 1.2rem;
    bottom: 1rem;
    font-size: 0.9rem;
    color: #444;
  }
  /* Small code-like box */
  .codeblock {
    border-radius: 8px;
    padding: 12px;
    border: 1px solid #e6eefc;
    background: rgba(240, 246, 255, 0.9);
  }
---

<!-- Title slide -->
# Product Documentation: MyProduct
### Maintainable docs with Marp (Markdown slides)

_footer: 24f3003595@ds.study.iitm.ac.in_ <!-- small footer text -->

---

## What this file contains
- Email included: **24f3003595@ds.study.iitm.ac.in**
- Custom CSS theme (in frontmatter `style:`)
- Page numbers (enabled)
- A slide with a background image (`assets/bg.jpg`)
- Math equations for algorithmic complexity
- Marp directives & small styling examples

---

<!-- backgroundImage: url('assets/bg.jpg') -->
# Visual Slide with Background Image
This slide uses a background image stored at `assets/bg.jpg`.

(You uploaded this file to `assets/bg.jpg` in the repo.)

---

## Example code + custom directive
Use a `codeblock` style for notes:

<div class="codeblock">
**How to use:** open `slides.md` with Marp or VS Code Marp extension to preview.
</div>

---

## Algorithmic complexity (math)
We can write math using LaTeX. Example:

The average-case runtime of Merge Sort:

$$
T(n) = 2T\left(\frac{n}{2}\right) + O(n) \implies T(n) = O(n \log n)
$$

Inline math example: $O(n \log n)$

---

## Small step instructions (child-friendly)
1. Open GitHub → create repo → add `slides.md`.
2. Upload `assets/bg.jpg`.
3. Open `slides.md` on GitHub → Raw → copy raw URL.
4. Paste raw URL in your assignment box.

---

## Contact & credits
Prepared by: **24f3003595@ds.study.iitm.ac.in**

---


---

<!--
_backgroundImage: url('Screenshot 2025-05-26 143930.png')
_backgroundSize: cover
-->

# Background Slide Example

This slide has a background image!
