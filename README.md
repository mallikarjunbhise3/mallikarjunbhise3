# Mallikarjun Bhise — Salesforce Commerce Cloud (SFCC/SFRA) Developer

Full-stack **Salesforce Commerce Cloud (SFCC/SFRA)** developer at **OSF Digital** with **800+ merged pull requests** across six international e-commerce platforms. Experience spans security remediation, payments integration & migration, major feature builds, data-feed pipelines, and performance optimization — delivered across multi-locale storefronts (FR, UK, JP, US, IT, Chile).

---

## 🧭 Projects Overview

| Project | Domain | Role Focus | Active Period |
|---|---|---|---|
| 🎾 **Babolat** | Sports equipment | Security, payments, search, BIS, features | Apr 2023 → present |
| 🛒 **Gifi / Go Sport** | Retail | BO-store order mgmt, cart/checkout, marketplace | Jun 2023 → Jan 2024 |
| 🍵 **Kusmi Tea** | Premium F&B | Klaviyo/CRM migration, Tapbuy, SEO | Jul 2025 → present |
| 🛍️ **CWF luxury brands** | Luxury fashion | Adyen migration, performance, feeds, compliance | Mar 2026 → present |
| 🎮 **Micromania** | Video games | PLP redesign, bundle automation, Click & Collect | Feb 2024 → Jan 2025 |
| 🖼️ **Shoppable Images (R&D)** | R&D | Caching configuration | Jan 2023 |

---

## 🎾 Babolat Implementation (SFCC)
Global sports-equipment retailer — multi-locale (FR, UK, JP, US, IT, Chile). Primary, longest-running project.

- **Security Assessment & Remediation Program:** CSRF protection, Address IDOR fix, hardcoded VIP password removal, payment-endpoint security controls (SubmitPreAuth), PII violation fix, custom-object flooding prevention, reCaptcha on VIP endpoints, OCAPI secret-exposure fix, SaveProfile authentication, payment-data validation.
- **Back In Stock (BIS) system:** subscription logic, de-duplication job, dashboard, email translation/sender config, anti-spam controls.
- **Payments (Adyen/PayPal):** PayPal fraud cancellation, Adyen webhook errors, order-confirmation handling.
- **Search Improvement:** Popular Searches activation + frontend support.
- **Checkout / Cart / PDP:** address-field validation, country selector + geolocation redirect, UPS address autofill, stringing-service flows, add-to-cart carousel fixes.
- **Other:** Product Finder/Quiz, Bazaarvoice feed, SEO redirects, accessibility (XML sitemap), Lamborghini VIP component, SFCC email sender.

## 🛒 Gifi — Go Sport Group (SFCC)
Tickets: `GIFIR` / `VENUS`. Focus on in-store back-office operations and storefront.

- **BO Store order management:** order detail/listing pages, status columns & labels, cancellation reasons, quantity dropdowns, export-file fixes, validation.
- **Mirakl Marketplace:** list-price display for marketplace products.
- **Cart / Checkout / PDP:** deleted-products error handling, max-quantity vs inventory, add-to-cart cache issues, price-per-liter/kilo config, click-&-collect selection.
- **Other:** wishlist sharing, GDPR customer purge, structured data (SEO), voucher display, cross-sell carousel, deprecated-API cleanup.

## 🍵 Kusmi Tea Maintenance
Premium tea brand. Tickets: `KSMIT` / `KTCXN`.

- **Klaviyo Migration:** transactional emails MC→Klaviyo, newsletter opt-in, order-confirmation events, reset-password link, customer create/update hook, e-giftcard events.
- **Tapbuy Integration:** cartridge updates, locale additions, US fixes.
- **SEO / Structured data:** JSON-LD Organization & product markup, hreflang/seasonal-URL config.
- **Promotions / Cart / DataLayer:** qualifying-product promo bug, bonus-product list, add-to-cart quantity-modifier event, Pop-in Welcome.

## 🛍️ CWF Luxury Brands (CWF Audit)
Claudie Pierlot, Maje, Zadig & Voltaire, Billieblush, Kids Around. Tickets: `FRUS` / `CWFMT` / `FRCWB`.

- **Adyen Payment Migration:** fatal payment-error fixes, pickup-point delivery, duplicate confirmation emails, PSP order/customer export & status, refund/return email corrections, PaymentMethod tag.
- **Performance Optimization:** DB-intensive Product API refactor, Search-Show controller cache strategy.
- **SFSC integration & export jobs:** customer file re-send/re-export, duplicate-file fix, shopping-feed archive/versioning, AGEC legal-mention traceability (compliance), SFTP fixes.
- **Other:** DataLayer, SEO (gen_color meta/OG/JSON-LD), PDP discount display, brand banner.

## 🎮 Micromania (SFCC)
France's leading video-game retailer. Tickets: `SMCR` / `MCMSM`.

- **PLP Redesign:** breadcrumb + title redesign, modular grid logic, product-tile redesign, pagination, price/universe filters, quick-access links, structured data, SEO box → FAQ.
- **Bundle automation:** auto-disable on out-of-stock, auto-reactivate on restock, Mega Bundle handling.
- **Click & Collect / Delivery:** favorite-store delivery restrictions, carrier restrictions at basket level, console/warranty C&C bug, in-store availability messages.
- **Loyalty / Checkout / Brand pages:** point-gain cache fix, CB order on homologation, €10 discount misuse, brand-page custom templates, shipping-method filtering.

## 🖼️ Shoppable Images (R&D)
Tickets: `FSMOR`. Cache-configuration tuning.

---

## 🛠️ Skills Snapshot

| Area | Highlights |
|---|---|
| **Platform** | Salesforce Commerce Cloud (SFCC / SFRA), ISML, OCAPI, SCSS |
| **Security** | CSRF, IDOR remediation, PII handling, secret management, reCaptcha, auth middleware |
| **Payments** | Adyen, PayPal, PayPlug, CB — integration, migration & error remediation |
| **Integrations** | Klaviyo, Tapbuy, Bazaarvoice, SFSC, Mirakl, Marketing Cloud, GTM/DataLayer |
| **E-commerce features** | PLP/PDP redesign, Back-In-Stock, bundle automation, Click & Collect, BO-store order management, loyalty |
| **Performance** | DB-intensive API refactors, caching strategies, large-file processing |
| **Jobs / Batch** | Product/customer feed exports, SFTP pipelines, GDPR customer purge, scheduled-job fixes |
| **Compliance & SEO** | AGEC legal mentions, structured data (JSON-LD), hreflang, redirects, accessibility (ARIA, XML sitemap) |
| **Localization** | Multi-locale delivery: FR, UK, JP, US, IT, Chile |

---

*Generated from authored pull request history across the OSF Digital organization.*
