# Version Control Commands:
From branch main (or whatever branch you want to update from):
```
git remote add upstream https://github.com/DS219/f22-projects.git
git fetch upstream
```

Bring changes into your local repository

```
 git rebase upstream/main
```

Push changes to your repo
```
console git push origin main
```

 From Team-1/typescript-nodejs/
``` 
npm init -y
npm install
npx ts-node index.ts
```
open any browser and input localhost:3000
```
ctrl c to interrupt program
```
rm -rf node_modules if changes need to be pushed to git
