# CRYPTO RADAR PRO — Version 2 (Web + app preparation)

## Included
- Responsive crypto market dashboard using CoinGecko public API
- Search, sort, gainers/losers, volume and watchlist filters
- Clearly labelled AdSense placement placeholders (no live ads)
- Privacy Policy, Terms of Use, Risk Disclaimer and Contact starter pages
- PWA manifest and service worker for installable-web-app preparation

## Advertising: important setup
The ad areas are placeholders only. They do not display ads or generate revenue.
- Website: after the site has original, useful content and the operator's AdSense account/site is approved, add the official AdSense code and publisher ID supplied by Google.
- Android app: AdMob requires a real Android app integration using the Google Mobile Ads SDK, an AdMob app ID and ad unit IDs. Do not paste AdSense website code into the Android app.
- Never click your own ads, encourage users to click, or use fake traffic.
- Do not publish example or invented ad IDs. Keep test ads enabled during development.

## Google Play preparation
This is currently a PWA-ready website package, not an Android APK or AAB.
To publish an Android app, create a proper Android wrapper/native project, test it, complete the store listing, privacy/data-safety declarations, content rating, app access details, and any required testing/verification. Google reviews each submission; acceptance cannot be guaranteed.
Keep this product informational: no wallet, exchange, custody, deposits, or trade execution is included. Adding those features can trigger additional legal and Google Play requirements.

## Before launch — required owner actions
1. Choose and register a domain.
2. Contact page support email is set to karim071984@gmail.com; confirm this inbox is monitored and approved for public use.
3. Review the Privacy Policy and Terms with the actual hosting, analytics, ad SDKs, and countries served.
4. Obtain and configure real AdSense/AdMob IDs only after the relevant account and app are approved.
5. Test the website on phones and desktop, and verify API rate limits.
6. For Play Console, an adult account owner must complete registration and identity checks if the developer is under 18.

## Deploy the website
Upload all files in this folder to the root of a GitHub repository and import it into Vercel as a static site. No build command is needed; use the repository root as the output directory.

## Notes
- CoinGecko public API rate limits and availability apply.
- No account login, exchange connection, wallet, trading, live push alerts, or AI prediction engine is implemented in this release.
- Privacy and legal pages are starter templates, not legal advice. Complete them accurately before submitting to ad networks or app stores.
\n\n## Multilingual candlestick dashboard update\nThe interface includes English, Arabic, French, Spanish, Portuguese and Turkish language options, plus a live historical OHLC candlestick chart for BTC, ETH, SOL and BNB powered by CoinGecko data and Lightweight Charts. More languages can be added through the translations dictionary in index.html.\n