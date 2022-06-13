# svelte-color-progressbar

### Installation

Install using NPM

```sh
npm i svelte-color-progressbar
```
### Import package to your component

```js
  import Progress from 'svelte-color-progressbar'
```
### Use

 Put this in your html 
 
```html
  <Progress/>
```

### Options

svelte-color-progressbar support for these options

| Option | Type | Default |
| ------ | ------ |  ------ |
| progress | number | 50 |
| color | string | Blue |

 Example:
 
```html
   <Progress progress={50} color={'blue'}/>
```