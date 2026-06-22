# proposal-model

m30ml example project for rendering a proposal

## Requirements
- npm
- gradle
- linkml

## Install dependencies

```bash
npm i
```

## Generate your proposal

This repository includes an example file named `model/proposal-model.yaml` you can use to generate your proposal.

After replacing the content with your own, use 

```bash
npm run build
```

Your generated proposal will appear in `build/proposal.adoc`.

## Edit the view

Nunjucks generates the view as an AsciiDoc file. To make changes to the view, such as section titles and the order thereof, you can edit `view/proposal.adoc.njk`. 
