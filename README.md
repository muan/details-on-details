# Details on `<details>`

These are notes from my talk *Details on `<details>`* at Brooklyn JS on 2018/07/19. I had way more prepared than could fit in [the slides](https://docs.google.com/presentation/d/1hvnPpsJo44BTPfJx28CV95vqk_dt6na1awUbk0kmZYM/edit?usp=sharing), so here's all the details on `<details>`. I have also recorded this talk in the format of a podcast ([English](https://anchor.fm/muan/episodes/Details-on-details-ehlu8i/a-a2s4pnu) with [transcript](http://muan.co/2020/08/04/details-on-details/) | [中文](https://anchor.fm/muan/episodes/Details-on-details-ehn7mf/a-a2sc9qe)) if you like those.

This document was previously in [a gist](https://gist.github.com/muan/adf26249c0adf018aea828105a5846eb).

## Spec

- [HTML Living Standard](https://html.spec.whatwg.org/multipage/interactive-elements.html#the-details-element)
- [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details)

## Browser support

- [Can I use](http://caniuse.com/#search=details)
- [Accessible polyfill for Edge/IE – `javan/details-element-polyfill`](https://github.com/javan/details-element-polyfill)

## CSS helpers

- [Overlay utility from `primer/primer`](https://github.com/primer/css/blob/e3d988a0fde0c9421d51139cecf134996588161a/src/utilities/details.scss#L3-L19)
- [Reset utility from `primer/primer`](https://github.com/primer/css/blob/e3d988a0fde0c9421d51139cecf134996588161a/src/utilities/details.scss#L21-L28)
  - [How to style/reset `<summary>` cross browsers?](https://github.com/whatwg/html/issues/722)
  - [Spec `list-style: disclosure-closed inside`](https://html.spec.whatwg.org/#the-details-and-summary-elements)
  - [Chrome issue tracker](https://bugs.chromium.org/p/chromium/issues/detail?id=590014)
  - [Firefox issue tracker](https://bugzilla.mozilla.org/show_bug.cgi?id=1221416) (fixed)
  - [Safari issue tracker](https://bugs.webkit.org/show_bug.cgi?id=157323)

## Compatibility issues

- ~~[**Safari** bug with `<details>` when used with `rem`](https://bugs.webkit.org/show_bug.cgi?id=173876)~~ (fixed) 
- [**Safari** bug with `<summary>` and `display: flex`](https://bugs.webkit.org/show_bug.cgi?id=167111)
- ~~[**Chrome** bug where `<summary>` triangle marker color doesn't update as CSS is applied](https://bugs.chromium.org/p/chromium/issues/detail?id=882462)~~ (fixed) 

## GitHub's `<details>` dependent Custom Elements

- [`<details-dialog>`](https://github.com/github/details-dialog-element)
- [`<details-menu>`](https://github.com/github/details-menu-element)

## Spec and background discussions

- [Should interactive elements inside of `<summary>` be banned?](https://github.com/whatwg/html/issues/2272)
- [Shouldn't/Why doesn't `toggle` event bubble?](https://github.com/whatwg/html/issues/1533)
- [Should we make `<summary>` unselectable?](https://github.com/whatwg/html/issues/3191)
- [How it went from `<legend>` to `<dt/dd>` to `<summary>`](https://www.w3.org/html/wg/tracker/issues/83)
- [That time `<details>` almost got removed](https://www.w3.org/html/wg/tracker/issues/93)
- [Why semantic elements and built-in accessibility are important](https://lists.w3.org/Archives/Public/public-html/2010Apr/0049.html)
