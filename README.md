# prettier-config
A simple Prettier configuration used at Chaine

## Prerequisite
Prettier must be isntalled as a dev dependency
```sh
npm install --save-dev --save-exact prettier
```

## Usage

Install the package using `npm` (or `yarn`)

```sh
npm install --save-dev @chaine/prettier-config
```

Add the `prettier` key to your `package.json`

```diff
diff --git a/package.json b/package.json
index 2ecef3d..260838f 100644
--- a/package.json
+++ b/package.json
@@ -5,6 +5,7 @@
   "keywords": [
     "prettier"
   ],
+  "prettier": "@chaine/prettier-config",
   "license": "MIT",
   "author": "Chaine Inc.",
   "main": "index.js"
 ```
 
 [Check out the `prettier` documentation for more info on sharing configurations](https://prettier.io/docs/en/configuration.html#sharing-configurations).
