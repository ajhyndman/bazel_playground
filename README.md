# bazel_playground

A playground for experimenting with Bazel tooling

## Getting started

This was bootstrapped with [@bazel/create](https://github.com/bazelbuild/rules_nodejs#quickstart).

To install locally, just run `npm install` in this repository's root folder. 
That will install a local copy of [bazelisk](https://github.com/bazelbuild/bazelisk), 
a Bazel version manager and launcher.

Run commands with Bazel

```
$ npm run bazel -- <your target and args here>
```

To try a different version of Bazel:

Edit `.bazelversion` and replace the default version with any valid Bazel 
version number.
