---
title: MD034 - Bare URL used
tags:  [links, url]
alias: no-bare-urls
---

This rule is triggered whenever a URL is given that isn't surrounded by angle
brackets:

    For more information, see http://www.example.com/.

To fix this, add angle brackets around the URL:

    For more information, see <http://www.example.com/>.

Rationale: Without angle brackets, the URL isn't converted into a link in many
markdown parsers.

Note: if you do want a bare URL without it being converted into a link,
enclose it in a code block, otherwise in some markdown parsers it _will_ be
converted:

    `http://www.example.com`


