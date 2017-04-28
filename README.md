# Demo: dev-expression issue

It seems like `babel-plugin-dev-expression` doesn't work with React Native (at least on v0.43).
Issue link: https://github.com/4Catalyzer/babel-plugin-dev-expression/issues/4.

## Usage

```console
yarn install
react-native run-android # or run-ios
```

Make sure if you tweak anything in `.babelrc` you run `npm start -- --reset-cache` to pick up the changes.
