# Group Order — Template Customisation Guide

This is a community group buying / co-op ordering template. It shows open orders with progress bars, how it works, member savings, and testimonials. It's built around the idea of neighbours pooling purchasing power.

## Key things to customise

**Service name**
- Replace "Gather & Order" with the actual service or co-op name throughout
- Update the nav, footer, page title, and any instances in body text

**Geography**
- Replace "Millbrook" and surrounding area names with real local place names
- Update the delivery area description in the "how it works" section

**Open orders section**
- Replace the 4 order cards with actual current open orders
- Each card has: emoji + title, supplier name, order status badge, progress bar, key metadata (savings, delivery date, minimum), and a deadline
- Status options: `status-open` (green), `status-full` (yellow), `status-closed` (grey)
- Update `style="width:68%"` on each `.progress-fill` to reflect actual fill percentage

**Progress math**
- Update "17/25 joined" and similar labels to match real participant counts
- The progress bar width should equal `(current / max) * 100`%

**Social proof**
- Update the "184 households" figure in the hero
- Replace avatar initials with realistic ones
- Update testimonial names, locations, and quotes

**Savings example**
- The savings comparison (Clonliffe meat box) should be updated with a real product comparison
- Change "€34 per month average saving" to a realistic figure based on actual orders

**Categories grid**
- Update the 8 category cards to match what this service actually organises
- The "Active order" badge (`cat-active`) shows which categories have current open orders — update accordingly

**Email signup**
- The CTA form is cosmetic — connect it to a mailing list, Airtable form, or custom signup backend

**Colours**
- `--purple: #5b4fcf` — main brand purple
- `--indigo: #1e1b5e` — dark indigo (nav, hero, CTA sections)
- `--lavender: #eef0ff` — light lavender (benefits section background)

## What this template works for
- Community group buying co-op
- Neighbourhood food collective
- Bulk order club for a street, estate, or apartment block
- Community-supported agriculture (CSA) with multiple producers
- Food hub or buying group for a school, parish, or sports club
