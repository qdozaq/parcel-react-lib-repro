# parcel-react-lib-repro

Reproduction repo for the following error:
```bash
🚨 Build failed.

@parcel/packager-js: Asset was skipped or not found.

  AssertionError [ERR_ASSERTION]: Asset was skipped or not found.
  at ScopeHoistingPackager.getSymbolResolution (/Users/paul.mendoza/git/parcel-react-lib/node_modules/@parcel/packager-js/lib/ScopeHoistingPackager.js:716:29)
  at /Users/paul.mendoza/git/parcel-react-lib/node_modules/@parcel/packager-js/lib/ScopeHoistingPackager.js:820:31
  at Array.map (<anonymous>)
  at ScopeHoistingPackager.buildAssetPrelude (/Users/paul.mendoza/git/parcel-react-lib/node_modules/@parcel/packager-js/lib/ScopeHoistingPackager.js:819:37)
  at ScopeHoistingPackager.buildAsset (/Users/paul.mendoza/git/parcel-react-lib/node_modules/@parcel/packager-js/lib/ScopeHoistingPackager.js:382:48)
  at ScopeHoistingPackager.visitAsset (/Users/paul.mendoza/git/parcel-react-lib/node_modules/@parcel/packager-js/lib/ScopeHoistingPackager.js:341:17)
  at /Users/paul.mendoza/git/parcel-react-lib/node_modules/@parcel/packager-js/lib/ScopeHoistingPackager.js:440:56
  at String.replace (<anonymous>)
  at ScopeHoistingPackager.buildAsset (/Users/paul.mendoza/git/parcel-react-lib/node_modules/@parcel/packager-js/lib/ScopeHoistingPackager.js:404:19)
  at ScopeHoistingPackager.visitAsset (/Users/paul.mendoza/git/parcel-react-lib/node_modules/@parcel/packager-js/lib/ScopeHoistingPackager.js:341:17)
```

### How to test
```bash
yarn install
yarn watch
```
