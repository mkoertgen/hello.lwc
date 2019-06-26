# hello.lwc

A flat dive into [Lightning Web Components (lwc)](https://github.com/muenzpraeger/lwc-create-app) by [Salesforce](https://www.salesforce.com/)

## Getting started

```console
# Install lwc-create-app
npm install
# Create lwc app
npx run lwc-create-app
cd myapp
# Live reloading at http://localhost:3001
npm run watch
# Production build at http://localhost:3002
npm run build && npm run serve
```

## Remarks

- What about integrating [stencil.js](https://github.com/ionic-team/stencil)?
- Nice framework built on [Web Components](https://www.webcomponents.org/) (cool because standardized and isolated shadow-root/css) but seems like reinventing a (big) wheel (e.g. React, Angular)
- Seems a good fit when having all teams using lwc. Since web components are all about isolation (e.g. microfrontends) how to integrate cross-tech-stack, i.e.
  - SPAs build using Angular, Vue, React
  Would this be tackled by wrapping the stenciljs output of that SPAs?
