# GitHub Pages Setup

## Enable GitHub Pages

1. Go to **https://github.com/Jaun7707/StrideQuest-Site**
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Set **Branch** to `main` and **Folder** to `/ (root)`
5. Click **Save**

The site will be live within a few minutes at:

**https://jaun7707.github.io/StrideQuest-Site/**

## App Store Connect URLs

### English (default)

| Field | URL |
|-------|-----|
| **Privacy Policy URL** | `https://jaun7707.github.io/StrideQuest-Site/privacy.html` |
| **Terms of Service URL** | `https://jaun7707.github.io/StrideQuest-Site/terms.html` |
| **Support URL** | `https://jaun7707.github.io/StrideQuest-Site/support.html` |
| **Marketing URL** | `https://jaun7707.github.io/StrideQuest-Site/` |

### Spanish (es)

| Field | URL |
|-------|-----|
| **Privacy Policy URL** | `https://jaun7707.github.io/StrideQuest-Site/es/privacy.html` |
| **Terms of Service URL** | `https://jaun7707.github.io/StrideQuest-Site/es/terms.html` |
| **Support URL** | `https://jaun7707.github.io/StrideQuest-Site/es/support.html` |
| **Marketing URL** | `https://jaun7707.github.io/StrideQuest-Site/es/` |

### Japanese (ja)

| Field | URL |
|-------|-----|
| **Privacy Policy URL** | `https://jaun7707.github.io/StrideQuest-Site/ja/privacy.html` |
| **Terms of Service URL** | `https://jaun7707.github.io/StrideQuest-Site/ja/terms.html` |
| **Support URL** | `https://jaun7707.github.io/StrideQuest-Site/ja/support.html` |
| **Marketing URL** | `https://jaun7707.github.io/StrideQuest-Site/ja/` |

### Simplified Chinese (zh-Hans)

| Field | URL |
|-------|-----|
| **Privacy Policy URL** | `https://jaun7707.github.io/StrideQuest-Site/zh-Hans/privacy.html` |
| **Terms of Service URL** | `https://jaun7707.github.io/StrideQuest-Site/zh-Hans/terms.html` |
| **Support URL** | `https://jaun7707.github.io/StrideQuest-Site/zh-Hans/support.html` |
| **Marketing URL** | `https://jaun7707.github.io/StrideQuest-Site/zh-Hans/` |

## Custom Domain (Optional, Later)

If you later set up `stridequests.app` as a custom domain:

1. In **Settings → Pages**, enter `stridequests.app` under **Custom domain**
2. Create a `CNAME` file in the repo root containing `stridequests.app`
3. Configure DNS at your registrar (CNAME or A records pointing to GitHub Pages)
4. Enable **Enforce HTTPS**
5. Update the URLs in App Store Connect and `ReleaseConfig.swift` to use the custom domain

## Updating Content

Edit the HTML files directly on `main` branch. GitHub Pages redeploys automatically on push.
