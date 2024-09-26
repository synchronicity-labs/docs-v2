# sync dev docs

welcome to sync's dev docs. we use mintlify to manage and serve our docs.

## getting started

to work on these docs locally:

1. install the mintlify cli:

```
npm i -g mintlify
```

2. run the dev server:

```
mintlify dev
```

## editing docs

- all docs are written in markdown
- the `mint.json` file controls the site structure and config
- make changes and preview them locally using the dev server

## publishing

we use github actions to automatically deploy changes. just push to the main/topic-branch, and your updates will go live/preview.

## need help?

if you run into issues:

- make sure you're in the right folder (where `mint.json` is).
- try running `mintlify install` to refresh dependencies.
- ping @assimovt or @nozma-knows to get help.
