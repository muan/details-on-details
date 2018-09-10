# Details on `<details>`

These are notes from my talk *Details on `<details>`* at Brooklyn JS on 2018/07/19. I had way more prepared than could fit in [the slides](https://docs.google.com/presentation/d/1hvnPpsJo44BTPfJx28CV95vqk_dt6na1awUbk0kmZYM/edit?usp=sharing), so here's all the details on `<details>`. ❤️ (Previously in [a gist](https://gist.github.com/muan/adf26249c0adf018aea828105a5846eb)).

## Spec

- [HTML Living Standard](https://html.spec.whatwg.org/multipage/interactive-elements.html#the-details-element)
- [HTML 5.1](https://www.w3.org/TR/html51/interactive-elements.html#the-details-element)
- [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details)

## Pratical things

- [Can I use](http://caniuse.com/#search=details)
- [Accessible polyfill for Edge/IE – `javan/details-element-polyfill`](https://github.com/javan/details-element-polyfill)
- [Overlay utility from `primer/primer`](https://github.com/primer/primer/blob/master/modules/primer-utilities/lib/details.scss)
- [Reset utility from `primer/primer`](https://github.com/primer/primer/blob/master/modules/primer-buttons/lib/button.scss#L206-L213)

## Things that are nice to know

- [**Edge** `<details>` feature tracking](https://wpdev.uservoice.com/forums/257854-microsoft-edge-developer/suggestions/6261266-details-summary-elements?page=2&per_page=20) (please :star:) 
- [**Safari** bug with `<details>` when used with `rem`](https://bugs.webkit.org/show_bug.cgi?id=173876) (please subscribe and bug them) 
- [**Chrome** bug where `<summary>` triangle marker color doesn't update as CSS is applied](https://bugs.chromium.org/p/chromium/issues/detail?id=882462) (please :star:) 
- [How to style/reset `<summary>` cross browsers?](https://github.com/whatwg/html/issues/722)
- [Should interactive elements inside of `<summary>` be banned?](https://github.com/whatwg/html/issues/2272)
- [Shouldn't/Why doesn't `toggle` event bubble?](https://github.com/whatwg/html/issues/1533)
- [Should we make `<summary>` unselectable?](https://github.com/whatwg/html/issues/3191)

## GitHub's `<details>` dependent Custom Elements

- [`<details-dialog>`](https://github.com/github/details-dialog-element)
- [`<details-menu>`](https://github.com/github/details-menu-element)

## Fun facts

- [How it went from `<legend>` to `<dt/dd>` to `<summary>`](https://www.w3.org/html/wg/tracker/issues/83)
- [That time `<details>` almost(?) got removed](https://www.w3.org/html/wg/tracker/issues/93)
- [Why semantic elements and built in accessibility are important](https://lists.w3.org/Archives/Public/public-html/2010Apr/0049.html)
