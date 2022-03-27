# monorepo
Webapps, npm packages managed by monorepo  

All in typescript

manage packages by yarn/lerna  

build webapps by webpack for production, vite for development

build npm packages by rollup

webapps base on react, typescript

micro frontend powed by webpack5 module federation

# details
## yarn workspace config
package.json
```
"workspaces": [
  "packages/*"
]
```

add all packages dependencies at project root
```
yarn
```

# todos
changelog
source code dependency Or dist dependency?
