# nest-tslint

This is a NPM package with some custom rules for your tslint configuration.
The focus of this configuration is on [nest JS](https://nestjs.com/) projects and extend the [tslint:recomended](https://github.com/palantir/tslint/blob/master/src/configs/recommended.ts) rules.

## How Install it

Install like a dev dependency the package via npm or yarn:

NPM command

```bash
npm i @coara/nest-tslint -D
```

or Yarn conmand

```bash
yarn add @coara/nest-tslint -D
```

### Configuration

Then you should extend your current `tslint.json` with this new configuration:

```json
{
  "extends": "@coara/nest-tslint/tslint-config",
  "linterOptions": {
    "exclude": ["**/some_folder/**"]
  },
  "rules": {
      ...
  }
}
```

---

Package powered by [coara TM](https://coara.co)
