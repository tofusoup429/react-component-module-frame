# react-component-module-frame
## What is this project about?
#### This template was built to make publishing react-components easy. All the basic settings such as tsconfig.json and package.json are done. It is up to you to modify the setting for your own taste.

-----------------------------------------------------------------------------------------------------------------------

#### To download this project  
```
git clone git@github.com:tofusoup429/react-component-module-frame.git
```
-----------------------------------------------------------------------------------------------------------------------
#### Fill in your own component inside /src and export it from index.ts.
-----------------------------------------------------------------------------------------------------------------------

#### Once your components are ready to be published, enter your own package name in package.json. And build. 
 
#### the build command transpiles the files in the src folder into dist with ts declaration files such as exampleModule.d.ts.
#### To build
```
yarn build
``` 
-----------------------------------------------------------------------------------------------------------------------
#### To publish
```
yarn publish
```
-----------------------------------------------------------------------------------------------------------------------

#### to import this module from other project. 
```
import {RotatingText} from "@tofusoup429/react-component-module-frame"
```


