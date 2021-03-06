# Pts

![image](./assets/pts-gif-10.gif)   

Pts is a new typescript/es6 library that enables you to compose and visualize points in spaces.

**Get started at [ptsjs.org](https://ptsjs.org)**

This library is currently in beta. Please give it a try, [file issues](https://github.com/williamngan/pts/issues), and send feedbacks to [@williamngan](https://twitter.com/williamngan). Thank you!

---    

### Usage

**Option 1:** Download the [latest release](https://github.com/williamngan/pts/releases) and get `pts.js` or `pts.min.js` (under "dist" folder). 
```
<script type="text/javascript" src="pts.js"></script>
```
Pts is pretty lightweight. Currently at 69kb minified and 19kb gzipped.


**Option 2:** Install via `npm install pts`. Then you can choose to import some parts of Pts into your project as needed. 
```
import {CanvasSpace, Pt, Group, Line} from 'pts';
```
See this example of using Pts in a React component [here](https://github.com/williamngan/pts-react-example).

---    

### For development

Pts is written in typescript. You can clone or fork this project and build it as follows:

#### Build and test

Clone this repo and install dependencies via `npm install`.

```
npm start
npm run build
npm test
```

#### Generate documentations
```
typedoc --readme none --out docs src --name Pts
```

#### Generate typescript declaration files
```
tsc -d
dts-bundle --name pts --main dist/files/*.d.ts --out ../pts.d.ts
```

---    

### License
Apache License 2.0. See LICENSE file for details.   
Copyright © 2017 by William Ngan and contributors.

