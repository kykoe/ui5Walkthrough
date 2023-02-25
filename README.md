# SAPUI5 Demo App

## Introduction

Following the [tutorial](https://sapui5.hana.ondemand.com/#/topic/851bde42e4e1410c96abbe402fa9128c) in the official documentation leads to the error message.

Also the [Getting Started](https://sap.github.io/ui5-tooling/pages/GettingStarted/) page does not resolve that.

```conf
⚠️  Process Failed With Error

Error Message:
Could not find required manifest.json for project webapp: ENOENT: no such file or directory, open '/home/user/projects/webapp/manifest.json'
```

Thankfully, there is a [Github issue](https://github.com/SAP/openui5/issues/3292), that deals with this issue.

## Commands

- Installing dependencies: `npm install`
- Start developement web server on port 8080: `ui5 serve`
- open http://127.0.0.1:8080/index.html
