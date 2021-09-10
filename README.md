# tfjs-issue-5584-test
A simple test trying to reproduce [#5584](https://github.com/tensorflow/tfjs/issues/5584). Build and test with `yarn test`. Uses esbuild because tfjs distributes its `.js` files as ESModules, so this repo bundles them into a file that node can run.
