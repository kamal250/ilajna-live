---
title: How I Made My Digital Garden for Under ₹300 Only!
slug: how-I-made-my-digital-garden-for-under-₹300-only
description: My learning to put the site online very cost-effectively
tags:
  - advice
  - learning
added: 2025-12-01T17:16:03.580Z
---

Creating a personal space on the internet doesn’t have to be expensive. In fact, I built my own digital garden — a space where I store my thoughts, notes, web-server guides, shell commands, configs and development learnings — for less than ₹300.

Yes, that's right — a fully functional website with DNS and hosting handled, accessible publicly, and managed with ease. Here’s exactly how I did it.

### 💡 Step 1: Buying the Domain (Cost: ₹\<300 Only)

I purchased a domain from CrazyDomains (Why CrazyDomains? I purchased my domains in the past from them) without opting for any extra add-ons or bundled services.

The goal was simple: keep costs low and take full control myself later through Cloudflare.

Domain price: Under ₹300 — the only money spent in this entire setup

![](</assets/1. domain under 300INR.png>)

### ⚙ Step 2: Pointing the Domain to Cloudflare

Next, I created a free account on Cloudflare and added my domain there. Cloudflare provided me with two Name Servers which I updated in CrazyDomains so Cloudflare could manage my DNS easily.

Why Cloudflare?

* Super fast DNS propagation
* Easy DNS record management
* No extra cost

![](</assets/2. Name Servers.png>)

At this point, my domain was functional — DNS sorted ✔

Now it was time to host my site.

### 🚀 Step 3: Hosting the Site Using Netlify (Free)

I needed a simple, reliable, fast hosting platform — and Netlify was the perfect choice. Since my project is public on GitHub, deployment was as smooth as it gets.

Steps I followed:

1. Pushed my static site to a GitHub repository.
2. Connected the repo to Netlify for auto-deploy on every commit.
3. Under Netlify → Your Project → Domain Management, I added my custom domain.
4. Netlify provided a TXT DNS record for verification.
5. I added that TXT record inside Cloudflare and verification happened almost instantly.

![](</assets/3. TXT Records.png>)

### 🌐 Adding Domain Alias

With domain ownership verified, only one final step remained — pointing the domain to Netlify.

I added a CNAME record in Cloudflare, and Netlify automatically handled rests on its own.

Result:
🔹 digitalgarden.ilajna.live → Works

Everything now runs securely, smoothly and — most importantly — freely.

### 🎉 Final Outcome

| Component  | Service Used | Cost   |
| ---------- | ------------ | ------ |
| Domain     | CrazyDomains | ₹\<300 |
| DNS        | Cloudflare   | Free   |
| Hosting    | Netlify      | Free   |
| Repository | GitHub       | Free   |

Total Cost = Under ₹300 Only

For a personal digital garden, knowledge hub, blog, or project showcase — this setup is lightweight, affordable, and beginner friendly.

### 🔚 Closing Thoughts

If you’ve been wanting to create your own digital garden or personal site, cost is no longer an excuse. With a one-time domain purchase and the power of Cloudflare + Netlify, you can get online almost instantly.

I hope my setup helps you start yours as well!
