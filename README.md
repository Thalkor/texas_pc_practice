# Texas P&C License Exam Practice App

A fully self-contained, offline-capable HTML practice app for the **Texas General Lines – Property & Casualty Insurance** licensing examination (administered by Pearson VUE).

## Exam Overview

| Item | Details |
|------|---------|
| Total questions | 150 (120 scored + 30 unscored pretest) |
| Passing score | 70% (84 out of 120 scored questions) |
| Time limit | 2 hours, 30 minutes |
| Administrator | Pearson VUE |

## Question Bank

This app includes **231 questions** covering all 4 official content areas:

| Category | Weight | Questions |
|----------|--------|-----------|
| General Insurance Concepts | ~20% | 40 |
| Property Insurance | ~30% | 62 |
| Casualty/Liability Insurance | ~25% | 55 |
| Texas Laws & Regulations | ~25% | 74 |

Topics covered include: insurable interest, indemnity, subrogation, homeowners policies (HO-1 through HO-8), commercial property, NFIP flood, TWIA, personal auto (PAP), CGL, workers compensation, professional liability, Texas Insurance Code, TDI licensing, unfair trade practices, cancellation/nonrenewal rules, surplus lines, and much more.

## How to Use the App

### Opening Locally

1. Download or locate `index.html`
2. Double-click the file to open it in your web browser (Chrome, Firefox, Edge, or Safari)
3. No internet connection required — everything runs in your browser

### Quiz Modes

| Mode | Questions | Timer | Best For |
|------|-----------|-------|----------|
| ⚡ Quick Quiz | 4 | None | Fast daily warm-up |
| 📝 Practice Quiz | 30 | None | Topic review |
| 🎯 Full Practice Test | 120 | 2.5 hours | Exam simulation |
| 🔄 Missed Questions | Variable | None | Targeted review |

**Tailored Mode** — Available for all modes. Pulls proportionally more questions from categories where you've scored lower.

**Lock Answers (No Going Back)** — Available for Full Practice Test. Disables the Previous button for a more realistic exam experience.

### Study Mode

- Browse all 231 questions with answers shown
- Filter by category using the chips at the top
- Search for specific topics using the search bar
- Click any question card to expand and see the correct answer + explanation

### Progress Tracking

All progress is saved automatically to your browser's `localStorage`:
- **Readiness Score** — Weighted average of your recent performance across categories
- **Category Performance** — Running correct/total for each content area
- **Quiz History** — Last 20 quiz results
- **Missed Questions Deck** — Questions you've answered incorrectly (deduplicated)

### Profile Features

From the **Profile** tab:
- **Export Profile** — Downloads a JSON file with all your progress data
- **Import Profile** — Loads a previously exported JSON file
- **Reset Progress** — Clears all history (with confirmation dialog)

## Opening on Different Platforms

### Desktop (Mac/Windows/Linux)
Simply open `index.html` in your browser. No server needed.

### iOS (iPhone/iPad)
1. Transfer `index.html` to your device (AirDrop, Files app, etc.)
2. Open with Safari (tap and hold → Open with Safari)
3. Optional: tap Share → Add to Home Screen for quick access

### Android
1. Transfer `index.html` to your device
2. Open with Chrome
3. Optional: tap ⋮ menu → Add to Home Screen

## Hosting on GitHub Pages

To share the app with others or access it from any device:

1. Create a new GitHub repository (e.g., `txpc-exam-prep`)
2. Upload `index.html` to the repository root
3. Go to **Settings → Pages → Source** and select your main branch
4. GitHub will provide a URL like `https://yourusername.github.io/txpc-exam-prep/`
5. Share that URL — works on any device with a browser

## Tips for Exam Preparation

1. **Take the Full Practice Test** regularly to simulate real exam conditions
2. **Focus on weak categories** — use the Tailored mode to drill your weakest areas
3. **Review explanations** — every question has an explanation for why the correct answer is right
4. **Use the Missed Questions deck** — regularly retry questions you've gotten wrong
5. **Aim for 80%+** in practice before taking the real exam (provides buffer above the 70% pass line)
6. **Pay special attention to Texas-specific rules** — many questions test TX Insurance Code specifics

## Important Disclaimers

> ⚠️ **This app is for study purposes only and does not guarantee exam results.**

- Questions reflect the Texas General Lines P&C exam content as of the app's creation date
- **Review questions periodically for regulatory changes** — Texas Insurance Code, TDI regulations, and minimum liability limits can change
- The Texas minimum auto liability limits were updated in 2023 to 30/60/25
- TWIA eligibility requirements and NFIP coverage limits should be verified with current official sources
- Exam question formats and content weights may change — always check with Pearson VUE and TDI for current exam blueprints

## Resources

- [Texas Department of Insurance (TDI)](https://www.tdi.texas.gov)
- [Pearson VUE Texas Insurance Exams](https://home.pearsonvue.com/tx/insurance)
- [Texas Insurance Code](https://statutes.capitol.texas.gov/Docs/IN/htm/IN.1.htm)
- [TWIA](https://www.twia.org)
- [NFIP / FloodSmart](https://www.floodsmart.gov)

## Technical Notes

- Single HTML file with all CSS and JavaScript inline
- No external dependencies (no CDN, no backend, no API calls)
- Progress stored in browser `localStorage` (cleared if browser data is reset)
- Works offline after initial load
- Compatible with Chrome 80+, Firefox 75+, Safari 13+, Edge 80+
