---
name: menu-or-price-list
description: Make a menu, price list, service list or rate card with DALFAST Studio. Use when someone needs a restaurant, café or bar menu, a salon or studio price list, a class timetable or a list of services with prices.
---

# Menus and price lists with DALFAST Studio

## Flow

1. Ask for the **items and prices exactly as they should appear**, grouped if they have groups (Starters, Mains, Drinks; Cuts, Colour, Treatments). Also the name, opening hours or contact line if wanted, and the currency.
2. **Never fill in prices, items, allergens or descriptions they did not give.** If a price is missing, leave the item without one and say so.
3. `find_templates` with format **Menu** (or **Poster** or **Instagram post** for a short price list), e.g. `{"query": "cafe menu", "format": "Menu"}`. Offer two or three by name.
4. `design_from_template` with `brand` (name), `title` ("Menu", "Price list", or their wording), `body` (the items and prices, one per line, groups as short headings; up to 1,500 characters), `details` (hours, address or phone they gave).
5. Long lists may not fit the template's text space: say that the full list can be finished and laid out in DALFAST Studio with the link, where more pages can be added.
6. Print: `download_design` as PDF. Screens and social: PNG. An Instagram post or Story version with the highlights is one more design.

## Always

- Use only the person's own facts. Never make up prices, dates, times, addresses, phone numbers, names, reviews, awards or discounts. Leave a field out rather than guess, and say what is missing.
- Keep their spelling of names and places. Ask before translating.
- One short question at most when something essential is unclear; otherwise make it and offer changes.
- Every design is saved in the person's own DALFAST Studio account. Give the "Open in DALFAST Studio" link with every design.
- Nothing is ever deleted through the connector.
- Help: https://dalfast.studio/connect · support@dalfast.studio
