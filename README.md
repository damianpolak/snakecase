# snakecase
> Convert a dot/hyphen/space separated string to snake case: Foo bar → foo_bar

## Usage
```js
const snakecase = require('snakecase.js');

snakecase('   asd   ______  qweeee    zxccccc--- QWERRTY   ASDF');
// returns 'asd_qweeee_zxccccc_qwerrty_asdf'

snakecase('Lorem---------ipsum-----dolor----sit amet----consectetuer   ');
// returns 'lorem_ipsum_dolor_sit_amet_consectetuer'

snakecase('Lorem ipsum dolor sit amet consectetuer');
// returns 'lorem_ipsum_dolor_sit_amet_consectetuer'

```

## License

MIT © Damian Polak
