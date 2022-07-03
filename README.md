<div
    style='text-align:center; cursor:pointer'
> <br/>
 <br/>
 <br/>
 <br/>
    <h1 style='
        color:#FFB647; 
        font-family: sans-serif;
        font-size:3rem;
        text-align:center;
        font-weight:800'
    >
       useMagicTheme 🟣📘🍊
    </h1>
    <p style='
        color:#7920FF; '>
        Magical - Build With Magic
        </p>
 <br/>
 <br/>
</div>

useMagicTheme is a magical theme library, useMagicTheme is basically a function that accept a boolean value as a parameter and return  prebuilt object of css HEX value 

# Installation

```js
npm install usemagic-theme
```
or
```js
yarn add usemagic-theme
```

# Usage
```js
Javascript

import {useMagicTheme} from 'usemagic-theme'

const button = document.getElementById('merlinButton')
const { background, brandColor} = useMagicTheme( true )

button.style.backgroundColor = brandColor


```