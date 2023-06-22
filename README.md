# iFrame Spike

Notion card - https://www.notion.so/beyonk/Apple-Google-pay-spike-4695c4dec7644f42af275f107950d5f4?pvs=4

Three separate projects in one to demostrate escaping an iframe using `target='_top'`
* Project #1 - client-site
* Project #2 - iframe
* Project #3 - checkout

## Installing

Add the following domains to your hosts file

```sh
127.0.0.1 foo.bar.baz
127.0.0.1 waldo.fred.plugh
127.0.0.1 qux.grault.garply
```

To demo run `npm i` then `npm run devStart` in each project
Go to http://foo.bar.baz:3000/