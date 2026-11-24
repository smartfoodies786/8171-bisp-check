# 8171 Check Online — BISP Eligibility by CNIC

Static guide site for checking BISP Kafaalat eligibility and payments via the official 8171 portal — guide + official portal link only. No data is collected or stored, and the site never claims to check eligibility itself.

## Pages (8)

- `index.html` — homepage: 20 Nov 2026 portal change callout, 4-step portal check, result-meanings table (5 results), Rs 14,500 payment strip, PMT cutoff, fake-message warning, old-year sections, quick answers, FAQ x10 with FAQPage JSON-LD, Urdu summaries
- `8171-web-portal.html` — portal field by field, "no login exists" correction, lookalike-portal warning
- `pmt-score-check.html` — PMT cutoff table (32 / 37 disabled), exact score only at Tehsil Office, PMT-calculator scam warning
- `8171-check-by-sms.html` — send 13-digit CNIC to 8171, reply meanings, SMS-cost conflict flagged
- `taleemi-wazaif-check.html` — stipend rates, 70% attendance, enrolment
- `bisp-payment-14500.html` — Rs 14,500 Oct–Dec 2026, six banks/wallets, collection, deductions, Rs 18,000 Jan 2027 as planned-not-confirmed
- `bisp-registration-survey.html` — no online registration; in-person NSER survey, free
- `bisp-complaint-helpline.html` — helpline 0800-26477 + Tehsil Office (portal complaint tab removed 20 Nov 2026)

## Verified facts

- Official portal: https://8171.bisp.gov.pk/ — since 20 Nov 2026 asks ONLY for CNIC number + picture code (form number, mobile field, complaint tab removed)
- Current payment: Rs 14,500/quarter, Oct–Dec 2026, from 12 Nov 2026, via HBL, HBL Microfinance, Bank Alfalah, Bank of Punjab, JazzCash, Easypaisa
- PMT cutoff: 32 (37 for households with a registered disabled member); exact score NOT shown online
- Helpline: 0800-26477 (toll-free)

## Deploy

Static site, no build step. Import into Vercel as a static project. Domain not bought yet — replace `example.com` in `sitemap.xml` and `robots.txt` with the live domain before submitting to Search Console, and add canonicals then.
