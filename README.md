
### Description

Replicates issue reported on [Compilation omits non-rendering code in extends #39](https://github.com/trivago/melody/issues/39).

Basically `counter/index.twig` is setting a value to a variable `trackMe` that should be the displayed value on `counter/index.twig`.

So `counter/index` *extends* `counter/count.twig`.

### Environment

- **Node version**: 8.9.0
- **Operating System**: MacOs High Sierra v10.13.6
- **melody version**: v1.0.0
