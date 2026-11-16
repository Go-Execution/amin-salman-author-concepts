# Dr. Amin Salman — two website concepts

Two independently accessible, responsive author website concepts built with React, TypeScript, Vite, and Tailwind CSS.

## Preview

```bash
npm install
npm run dev
```

- `/` — concept selection
- `/concept-one` — Heritage Editorial
- `/concept-two` — Modern Literary Minimalism

Run `npm run build` for a production build.

## Client assets and commerce setup

The supplied brief referenced a website screenshot and book-cover PDF, but those files were not present in the provided attachment. All three product visuals are explicitly labelled temporary placeholders. The portrait and video are also placeholders. Replace the `cover` values in `src/data/books.ts` with paths to approved, unaltered front-cover images placed in `public/`. Add the approved author portrait, biography, video content, and contact details before launch.

The catalogue is shared by both concepts in `src/data/books.ts`. Set each `priceUsd` to an approved USD amount. Until prices are supplied, the cart can be explored but totals remain pending. Checkout is a visible demo interface with no payment submission. A secure payment provider, verified settlement account, shipping rules, tax handling, order processing, privacy/terms copy, and email delivery must be configured before accepting orders or messages. Newsletter and contact forms are presentation previews only.

The project intentionally contains no API keys or payment credentials.
