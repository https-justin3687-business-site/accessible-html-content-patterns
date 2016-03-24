# Accessible HTML Content Patterns
A collection of the full [HTML5 Doctor Element Index](http://html5doctor.com/element-index/), minus the `<details>`, `<summary>`, `<command>`, and `<menu>` tags (which have poor browser support), as well as common markup patterns for quick reference.


## Motivation
There are countless little gotchas and quirks to remember when writing markup, even for basic components. This is an attempt to capture and centralize them.

Use this as a starting point when creating your base markup and styling for a stable, progressively enhanced foundation to your site or app, or cherry-pick as needed.


## Installation
There are a couple of ways to work with this repo:

- Clone it in its entirety: `https://github.com/ericwbailey/accessible-html-content-patterns.git`
- [Download a zipped copy](https://github.com/ericwbailey/accessible-html-content-patterns/archive/master.zip)


## Code Concerns

### Classes, IDs, and Attributes
Are suggestions only, or used for internal navigation/reference. Don't feel you need to include them if they're not relevant to your component's needs.

### Code Style
Tabs, indentation, comments, etc. are my personal preference. It's more important to be consistent than literal when using for your own project. Use [EditorConfig](http://editorconfig.org/) to help make this easier.

### Accessibility Testing
This page has been tested via the Chrome DevTools [Accessibility Audit](https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb?hl=en), as well as  [WebAIM's WAVE](http://wave.webaim.org/extension/) and [Deque System's aXe](http://www.deque.com/products/axe/#aXeExtensions) accessibility testing browser extensions, as well as [Khan Academy's tota11y bookmarklet](http://khan.github.io/tota11y/). 

Answers to specific warnings issues are available on the [repo's Wiki](https://github.com/ericwbailey/accessible-html-content-patterns/wiki).

**A note about [ARIA](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA):** ARIA is a band-aid and not a cure-all. Use semantic markup whenever possible.


## Contributing
Contributions are welcome! Submit a [Pull Request](https://github.com/ericwbailey/accessible-html-content-patterns/pulls) or [raise an Issue](https://github.com/ericwbailey/accessible-html-content-patterns/issues).


## Credits, Attribution, and Inspiration
- [Adam Morse](http://mrmrs.cc/)'s [mrmrs/html](https://github.com/mrmrs/html)
- [HTML5 Doctor](http://html5doctor.com/)
- [Alistair Duggin](http://alistairduggin.co.uk/)'s [Accessibility Fails](http://aduggin.github.io/accessibility-fails/)
- [Paul J. Adam](http://pauljadam.com/)'s [WAI-ARIA Landmarks Site Navigation Structure Demo](http://pauljadam.com/demos/landmarks.html)
- The [Falsehoods Programmers Believe](http://spaceninja.com/2015/12/08/falsehoods-programmers-believe/) series
- [GOV.UK Elements](http://govuk-elements.herokuapp.com/)
- [Baymard Institute](http://baymard.com/)'s [Touch Keyboard Types](http://baymard.com/labs/touch-keyboard-types)
- [Chrome Autofill](https://developers.google.com/web/updates/2015/06/checkout-faster-with-autofill?hl=en)
- [Nielsen Norman Group](https://www.nngroup.com/)'s [Checklist for Designing Mobile Input Fields](https://www.nngroup.com/articles/mobile-input-checklist/)


## License
[MIT License](https://raw.githubusercontent.com/ericwbailey/accessible-html-content-patterns/master/LICENSE)
