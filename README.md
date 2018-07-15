# nViso Reports generator

---

## Bootstrap

### Clone the project

```
$ git clone git@bitbucket.org:nviso_insights_custom/insights_custom_ea_report.git
```

### Install dependencies

1) Install `yarn` globally:

```
npm i -g yarn
```

2) Install dependencies:

```
$ yarn
```

If you need to install or update existing packages use:

```
$ yarn add --dev <package>
```

## Development

1. `$ cp config/development.js.dist config/development.js`
2. `$ yarn start`

This will build the files and serve them on `http://localhost:8080`.

## Production

1. `$ cp config/production.dist.js config/production.js`
2. `$ NODE_ENV=production yarn build`
```
