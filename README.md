# נאלה

A business expense and income tracker. The whole site is a single file: `index.html`.

## Working on it locally

1. Clone the repo: `git clone <repo-url>`
2. Open `index.html` in a browser (double-click it). No build step or server is needed.
3. Edit `index.html`, refresh the browser to see changes.
4. Commit and push: `git add . && git commit -m "describe the change" && git push`

Once pushed to the `main` branch, GitHub Pages updates the live site within a minute or two.

## Notes

- Data people enter (expenses, income, receipts) is saved in their own browser (`localStorage`). It is not shared between devices or users, and clearing browser data erases it.
- Fonts, Chart.js and Tesseract.js (receipt scanning) load from public CDNs, so the page needs an internet connection.
