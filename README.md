# erd (archived)

This fork only existed to publish an `erd` container image used by [Kroki](https://github.com/yuzutech/kroki).
It is no longer used.

The `erd` binary is now built from the upstream release sources, [BurntSushi/erd](https://github.com/BurntSushi/erd), in [`tools/erd`](https://github.com/yuzutech/kroki/tree/main/tools/erd) of the Kroki repository, and published as the `ghcr.io/yuzutech/kroki-builder-erd` image ([yuzutech/kroki#2187](https://github.com/yuzutech/kroki/pull/2187)).
New versions follow the upstream releases.
