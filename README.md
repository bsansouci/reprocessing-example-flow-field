Reprocessing Example - Perlin Noise Flow Field
---

## What is this?

This is the [Coding Challenge #24: Perlin Noise Flow Field](https://www.youtube.com/watch?v=BjoM9oKOAKY) written in Reasonml + Reprocessing.

## Controls

* *G*: Toggle grid view on and off
* *C*: Toggle drawing with colors

## How to
```
git clone https://github.com/ekosz/reprocessing-example-flow-field.git
```

### Install

```
npm install
```

### Build
```
npm run build
```

### Start
```
npm start
```

To build to JS run `npm run build:web` and then run a static server, like `python -m SimpleHTTPServer` and go to `localhost:8000`. If you're using safari you can simply open the `index.html` and tick `Develop > Disable Cross-Origin Restrictions`.

To build to native run `npm run build:native` and run `npm run start:native`

The build system used is [bsb-native](https://github.com/bsansouci/bsb-native).
