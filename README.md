# chocolatey-packages #

a repo to hold artefacts to publish and support chocolatey packages

typically things that need to be served from a CDN but where we have the artefacts in a private repo

## CDN links ##

Because github has asked that raw links should not be served directly as a resources, there are a number of free CDN services which do allow serving of resources, for example [statically](https://statically.io/convert/)

for instance

```
https://github.com/derekwilson/chocolatey-packages/blob/master/worldolio/wologo.png
```

becomes

```
https://cdn.statically.io/gh/derekwilson/chocolatey-packages/eb98ccc1/worldolio/wologo.png
```