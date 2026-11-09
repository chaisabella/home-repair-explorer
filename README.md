# Home repair explorer

An interactive cutaway house for people who have never worked in construction or home repair. Hover over a part of the house to see typical repair and replacement costs. Click it to read what the part does, what goes wrong, why to fix it early, and who you would call.

## What is in it

- Outside and inside views of a two-story house with a basement and attic
- Hover prices and a detail panel for each part and room
- "What are you seeing at home?" chips (leaking ceiling, damp basement, and so on) that point to likely causes
- A short house tour
- A "who fixes what" list of trades

## Run it locally

It is a single file with no build step and no dependencies. Open `index.html` in a browser.

## Notes on the numbers

Prices are national ranges in US dollars. Ranges that start with `~` are ballpark estimates. The rest come from published 2026 cost guides (HomeAdvisor, NerdWallet, Liberty Home Guard and others). Costs vary by market and house age, so treat them as a starting point and get written quotes.

The three priority groups (dry and running, healthy and safe, works for the people who live there) follow a standard home assessment approach. An inspector decides which group a particular problem belongs in.

## Editing

Everything is in `index.html`:

- Styles are in the `<style>` block at the top.
- The house is the inline `<svg>`.
- Parts, costs, symptoms, tour stops and people are plain JavaScript objects in the `<script>` block (`comps`, `ZONES`, `SYMPTOMS`, `TOUR`, `PEOPLE`). The `GLOSSARY` list is still in the file but is not shown on the page.
