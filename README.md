# RTM SOFT website

Static company website for RTM SOFT Co., Ltd., used as the public organization website for the Apple Developer Program migration. It has no build step.

## Preview

```bash
python3 -m http.server 8000
```

## Deploy

Push to a GitHub repository and enable GitHub Pages from the `main` branch. The `CNAME` file sets the custom domain, `rtm-soft.com`. Point its DNS at GitHub Pages.
