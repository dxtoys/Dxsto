DXSTOCK ALERT — ANDROID PWA · NSE FEED UPGRADE

WATCHLIST
- CUPID — Cupid Ltd
- GODREJIND — Godrej Industries
- GODREJCP — Godrej Consumer Products
- JPL — Jio Platforms
- RELIANCE — Reliance Industries
- RAYMOND — Raymond Ltd

DATA SOURCES
- Google News RSS search results, per company.
- NSE India public RSS: corporate announcements, corporate actions, board meetings, financial results and insider trading.
- NSE feed directory: https://www.nseindia.com/static/rss-feed
- RSS feeds are converted through the public RSS2JSON service because browser pages cannot reliably fetch the NSE XML directly (CORS). That converter is a third party and may rate-limit or fail.

FEATURES
- Six-company watchlist with per-company filters.
- Combined news and exchange-feed dashboard.
- Separate filters for exchange filings and corporate actions.
- Keyword-based potentially positive/negative/neutral hints.
- Important-news filter, local cache, CSV export.
- Refresh on open and every 15 minutes while the app is visible.
- Android-installable PWA when hosted on HTTPS.

IMPORTANT LIMITATIONS
- This is not guaranteed real-time, not an exchange-grade terminal, and does not guarantee every relevant filing is captured.
- NSE RSS is filtered by company-name/symbol matching. Filings that use abbreviations, subsidiaries, or unusual entity names may be missed.
- Free RSS conversion service has availability and rate limits; no API key or paid data plan is included.
- Dashboard-only means no background push alerts. Refresh runs only while the app is open/visible.
- Bulk/block-deal monitoring is not included in this build; it needs a reliable structured exchange source and separate validation.
- Sentiment is a basic keyword heuristic, not an AI assessment, prediction, or investment advice.
- Jio Platforms is configured as JPL per the selected watchlist; confirm the exact listed security identifier against your broker/exchange before relying on it.

INSTALL ON ANDROID (FREE)
1. Create a free GitHub account and a public repository named dxstock-alert.
2. Upload all files from this folder to the repository root.
3. In repository Settings > Pages, deploy from the main branch and root folder.
4. Open the published HTTPS URL in Chrome on Android.
5. Chrome menu > Install app / Add to Home screen.

The app uses no broker credentials and cannot place trades.
