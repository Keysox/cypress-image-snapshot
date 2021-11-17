# cypress-image-snapshot

## 4.0.2

### Patch Changes

- [`5c760fe`](https://github.com/Keysox/cypress-image-snapshot/commit/5c760fe0bd09a56a4c0bcc86bf64521fb3ca4478) [#1](https://github.com/Keysox/cypress-image-snapshot/pull/1) Thanks [@Keysox](https://github.com/Keysox)! - Expand cypress peerDependency range

## 4.0.1

### Patch Changes

- [`17f7927`](https://github.com/jaredpalmer/cypress-image-snapshot/commit/17f7927384bfdbd6cbb65d344c8337d32926b691) Thanks [@jaredpalmer](https://github.com/jaredpalmer)! - When using native retries that come in Cypress v5+ real image failures are marked as passed on the retries because cypress names the snapshots as 'filename (attempt X).png (and there is no configuration option to change this). The fix just removes the ' (attempt X)' suffix from the filename.
