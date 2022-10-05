# JavaScript Wishlist

## Missing Cross-Browser Features

|                                                             | [Chrome](https://bugs.chromium.org/p/chromium/issues/list) | [Firefox](https://bugzilla.mozilla.org/) | [Safari](https://bugs.webkit.org/) | Why
|-------------------------------------------------------------|--------------------|---------------|---------------|-------------
|[Web Components (V1)](https://caniuse.com/custom-elementsv1) |                    |               | [Incomplete](https://bugs.webkit.org/show_bug.cgi?id=182671) | Accessibility / Sustainability - Be able to progressively enhance using the least amount of bandwidth
|[HTTP/3](https://caniuse.com/http3)                          |                    |               | Experimental  | Performance
|[CSS :has()](https://caniuse.com/css-has)                    | Experimental (105) | [Missing](https://bugzilla.mozilla.org/show_bug.cgi?id=418039) |               | Developer Experience
| [CSS Nesting](https://drafts.csswg.org/css-nesting/) | [Missing](https://groups.google.com/a/chromium.org/g/blink-dev/c/-GxQ0MIcons/m/dTi5stNrBAAJ?pli=1) | [Missing](https://github.com/mozilla/standards-positions/issues/695) | [Missing](https://github.com/WebKit/standards-positions/issues/69) | Sustainability
|[SVG favicons](https://caniuse.com/link-icon-svg)            |                    |               | Missing       | Developer Experience - simplify code
|[ui-serif, ui-sans-serif, ui-monospace fonts](https://caniuse.com/extended-system-fonts) | [Missing](https://bugs.chromium.org/p/chromium/issues/detail?id=1240117) | [Missing](https://bugzilla.mozilla.org/show_bug.cgi?id=1598879) |               | Accessibility / Performance
|[AVIF Image format](https://caniuse.com/avif)                |                    |               | Missing(16)   | Sustainability / Performance - Shipping fewer bytes is a win for everyone
|[inert](https://caniuse.com/mdn-api_htmlelement_inert)       |                    | Missing (104) |               | Accessibility
|[MathML](https://caniuse.com/mathml)                         | Experimental (106) |               |               | Accessibility
|[Shared Web Workers](https://caniuse.com/sharedworkers)      |                    |               | Missing (16)  | 

## Other ideas and thoughts
- [CompressionStream](https://caniuse.com/?search=CompressionStream): Support in Firefox and Safari. Include brotli and protobuf support.
- [SubtleCrypto (digest)](https://caniuse.com/mdn-api_subtlecrypto_digest): Support NIST algorithms like SHA3 and [streams](https://github.com/w3c/webcrypto/issues/73)
- [backgroundFetch](https://caniuse.com/mdn-api_serviceworkerregistration_backgroundfetch) (Chrome Only): I see a lot of promise for this around larger uploads in making them resilient. Having people close a tab before the upload is complete is a common pain point. Would love if uploads provided a progress indicator.
- [Datalist Element](https://caniuse.com/datalist): An element that isn't used or talked about enough. Would love to see it implemented consistently across browsers, support styling.
- [Feature-Policy](https://caniuse.com/feature-policy): Add supoort for `default` like CSP to allow better future proofing as new features are allowed. [off-by-default](https://paul.kinlan.me/the-off-by-default-web/)

## References
- [Interop](https://github.com/web-platform-tests/interop/issues)
