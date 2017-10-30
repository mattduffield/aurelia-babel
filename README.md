# aurelia-babel
This project is used for bundling an Aurelia application using Babel and RequireJS.

## Initial Setup

```shell
npm install
```

## Update Aurelia Plugins

Execute the following command to update all the aurelia libs:

```shell
npm install aurelia-binding@latest aurelia-bootstrapper@latest aurelia-dependency-injection@latest aurelia-event-aggregator@latest aurelia-framework@latest aurelia-history@latest aurelia-history-browser@latest aurelia-loader@latest aurelia-loader-default@latest aurelia-logging@latest aurelia-logging-console@latest aurelia-metadata@latest aurelia-pal@latest aurelia-pal-browser@latest aurelia-path@latest aurelia-polyfills@latest aurelia-router@latest aurelia-route-recognizer@latest aurelia-task-queue@latest aurelia-templating@latest aurelia-templating-binding@latest aurelia-templating-router@latest aurelia-templating-resources@latest aurelia-validation@latest aurelia-fetch-client@latest aurelia-http-client@latest  --save
```

## Smoke Test

To verify things are working, execute the following commands and navigate to [http://localhost:9000](http://localhost:9000).  You should see a form with some validation wired up.

```shell
gulp export
gulp serve-export
```

## Publish

To publish, execute:

```shell
gulp export-gh-pages
```

>Note: publishing will effectively update **ALL** gists that reference this bundle. 

Here's a gist to check after publishing: https://gist.run/?id=7542e061bc940cde506b

>Note: The following link demonstrates how to get vendor and node_modules folders hosted on GitHub Pages:
https://www.bennadel.com/blog/3181-including-node-modules-and-vendors-folders-in-your-github-pages-site.htm