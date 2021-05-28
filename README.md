# Kanoe template

Simple basic project using:

- [Parcel](https://github.com/parcel-bundler/parcel)
- [PUG](https://github.com/pugjs/pug)
- [Stylus](https://github.com/stylus/stylus)

## Installation

```bash
npm install
```

## Usage

```bash
# development server
npm run start
# build to production
npm run build
```

## Code formatters

### Watch mode

```bash
# all files
npm run  fix:watch:all
```

### MD, JS, CSS, JSON, PUG

```bash
# watch mode
npm run prettier:fix:watch
# all files
npm run prettier:fix
```

### STYL

```bash
# watch mode
npm run stylus:fix:watch
# all files
npm run stylus:fix:all
# one file
npm run stylus:fix:file --file=./file.styl
```

## Lint

### Styles

```bash
# all files
npm run stylus:lint
# one file
npm run stylus:lint --file=./file.styl
```
