# JavaScript Wishlist

## Missing Cross-Browser Features

|                                                             | Chrome             | Firefox       | Safari        | Why
|-------------------------------------------------------------|--------------------|---------------|---------------|-------------
|[AVIF Image format](https://caniuse.com/avif)                |                    |               | Missing       | Sustainability / Performance - Shipping fewer bytes is a win for everyone
|[Web Components (V1)](https://caniuse.com/custom-elementsv1) |                    |               | [Incomplete](https://bugs.webkit.org/show_bug.cgi?id=182671) | Accessibility / Sustainability - Be able to progressively enhance using the least amount of bandwidth
|[HTTP/3](https://caniuse.com/http3)                          |                    |               | Experimental  | Performance
|[CSS :has()](https://caniuse.com/css-has)                    | Experimental (105) | Missing       |               | Developer Experience
|[SVG favicons](https://caniuse.com/link-icon-svg)            |                    |               | Missing       | Developer Experience - simplify code
|[ui-* fonts](https://caniuse.com/extended-system-fonts)      | Missing            | Missing       |               | Accessibility / Performance
|[inert](https://caniuse.com/mdn-api_htmlelement_inert)       |                    | Missing (104) |               | Accessibility
|[MathML](https://caniuse.com/mathml)                         | Experimental (106) |               |               | Accessibility
|[Shared Web Workers](https://caniuse.com/sharedworkers)      |                    |               | Missing (16)  | 

## Other ideas and thoughts
- [CompressionStream](https://caniuse.com/?search=CompressionStream): Support in Firefox and Safari. Include brotli and protobuf support.
- [SubtleCrypto (digest)](https://caniuse.com/mdn-api_subtlecrypto_digest): Support NIST algorithms like SHA3
- [backgroundFetch](https://caniuse.com/mdn-api_serviceworkerregistration_backgroundfetch) (Chrome Only): I see a lot of promise for this around larger uploads in making them resilient. Having people close a tab before the upload is complete is a common pain point. Would love if uploads provided a progress indicator.
- [Datalist Element](https://caniuse.com/datalist): An element that isn't used or talked about enough. Would love to see it implemented consistently across browsers, support styling.
- [Feature-Policy](https://caniuse.com/feature-policy): Add supoort for `default` like CSP to allow better future proofing as new features are allowed.
