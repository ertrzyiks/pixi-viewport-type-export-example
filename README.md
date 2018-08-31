# pixi-viewport-type-export-example

Example of using a type defined in pixi-viewport library.

index.ts
```
import 'pixi.js'
import * as Viewport from 'pixi-viewport'

class MyViewport extends Viewport {
  constructor(options?: Viewport.ViewportOptions) {
    super(options)
  }
}
```

## How to run
```
npm install
npm run build
```

the output:
```
index.ts:5:34 - error TS2694: Namespace 'Viewport' has no exported member 'ViewportOptions'.

5   constructor(options?: Viewport.ViewportOptions) {

```

