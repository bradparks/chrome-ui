# Chrome UI [![Build Status](https://travis-ci.org/pd4d10/chrome-ui.svg?branch=master)](https://travis-ci.org/pd4d10/chrome-ui)

Chrome UI built with web stack.

Demo: https://pd4d10.github.io/chrome-ui/

## Trouble Shooting

### Q: When I open Google, Twitter or GitHub, it shows blank page instead of webpage content

Because these sites have HTTP Header Field `X-Frame-Options` set. See http://stackoverflow.com/a/19843216.

Try `www.bing.com` or `en.wikipedia.org` instead.

### Q: It is messed up in my browser

It is tested only on Chrome for now.

If you find a bug or style mess, please [submit an issue](https://github.com/pd4d10/chrome-ui/issues/new). Thanks!

## Todos

* Add tests
* Incognito mode theme

## Contribute

```sh
git clone https://github.com/pd4d10/chrome-ui.git
yarn
yarn start

# You can also use npm instead:
npm install
npm start
```

## License

MIT
