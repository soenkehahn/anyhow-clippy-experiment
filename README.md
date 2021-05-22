Running

```
$ cargo clippy
```

on this repository results in the following error:

```
error: error reading Clippy's configuration file `/home/shahn/.cargo/registry/src/github.com-1ecc6299db9ec823/anyhow-1.0.40/.clippy.toml`: unknown field `msrv`, expected one of `blacklisted-names`, `cognitive-complexity-threshold`, `cyclomatic-complexity-threshold`, `doc-valid-idents`, `too-many-arguments-threshold`, `type-complexity-threshold`, `single-char-binding-names-threshold`, `too-large-for-stack`, `enum-variant-name-threshold`, `enum-variant-size-threshold`, `verbose-bit-mask-threshold`, `literal-representation-threshold`, `trivial-copy-size-limit`, `too-many-lines-threshold`, `third-party` at line 1 column 1
```
