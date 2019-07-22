# AMP Hacks

[AMP](https://amp.dev/) (Accelerated Mobile Pages) is good for a number of things, such as news sites and other content heavy sites from major 
parties. I tried implementing an AMP site for my personal / web development blog and, while it works and I'm generally happy, had need of some 
hackery to make it work. This repo provides that hackery in a dedicated location.

Note: I don't recommend a personal blog implementing AMP. Mine was a trial and I learned a lot about AMP and that it's not what I need.

## Installation

None. There's no build process, dev tooling, or otherwise. Static HTML drives 

## Usage

Point to the live URL of the respective page and embed away with `amp-iframe`.

## What's Included

Check the source of the files. If you're here and interested, it should read pretty cleanly.

### 1. `disqus_embed.html`

This follows [the example given from disqus](https://github.com/disqus/disqus-install-examples/tree/master/google-amp).

### 2. `gist_embed.html`

Similarly for GitHub gist embeds, including availability of single file selection. This was superseded in my implementation in my blog, so it's 
included more for historical reference.

## History

AMP does a few things well, and a few things less-so. This brings my hackery involving `amp-iframe` embeds into a single, dedicated location.

## License

MIT
