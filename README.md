* HTML/CSS Checkbox Toggle, No JavaScript

A CSS only toggle I created while I working to avoid the use of an additional sprite or javascript.
The toggle is built around a visually hidden radio or checked box input field and a label.

The toggle is powered by CSS :checked pseudo selectors and + adjacent sibling selectors.

The adjacent CSS select was used for to bring older versions of IE (with Modernizr) and native Gingerbread and earlier android browsers.  Additionally, the visually hidden input field must be in teh document flow for IE or else the, it appears, that the :checked pseudo selector is ignored (this could be a Modernizr issue?).