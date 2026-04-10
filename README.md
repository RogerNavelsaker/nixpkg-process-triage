# nixpkg-process-triage

Thin Nix packaging repo for [`Dicklesworthstone/process_triage`](https://github.com/Dicklesworthstone/process_triage).

## Upstream

- Repo: `Dicklesworthstone/process_triage`
- Vendored source: [`upstream/`](/home/rona/Repositories/@nixpkgs/nixpkg-process-triage/upstream)
- Upstream CLI crate version: `2.0.5`
- Vendored commit: `be277c09d7ea7e3f59f1924d549b52a81c400264`

## Usage

```bash
nix build
nix run
```

The upstream workspace builds `pt-core`; this package exposes it as the canonical `pt` command.
