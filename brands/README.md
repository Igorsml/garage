# Service logos

- `vk.svg`, `telegram.svg`, `instagram.svg`, `googleforms.svg`: Simple Icons, retrieved from https://cdn.simpleicons.org/ . Brand marks remain the property of their respective owners.
- `teddyfood.svg`: original service mark from https://teddyfood.com/static/logo.svg .
- `ozon.png`, `avito.png`: site favicons retrieved through Google's favicon cache for ozon.ru and avito.ru.

Assets are stored locally so visitors do not request favicons from third-party services. Logos identify the destinations of links; they do not imply endorsement.

The website uses monochrome inline SVG marks generated into `src/components/brand-marks.ts` by `scripts/generate-brand-marks.mjs`. VK, Telegram, Instagram, Google Forms and Teddy Food retain the silhouettes of their source vectors. Ozon is a compact redrawn wordmark; Avito uses its four characteristic circles. All marks use `currentColor` to match light and dark themes. PNG favicons above remain archived sources and are not used for service icons on the page.
