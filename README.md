# turborepo-build-storybook-bug

Running build-storybook from ui package works fine.

```bash
yarn --cwd packages/ui build-storybook
```

Running build-storybook using turbo gets stuck forever.

```bash
yarn build-storybook
```
