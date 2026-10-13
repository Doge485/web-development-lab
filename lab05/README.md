# Lab 5 — Responsive Static Website + Wireframes

CineScope is a mobile-first responsive adaptation of Lab 4. No JavaScript or backend is needed.

## Files
- `index.html` — semantic movie website with mobile `<details>` menu
- `style.css` — external CSS, responsive media queries
- `wireframe.svg` — editable/scalable wireframe showing mobile and desktop
- `wireframe.png` — preview image of both wireframes

## Responsive breakpoints
- **Mobile**: under 600px — one movie column; collapsible mobile navigation
- **Tablet**: 600–999px — two movie columns; collapsible navigation
- **Desktop**: 1000px and above — three movie columns and sidebar on right; horizontal navigation
- **Very narrow phones**: at most 359px — reduced spacing and type size via `@media (max-width:359px)`

## Testing
1. Open `index.html` with Live Server.
2. In Chrome DevTools (`F12`), toggle device toolbar (`Ctrl+Shift+M`).
3. Try viewport widths 320px, 375px, 768px, 1024px, 1440px.
4. Confirm navigation changes at 1000px; there is no horizontal scroll or overlapping content.
5. The movie titles and ratings are fictional demo data.

## GitHub
Place this folder at `web-development-lab-old/lab05`, then:
```
git add lab05/
git commit -m "Add Lab 05: Responsive CineScope and wireframes"
git pull --rebase origin main
git push origin main
```
