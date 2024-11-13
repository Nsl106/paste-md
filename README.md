Fork of https://github.com/topaz/paste to allow for markdown rendering in the ui.


This is a no-datastore, client-side paste service. It turns text into [LZMA](https://en.wikipedia.org/wiki/Lempel%E2%80%93Ziv%E2%80%93Markov_chain_algorithm)-compressed, [Base64](https://en.wikipedia.org/wiki/Base64)-encoded URLs.

Because the entire paste is inside the URL, there's no risk of losing your data because a 3rd-party service vanished or deleted old pastes. If you have the URL, you have the pasted data.

Uses [LZMA-JS](https://github.com/LZMA-JS/LZMA-JS), [Marked](https://github.com/markedjs/marked), and [Github-Markdown-CSS](https://github.com/sindresorhus/github-markdown-css/tree/main).
