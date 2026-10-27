# typeopt

Experimental Rust CLI for conservative TypeScript optimization before bundling and type-independent JavaScript optimization after bundling.

See [the CLI guide](crates/typeopt/README.md) for usage, safety boundaries, Vite integration and benchmark procedures. The [project index](docs/project-typeopt.md) and [foundation contract](docs/crates-typeopt-foundation.md) define development requirements.

## Development

Use the pinned Rust toolchain, Node.js 24 and pnpm 10.26.2.

```sh
pnpm install --frozen-lockfile
cargo test --locked
cargo build --locked
pnpm --dir crates/typeopt/examples/vite install --ignore-workspace --frozen-lockfile
pnpm --dir crates/typeopt/examples/vite test
pnpm test
pnpm format:check
```

## License

Repository-owned source uses [Apache-2.0](LICENSE). Compiler licenses and notices are retained in [crates/typeopt/licenses](crates/typeopt/licenses).
