# Aviation Operations Grade Calculator

A single-file, mobile-friendly calculator for the **Pearson BTEC Level 3 Extended Diploma in Aviation Operations (QCF)** (600/6439/0).

## Publish on GitHub Pages

1. Create a **public** GitHub repository (for example, `aviation-grade-calculator`).
2. Upload `index.html` to the **root** of the `main` branch. The optional `.nojekyll` file can go there too.
3. In the repository, go to **Settings → Pages**.
4. Choose **Deploy from a branch**, then `main` and `/(root)`. Save.
5. When Pages shows your site URL, share it with your classmates. Typical URL: `https://YOUR-USERNAME.github.io/aviation-grade-calculator/`.

**No build step, packages, domain or payment required.** The whole site works from `index.html` and has no third-party scripts or tracking. Each visitor's grade selections are stored only in their own browser's local storage (if available).

## How it calculates

- Four mandatory units: Units 1–4 (27 credits total).
- 153 optional credits, making 180 credits overall.
- At least 161 credits must be Level 3 or above. The listed optional Level 2 units together total 9 credits, so this criterion holds for every valid combination in this calculator.
- Level 2: P=5, M=6, D=7 points/credit; Level 3: P=7, M=8, D=9 points/credit.
- If more than 180 credits are selected, the **highest-scoring exact-credit eligible 180-credit combination** is used; this is a planning estimate rather than a Pearson certification decision.
- The thresholds are Pearson's Extended Diploma (QCF) thresholds, and UCAS points are from the published Extended Diploma tariff table.
- Blank units are excluded. If fewer than 180 credits are graded or the exact credit combination cannot be formed, no final grade is shown. Students can enter predicted grades for future units.

**Sources:**

- [Pearson Aviation Operations (QCF) specification, Issue 3](https://qualifications.pearson.com/content/dam/pdf/BTEC-Nationals/Aviation-Operations/2010/Specification/9781446935262-btec-90c-l3-aviationops-iss2.pdf) — Extended Diploma units pp. 15–16, grading pp. 18–19.
- [UCAS Tariff calculator](https://www.ucas.com/applying/before-you-apply/what-and-where-to-study/entry-requirements/calculate-your-ucas-tariff-points)
- [Pearson UCAS points reference](https://qualifications.pearson.com/en/support/support-topics/understanding-our-qualifications/comparing-btec-to-other-qualifications/btec-ucas-points.html)

This is an independent calculator, not endorsed by Pearson or UCAS. Confirm unusual unit combinations or grades with your college.
