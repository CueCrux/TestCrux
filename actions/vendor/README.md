## Vendored GitHub Actions

These copies allow `.github/workflows/*.yml` to run with `act` without downloading published actions.
Each folder represents the upstream repository at the exact commit listed below. Refresh a vendor
by removing its directory, cloning the upstream repo at the tagged ref, deleting the inner `.git`,
and updating this table.

| Local Path | Upstream | Ref | Commit |
| --- | --- | --- | --- |
| `checkout` | `actions/checkout` | `v4` | `08eba0b27e820071cde6df949e0beb9ba4906955` |
| `setup-qemu` | `docker/setup-qemu-action` | `v3` | `c7c53464625b32c7a7e944ae62b3e17d2b600130` |
| `setup-buildx` | `docker/setup-buildx-action` | `v3` | `e468171a9de216ec08956ac3ada2f0791b6bd435` |
| `login` | `docker/login-action` | `v3` | `5e57cd118135c172c3672efd75eb46360885c0ef` |
| `build-push` | `docker/build-push-action` | `v6` | `263435318d21b8e681c14492fe198d362a7d2c83` |
| `sbom` | `anchore/sbom-action` | `v0` | `8e94d75ddd33f69f691467e42275782e4bfefe84` |
| `cosign-installer` | `sigstore/cosign-installer` | `v3` | `398d4b0eeef1380460a10c8013a76f728fb906ac` |
| `upload-artifact` | `actions/upload-artifact` | `v4` | `ea165f8d65b6e75b540449e92b4886f43607fa02` |
| `setup-node` | `actions/setup-node` | `v4` | `49933ea5288caeca8642d1e84afbd3f7d6820020` |
| `setup-kubectl` | `Azure/setup-kubectl` | `v4` | `776406bce94f63e41d621b960d78ee25c8b76ede` |
| `pnpm-setup-v4` | `pnpm/action-setup` | `v4` | `41ff72655975bd51cab0327fa583b6e92b6d3061` |
| `pnpm-setup-v3` | `pnpm/action-setup` | `v3` | `a3252b78c470c02df07e9d59298aecedc3ccdd6d` |

