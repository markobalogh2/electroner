<!-- Please do not edit this file. Edit the `blah` field in the `package.json` instead. If in doubt, open an issue. -->


[![electroner](http://i.imgur.com/z3xjvS3.png)](#)

# electroner

 [![Support me on Patreon][badge_patreon]][patreon] [![Buy me a book][badge_amazon]][amazon] [![PayPal][badge_paypal_donate]][paypal-donations] [![Ask me anything](https://img.shields.io/badge/ask%20me-anything-1abc9c.svg)](https://github.com/IonicaBizau/ama) [![Version](https://img.shields.io/npm/v/electroner.svg)](https://www.npmjs.com/package/electroner) [![Downloads](https://img.shields.io/npm/dt/electroner.svg)](https://www.npmjs.com/package/electroner)

> Start ElectronJS apps from Node.js.

:bulb: If you're using **`4.x.x`**, you have to manually install `electron` since this is not a dependency of `electroner` anymore, but it is used by it.

## :cloud: Installation

```sh
# Using npm
npm install --save electroner

# Using yarn
yarn add electroner
```


## :clipboard: Example



```js
const electroner = require("electroner");

// Start the Electron app
electroner(`${__dirname}/app/index.js`, {
     "enable-transparent-visuals": true
   , "disable-cpu": true
});
```



## :question: Get Help

There are few ways to get help:

 1. Please [post questions on Stack Overflow](https://stackoverflow.com/questions/ask). You can open issues with questions, as long you add a link to your Stack Overflow question.
 2. For bug reports and feature requests, open issues. :bug:

 3. For direct and quick help, you can [use Codementor](https://www.codementor.io/johnnyb). :rocket:



## :memo: Documentation


### `electroner(options, callback)`
Starts the Electron process.

#### Params

- **Object** `options`: The path to the main script or an object interpreted by [`oargv`](https://github.com/IonicaBizau/node-oargv) and optional fields:

 - `cwd` (String): An optional key representing directory where the electron
   process should be executed.
- **Function** `callback`: The callback function.

#### Return
- **Process** The Electron process.



## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :sparkling_heart: Support my projects

I open-source almost everything I can, and I try to reply everyone needing help using these projects. Obviously,
this takes time. You can integrate and use these projects in your applications *for free*! You can even change the source code and redistribute (even resell it).

However, if you get some profit from this or just want to encourage me to continue creating stuff, there are few ways you can do it:

 - Starring and sharing the projects you like :rocket:
 - [![Buy me a book][badge_amazon]][amazon]—I love books! I will remember you after years if you buy me one. :grin: :book:
 - [![PayPal][badge_paypal]][paypal-donations]—You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:
 - [![Support me on Patreon][badge_patreon]][patreon]—Set up a recurring monthly donation and you will get interesting news about what I'm doing (things that I don't share with everyone).
 - **Bitcoin**—You can send me bitcoins at this address (or scanning the code below): `1P9BRsmazNQcuyTxEqveUsnf5CERdq35V6`

    ![](https://i.imgur.com/z6OQI95.png)

Thanks! :heart:


## :dizzy: Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:


 - [`hey-you`](https://github.com/zacanger/hey-you#readme) (by Zac Anger)—hey, you
 - [`instagram-chat`](https://npmjs.com/package/instagram-chat) (by nemanjan00)—Instagram Chat Application
 - [`photon-browser`](https://github.com/IonicaBizau/photon-browser#readme)—A tiny web browser based on Photon and Electron.
 - [`simple-cam`](https://github.com/zacanger/simple-cam#readme) (by Zac Anger)—Very simple webcam viewer for desktop.

## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[badge_patreon]: http://ionicabizau.github.io/badges/patreon.svg
[badge_amazon]: http://ionicabizau.github.io/badges/amazon.svg
[badge_paypal]: http://ionicabizau.github.io/badges/paypal.svg
[badge_paypal_donate]: http://ionicabizau.github.io/badges/paypal_donate.svg
[patreon]: https://www.patreon.com/ionicabizau
[amazon]: http://amzn.eu/hRo9sIZ
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(https%3A%2F%2Fionicabizau.net)&year=2015#license-mit
[website]: https://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
