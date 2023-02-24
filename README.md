# hackernews-async-ts

[Hacker News](https://news.ycombinator.com/) showcase using typescript && egg

## QuickStart

### Development

```bash
$ yarn
$ yarn run dev
$ open http://localhost:7001/
```

Don't tsc compile at development mode, if you had run `tsc` then you need to `npm run clean` before `npm run dev`.

### Deploy

```bash
$ yarn run tsc
$ yarn start
```

### Npm Scripts

- Use `yarn run lint` to check code style
- Use `yarn test` to run unit test
- se `yarn run clean` to clean compiled js at development mode once
