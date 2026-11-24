# BETWEEN US v0.3
Mobile-first PWA prototype. Light premium visual style (ivory, burgundy, muted gold), high contrast and larger player labels.

## Current gameplay
- One shared phone, two players.
- 20 questions per round.
- Four stages: player 1 answers; player 2 guesses; player 2 answers; player 1 guesses. Both directions are scored at the end.
- Final screen compares both sets of answers.
- Each question has multiple-choice answers plus a custom-answer field.
- Ukrainian and English interface.

## Deploy
Upload `index.html`, `questions.json`, `manifest.webmanifest`, and `sw.js` to the root of the GitHub Pages repository. The service-worker cache is versioned `v03`; refresh the site after deployment.

## Prototype limitations
This v0.3 iteration implements the revised one-phone flow. Two-phone code exchange is not included in this revised flow yet. Matching is exact normalized text matching; semantically equivalent custom answers may be counted as different. The score is a game result, not a relationship compatibility measure.
