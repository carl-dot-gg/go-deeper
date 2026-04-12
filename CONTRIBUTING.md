# Contributing to go deeper

Thanks for wanting to make conversations better! Here's how you can help.

## 🆕 Adding new questions

### What makes a good question?

**DO:**
- Questions that reveal character, values, or hidden truths
- Questions that take courage to answer honestly
- Questions that create connection, not just information exchange
- Short, punchy questions (under 20 words ideal)
- Questions that assume the truth ("What lie do you tell yourself?" not "Do you lie to yourself?")

**DON'T:**
- Yes/no questions
- Questions with obvious "right" answers
- Questions that feel like an interrogation
- Questions that are too dark without purpose
- Questions that only work for specific demographics

### How to submit

1. Fork this repo
2. Edit `questions.json`
3. Add your question with:
   ```json
   {
     "id": "x99",
     "depth": "deeper",
     "en": "Your question in English?",
     "fr": "Ta question en français?"
   }
   ```
4. Submit a Pull Request with:
   - The question
   - Why you think it belongs at that depth level
   - (Optional) Source or inspiration

### Depth level guide

| Level | Courage required | Example |
|-------|------------------|---------|
| **Light** | Zero risk | "What's your hidden talent?" |
| **Medium** | Low risk | "What did your parents get right?" |
| **Deep** | Medium risk | "What battle did you win that no one saw?" |
| **Deeper** | High risk | "Whose life are you living?" |

The key is **courage required to answer honestly**, not darkness.

## 🌍 Improving translations

### French
- We use casual "tu" form, not formal "vous"
- Spoken register, not literary
- Natural phrasing over literal translation

### Adding new languages
1. Add a new field to each question in `questions.json` (e.g., `"es"` for Spanish)
2. Update the language toggle in `index.html`
3. Submit a PR

## 🐛 Reporting issues

Found a typo? Question doesn't land right? Open an issue with:
- What's wrong
- Where it is (question ID)
- Suggested fix (if you have one)

## 🎨 Design contributions

The visual identity:
- Colors: Warm cream (#F5F2ED), forest green (#2D4A3E), stone gradients
- Typography: DM Serif Display (questions), DM Sans (UI)
- Vibe: Warm, minimal, inviting — not clinical or dark

---

Questions about contributing? Open an issue and ask.
