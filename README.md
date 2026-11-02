# Terrabox — terrabox networks ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `terraboxnetworksltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/terraboxnetworksltd.mjs`).
> To change the content, edit that file and run `node build.mjs terraboxnetworksltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@terraboxnetworksltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($1 week / $£[AMOUNT] / $5 weeks) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Terrabox Networks Ltd lets and operates its own and leased residential property in London, and has been trading since 2013. We let as the landlord rather than as an agent for anyone else, which is worth saying plainly because it changes what applies: an agent must belong to a redress scheme and protect client money, and a landlord letting its own property is not in that regime, so we do not claim protections we are not subject to. What we do instead is run the checks properly. In England a landlord must establish that every adult who will occupy the property as their main home has the right to rent, before they move in and not afterwards, and that means all adult occupiers rather than only the person who signs. Getting it wrong carries a civil penalty of up to ten thousand pounds per occupier for a first breach, and knowingly letting to someone disqualified is a criminal offence. The part most landlords miss is that checking only the people who look foreign to them is unlawful discrimination, so the same discipline protects against both: check everyone, identically, and keep the record. Site: terraboxnetworksltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
