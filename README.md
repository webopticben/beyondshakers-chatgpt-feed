# Beyond Shakers – ChatGPT Ads product feed

`chatgpt-feed.csv` is the product feed for OpenAI Ads Manager (OpenAI product file schema).

- Source: the Shopify page `https://beyondshakers.com/pages/chatgpt-feed`, rendered by the
  theme template `templates/page.chatgpt-feed.liquid`.
- A GitHub Action (`.github/workflows/refresh-feed.yml`) downloads it every hour and commits
  any changes, so stock, prices and new products flow through automatically.
- Published via GitHub Pages; that URL is the Hosted URL in Ads Manager.

To change what's in the feed, edit the Liquid template in the Shopify theme, not this CSV.
