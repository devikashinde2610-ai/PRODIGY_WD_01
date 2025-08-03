
## How to Run
1. Clone the repo:  
   `git clone https://github.com/<your-username>/PRODIGY_WD_01.git`
2. Open `index.html` in any browser.  
   No build tools required; it’s a static HTML/CSS/JS demo.

## Customization Tips
- Change colors via CSS variables in `:root` (`--bg-scrolled`, `--accent`, etc.).
- Extend to a multi-page site by including the same `nav` markup in other HTML files.
- Replace anchors with real routes for SPA frameworks or server-rendered pages.

## Key Learnings
- Managing dynamic UI state based on scroll position.  
- Using `IntersectionObserver` to track visibility and update navigation.  
- CSS transitions and pseudo-elements for smooth interactive feedback.  
- Accessibility basics: focus states, semantic markup, and ARIA roles.

## Demo / Screenshots
(Insert GIF or screenshot of scrolling and hover state here.)

## Sample Commit Message
`feat: add interactive fixed navigation menu with scroll and hover styles`

## Next Steps
- Add mobile hamburger toggle with animated open/close.  
- Make the menu into a reusable component (e.g., for React or vanilla JS import).  
- Add unit/integration tests for link activation logic.

