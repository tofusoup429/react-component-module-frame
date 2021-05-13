# react-component-module-frame
## What is this project about?
#### This project has a frame with typescript set-up for publishing your own react-component to NPM. By replacing files inside src/ and yarn build && yarn publish, you can easily publish your own components. 

#### The files to be published will be transpiled to lib/esm by "yarn build" 
#### To download this project  
```
git clone git@github.com:tofusoup429/react-component-module-frame.git
```
#### To build
```
yarn build
```  

### import this module from other project. 
```
import {RotatingText} from "@tofusoup429/react-component-module-frame/lib/esm/RotatingText"
```
