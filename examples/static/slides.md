---
addons:
  - slidev-addon-inalia
---

# Static Example

Your first question is on the next slide, without requesting any data from the Inalia API.

---

<Inalia
  question="my first question"
  type="text"
  :data="['c\'est une réponse ça', 'c\'est toujours aussi agréable']"
/>
