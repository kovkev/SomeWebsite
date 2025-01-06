Try doing the following:

```
rm -rf node_modules ; 
rm package-lock.json ;
rm -rf packages/SomeWebsite ;
cd packages ; 
npx create-expo-app@latest SomeWebsite ; 
cd SomeWebsite ; 
npm run web ;
```

There will be an error: 

```
TypeError: minimatch is not a function
```
