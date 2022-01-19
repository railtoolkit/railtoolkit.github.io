---
title: "tikz-trackschematic"
description: "This TikZ library is a toolbox of symbols geared primarily towards creating track schematic for either research or educational purposes. It provides a TikZ frontend to some of the symbols which may be needed to describe situations and layouts in railway operation."
repository: "https://github.com/railtoolkit/tikz-trackschematic"
---

# tikz-trackschematic

{{ $resp := getJSON "https://api.github.com/repos/railtoolkit/tikz-trackschematic/contents/readme"  }}

{{ $resp.content | base64Decode | markdownify }}
