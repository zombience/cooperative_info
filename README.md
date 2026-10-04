# Cooperative Info

A shared learning hub for our group as we form a **housing cooperative in Chicago**.

We're six households. Four are buying in now and two plan to join in about two years. We're buying one property. We care more about community than about financial gain, while being realistic about the financial system we live in.

Our co-op lawyer handles the legal side. **This repo is mostly about the money**: learning enough about co-op finance to make good decisions together, then bringing in a financial professional to review them.

## Where to start
1. **[Start here](docs/learning-path/00-start-here.md)**: how the learning path works.
2. Work through the **[learning path](docs/learning-path/00-start-here.md#the-steps)** together, one step every week or two.
3. Record decisions in the **[decision log](docs/worksheets/decision-log.md)**.

## What's in here
| Folder | What it holds |
|---|---|
| [`docs/learning-path/`](docs/learning-path/) | Ten guided steps, from "what's a co-op" to closing. Each has short readings, discussion questions, and what to decide. |
| [`docs/resources/`](docs/resources/) | Curated, annotated links: [Radish & co-buying](docs/resources/radish-and-cobuying.md), [finance & structures](docs/resources/finance-and-structures.md), [Chicago & Illinois](docs/resources/chicago-illinois.md), [organizations](docs/resources/organizations.md). |
| [`docs/worksheets/`](docs/worksheets/) | Things to fill in and bring to meetings: the [four-now-two-later worked example](docs/worksheets/scenario-staggered-entry.md), [member snapshot](docs/worksheets/member-snapshot.md), [questions for our lawyer](docs/worksheets/questions-for-our-lawyer.md), [questions for a financial professional](docs/worksheets/questions-for-a-financial-advisor.md), [decision log](docs/worksheets/decision-log.md). |
| [`docs/glossary.md`](docs/glossary.md) | Plain-language definitions. |

## If you only read five things
1. [Chicago Housing Cooperatives, Explained](https://www.citybureau.org/newswire/2022/11/2/chicago-housing-cooperatives-explained) (City Bureau)
2. [The Radish FriendLLC Model Explained](https://supernuclear.substack.com/p/the-radish-friendllc-model-explained) (Supernuclear)
3. [Guide to Resale Policies](https://uhab.org/resource/guide-to-resale-policies/) (UHAB)
4. [Holding the Line: Inside Chicago's Trailblazing Housing Cooperatives](https://eps.edu.miami.edu/_assets/pdf/chicago-field-note-new-generation-housing-cooperatives.pdf) (COLA Lab)
5. Our own [worked example: four members now, two later](docs/worksheets/scenario-staggered-entry.md)

## A note on accuracy
This is educational material collected by members, **not legal, tax, or financial advice**. Links were checked in October 2026. Laws, city programs, and lender terms change. Confirm anything you rely on with our lawyer or financial professional.

## Contributing
Found a good article? See [CONTRIBUTING.md](CONTRIBUTING.md). **Never commit personal financial details.** Remember that everything under `docs/` is public on the website.

## The website
The `docs/` folder is published as a website (built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)) at **https://zombience.github.io/cooperative_info/**. It rebuilds automatically each time a change is merged into `main`.

**What's public and what's private.** The repository is private, but **the website is public**. Anything under `docs/` will be visible to anyone with the link. Anything outside `docs/` (for example the [`private/`](private/) folder) stays in the private repository and is never published.

To preview the site on your own computer: `pip install -r requirements-docs.txt`, then `mkdocs serve`, then open http://127.0.0.1:8000.
