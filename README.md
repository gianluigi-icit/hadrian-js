# Hadrian

[![build status](https://img.shields.io/travis/interconnectit/hadrian-js.svg?style=flat-square)](https://travis-ci.org/interconnectit/hadrian-js)
[![code style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square)](http://standardjs.com)

This is where your description should go. Try and limit it to a paragraph or two.

## Install

Via NPM

``` bash
$ npm install --save @interconnectit/hadrian
```

Via CDN

``` html
<script src="//cdn.jsdelivr.net/npm/@interconnectit/hadrian/dist/hadrian.min.js"></script>
```

## Usage

``` js
Hadrian.config
    .site('your-site-uuid')
    .payload({
        post_id: 1,
        post_title: 'Lorem ipsum dolor sit amet',
        ...
    })

Hadrian.requirements
    .on({user: {subscription: 'gold'}}, function () {
        $('.popup_subscription_gold').show()
    })
    .on({user: {subscription: 'silver'}}, function () {
        $('.popup_subscription_silver').show()
    })
    ...
```

## Testing

``` bash
$ npm run test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email support@interconnectit.con instead of using the issue tracker.

## Credits

- [interconnect/it](https://interconnectit.com)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.