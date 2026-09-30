# strahinjamilosevic.com

Source of my technical writing portfolio, built on [Mintlify](https://mintlify.com) and published at [strahinjamilosevic.com](https://strahinjamilosevic.com).

## Structure

- `docs.json`: site configuration, navigation, navbar, and footer.
- `index.mdx`: home page.
- `skills.mdx`, `experience.mdx`, `education.mdx`, `contact.mdx`: one page per top navigation tab.
- `projects/`: one page per case study, in a why, what, how, result format.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```
npm i -g mint
```

Run the local preview from the repository root:

```
mint dev
```

View the preview at `http://localhost:3000`. Run `mint broken-links` before pushing.

## Publishing

Changes deploy automatically after a push to `main`.
