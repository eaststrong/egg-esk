# hackernews-async-ts

[Hacker News](https://news.ycombinator.com/) showcase using typescript && egg

## QuickStart

### Development

```bash
$ yarnpkg
$ yarnpkg run dev
$ open http://localhost:7001/
```

Don't tsc compile at development mode, if you had run `tsc` then you need to `npm run clean` before `npm run dev`.

### Deploy

```bash
$ yarnpkg run tsc
$ yarnpkg start
```

### Npm Scripts

- Use `yarnpkg run lint` to check code style
- Use `yarnpkg test` to run unit test
- se `yarnpkg run clean` to clean compiled js at development mode once
