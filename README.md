# Strahinja Milošević

Hi, I'm Stra, and this is my little personal chunk of the internet. During the day, I work as a technical writer documenting software solutions mostly, but not only, in the fintech domain.

The rest of the time, I tend to be a dude of many interests, if not talents :).

I like tinkering with manual crafts like metal, wood, stone, and leatherworking. Music is my life, so it's always in the background, whether the player is on or not.

## Where to find me

- [strahinjamilosevic.com](https://strahinjamilosevic.com): my technical writing portfolio, with skills, experience, and case studies.
- [all-maker.com](https://all-maker.com/): my blog on documentation strategy, AI-augmented workflows, leatherwork, metalwork, and other shenanigans.
- [My resume](https://all-maker.com/strahinja_milosevic_cv.pdf) as a PDF.
- [LinkedIn](https://www.linkedin.com/in/strahinjamilosevic/) for roles, projects, or a chat about documentation.

## What I do

I'm a senior technical writer and documentation engineer based in the Netherlands. I build documentation as a product: information architecture, publishing pipelines, and content governance.

- I'm the sole writer behind [Bitvavo's developer portal](https://docs.bitvavo.com), which reached 73,000+ new users in its first year.
- I rebuilt the information architecture of Adyen's in-person payments docs, which increased section traffic by about 25%.

## Case studies

Each case study follows a why, what, how, and result structure.

| Project | Result |
| --- | --- |
| [Bitvavo API docs platform](https://strahinjamilosevic.com/projects/bitvavo-api-docs-platform) | A developer portal for 8 REST, WebSocket, and FIX APIs, with 73,000+ new users in the first year. |
| [Bitvavo docs strategy](https://strahinjamilosevic.com/projects/bitvavo-docs-strategy) | Information architecture, release management, and API governance as the sole writer. |
| [Adyen in-person payments docs overhaul](https://strahinjamilosevic.com/projects/adyen-in-person-payments-overhaul) | Navigation cut from 67 items to 47, with about 25% more section traffic. |
| [Adyen Terminal API reference](https://strahinjamilosevic.com/projects/adyen-terminal-api-reference) | OpenAPI for a non-REST payment protocol. |
| [Adyen NFC integration docs](https://strahinjamilosevic.com/projects/adyen-nfc-integration-docs) | Integration docs structured around user intent. |
| [Adyen Logistics API reference](https://strahinjamilosevic.com/projects/adyen-logistics-api-reference) | Partner documentation for an API still in development. |
| [ProGlove docs platform](https://strahinjamilosevic.com/projects/proglove-docs-platform) | From a minimal MkDocs site to a multi-product portal within a year. |

## Repositories

- [strahinjamilosevic](https://github.com/strahinjamilosevic/strahinjamilosevic): the source of my portfolio, built on [Mintlify](https://mintlify.com) with docs-as-code.
- [all-maker](https://github.com/strahinjamilosevic/all-maker): the source of my blog, built on [Docusaurus](https://docusaurus.io/).

## About this repository

This repository holds the source of [strahinjamilosevic.com](https://strahinjamilosevic.com). Pages are MDX files, and `docs.json` holds the site configuration. Case studies live in `projects/`.

To preview the site locally, install the [Mintlify CLI](https://www.npmjs.com/package/mint) and run `mint dev` from the repository root. View the preview at `http://localhost:3000`. Run `mint broken-links` before pushing. Changes deploy automatically after a push to `main`.
