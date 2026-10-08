# Project Placeholders Documentation

This document lists all exact `[PLACEHOLDER]` variables present across the static lead generation landing page files (`index.html`, `privacy.html`, `terms.html`, `thank-you.html`, `robots.txt`, `sitemap.xml`, `llms.txt`).

Before launching the site in production, search and replace each of these placeholder tags with your actual brand, contact, pricing, and infrastructure details.

---

## 🏢 Brand & Contact Details

| Placeholder Tag | Description & Format | Files Present |
| :--- | :--- | :--- |
| `[AGENCY_NAME]` | Your digital marketing agency name (e.g. *Digitacurve Media*) | `index.html`, `privacy.html`, `terms.html`, `thank-you.html`, `robots.txt`, `sitemap.xml`, `llms.txt` |
| `[DOMAIN]` | Web domain without protocol (e.g. *digitacurve.com*) | `index.html`, `privacy.html`, `terms.html`, `thank-you.html`, `robots.txt`, `sitemap.xml`, `llms.txt` |
| `[EMAIL]` | Primary support/business inquiry email address | `index.html`, `privacy.html`, `terms.html`, `llms.txt` |
| `[PHONE]` | Primary phone number formatted with country code (e.g. *+91 98765 43210*) | `index.html`, `privacy.html`, `terms.html`, `llms.txt` |
| `[WHATSAPP_NUMBER]` | WhatsApp phone number in pure digits without '+' (e.g. *919876543210*) | `index.html`, `thank-you.html`, `llms.txt` |
| `[ADDRESS]` | Street / Office street address | `index.html`, `privacy.html`, `terms.html`, `llms.txt` |
| `[CITY]` | City name (e.g. *Mumbai*, *Delhi*, *Bengaluru*) | `index.html`, `privacy.html`, `terms.html`, `llms.txt` |
| `[STATE]` | State name (e.g. *Maharashtra*, *Karnataka*) | `index.html`, `privacy.html`, `terms.html`, `llms.txt` |
| `[PINCODE]` / `[PIN]` | 6-digit postal code (e.g. *400001*) | `index.html`, `privacy.html`, `terms.html`, `llms.txt` |

---

## 💰 Pricing & Plans

| Placeholder Tag | Description & Format | Files Present |
| :--- | :--- | :--- |
| `[STARTING_PRICE]` | Lowest starting price text (e.g. *₹14,999/mo*) | `index.html` |
| `[PRICE_RANGE]` | Schema price range string (e.g. *₹15,000 - ₹1,50,000 INR*) | `index.html` |
| `[PRICE_STARTER]` | Monthly price for Starter tier (e.g. *₹14,999*) | `index.html` |
| `[PRICE_GROWTH]` | Monthly price for Growth tier (e.g. *₹29,999*) | `index.html` |
| `[PRICE_SCALE]` | Monthly price for Scale tier (e.g. *₹59,999*) | `index.html` |
| `[BEST_FOR_STARTER]` | Target client description for Starter plan | `index.html` |
| `[BEST_FOR_GROWTH]` | Target client description for Growth plan | `index.html` |
| `[BEST_FOR_SCALE]` | Target client description for Scale plan | `index.html` |
| `[INCLUDES_STARTER]` | Key inclusions string for Starter plan | `index.html` |
| `[INCLUDES_GROWTH]` | Key inclusions string for Growth plan | `index.html` |
| `[INCLUDES_SCALE]` | Key inclusions string for Scale plan | `index.html` |
| `[PRICE_VIDEO_EDITING]` | Price estimate for Video Editing service | `index.html` |
| `[PRICE_YT_SEO]` | Price estimate for YouTube Growth & SEO | `index.html` |
| `[PRICE_LEADGEN]` | Price estimate for Lead Generation Funnels | `index.html` |
| `[PRICE_PPC]` | Price estimate for Google & Meta Ads | `index.html` |
| `[PRICE_SEO]` | Price estimate for Website SEO | `index.html` |
| `[PRICE_WEBSITE]` | Price estimate for Landing Page & Web Dev | `index.html` |
| `[PRICE_SOCIAL]` | Price estimate for Social Media Management | `index.html` |
| `[PRICE_ACCOUNT_MGMT]` | Price estimate for Dedicated Account Management | `index.html` |

---

## 📊 Proof & Guarantees

| Placeholder Tag | Description & Format | Files Present |
| :--- | :--- | :--- |
| `[CLIENT_1]` | First featured client/brand name | `index.html` |
| `[CLIENT_2]` | Second featured client/brand name | `index.html` |
| `[CLIENT_3]` | Third featured client/brand name | `index.html` |
| `[RATING]` | Aggregate rating score out of 5 (e.g. *4.9*) | `index.html` |
| `[RESULT_3]` | Highlights of client 3 results (e.g. *10M+ views & 3.5x revenue*) | `index.html` |
| `[RESPONSE_TIME]` | Team response time claim (e.g. *15 Minutes*) | `index.html`, `thank-you.html` |
| `[LAUNCH_DAYS]` | Campaign launch speed promise (e.g. *48 Hours*) | `index.html` |
| `[COMMISSION_OR_PRICE]` | Guarantee or commission policy text | `index.html` |
| `[NICHE]` | Targeted industry niche (e.g. *Creators, E-commerce & EdTech*) | `index.html` |

---

## 🔗 Technical & External Endpoints

| Placeholder Tag | Description & Format | Files Present |
| :--- | :--- | :--- |
| `[FORM_ENDPOINT_URL]` | Form submission endpoint (e.g. *https://formspree.io/f/xyz* or your custom API backend) | `index.html` |
| `[INSTAGRAM_URL]` | Official Instagram profile link | `index.html` |
| `[YOUTUBE_URL]` | Official YouTube channel link | `index.html` |
| `[LINKEDIN_URL]` | Official LinkedIn company page link | `index.html` |
| `[X]` / `[TWITTER_URL]` | Official X / Twitter profile link | `index.html` |

---

## 🛠️ Instructions for Replacement

You can replace all placeholders at once using bash `sed` commands. For example:

```bash
cd /path/to/leadgen-site
sed -i '' 's/\[AGENCY_NAME\]/Digitacurve Media/g' *.html *.txt *.xml *.md
sed -i '' 's/\[DOMAIN\]/digitacurve.com/g' *.html *.txt *.xml *.md
sed -i '' 's/\[EMAIL\]/contact@digitacurve.com/g' *.html *.txt *.xml *.md
sed -i '' 's/\[PHONE\]/+91 98765 43210/g' *.html *.txt *.xml *.md
sed -i '' 's/\[WHATSAPP_NUMBER\]/919876543210/g' *.html *.txt *.xml *.md
sed -i '' 's/\[FORM_ENDPOINT_URL\]/https:\/\/formspree.io\/f\/example/g' index.html
```
