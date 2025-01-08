# pnpm-symlink-bug-repo

```bash
git clone git@github.com:Silvenga/pnpm-symlink-bug-repo.git
cd pnpm-symlink-bug-repo

pnpm config set symlink false
pnpm install
```

Observe the the `parcel` package wasn't hoisted to the root of `node_modules` (where `symlink=true` does correctly hoist `parcel`).
