# Catherine Nolasco Portfolio

A single-page, static portfolio for Catherine Nolasco, SHRM-CP, tailored to the Director of Global HR Operations role at Auction Technology Group.

## View it

Open `index.html` in a browser, or publish it with GitHub Pages (Settings, Pages, deploy from the `main` branch, root folder).

## Files

- `index.html`: the finished page. Fonts are embedded, so it works offline with no build step.
- `src/content.py`: all page text and data.
- `src/build_portfolio.py`: generates `index.html` from the content and styles.
- `src/fonts/`: Montserrat font files used by the build script.

## Rebuild

```
cd src
python3 build_portfolio.py
```
