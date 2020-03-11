# incca-react-pdf
convert html to pdf
This is a copy package of the react-html2pdf forked to work in a private project of Incca Sistemas

## Install package
```bash
$ npm i incca-react-pdf
```

## Usage
```js
//import
import { Preview, print } from 'incca-react-pdf';

//render
<Preview id={'jsx-template'} >
    <p>adsf</p>
</Preview>
<button onClick={()=>print('a', 'jsx-template')}> print</button>
```

## License

[MIT License](http://opensource.org/licenses/mit-license.html). © 2018 San Pyae Lin