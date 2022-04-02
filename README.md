# scala-cli-lab
scala cli lab


## Setup Build Server Protocol

requirements.
* bazel
* coursier<https://get-coursier.io/docs/cli-installation>

1. [Build Server Protocol](https://build-server-protocol.github.io)

``sh
cs launch org.jetbrains.bsp:bazel-bsp:1.1.1 -M org.jetbrains.bsp.bazel.install.Install
``

2. .bsp & .bazelbsp add .gitignore

