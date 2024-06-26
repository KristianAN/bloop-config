# bloop-config

This project is a standalone [Bloop
Configuration](https://scalacenter.github.io/bloop/docs/configuration-format)
library meant to help reading and writing configuration files.

## Getting Started

- To get started with `bloop-config` head to the docs [here](https://scalacenter.github.io/bloop/docs/configuration-format).
- If you're looking for the Bloop codebase, look [here](https://github.com/scalacenter/bloop)
- If you're looking to contribute, check our [CONTRIBUTING.md](./CONTRIBUTING.md)
- If you're unfamiliar with Bloop and want to learn more, please check out our full [site](https://scalacenter.github.io/bloop/)

## Binary compatibility

bloop-config uses [unroll](https://github.com/com-lihaoyi/unroll/tree/main) to maintain binary compatibility. 
If you add an option that breaks binary compatibility import scala.annotation.unroll and annotate the field with @unroll.
Give the field a reasonable default value.
