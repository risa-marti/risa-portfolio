# Risa Martignon — Portfolio

Built with React + Vite + React Router. Deployed on Vercel.


## File structure

```
src/
  assets/
    images/          ← drop all your photos here
  components/
    Nav.jsx          ← sticky navigation
    Footer.jsx       ← footer with legal name
    PhotoSlot.jsx    ← image placeholder component
    ProjectPage.jsx  ← shared layout for all project pages
  pages/
    Home.jsx
    Projects.jsx     ← project index with filters
    Activities.jsx
    Hobbies.jsx
    projects/
      EFR.jsx
      SPORE.jsx
      Apollo.jsx
      CloudChamber.jsx
      ElectricCart.jsx
      PWA.jsx
```

---

## Colours (to change the theme)

All colours are CSS variables in `src/index.css`:

```css
--blush:     #F9F0F3;   /* page background */
--petal:     #F3D9E3;   /* card backgrounds */
--rose:      #E8B4C8;   /* borders, graph paper lines */
--deep-rose: #C47A95;   /* primary accent */
--berry:     #8B4A6B;   /* hover states, logo */
--ink:       #2D2D2D;   /* body text */
--ink-soft:  #5A4A50;   /* secondary text */
```
