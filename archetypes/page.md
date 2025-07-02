---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: '{{ .Date }}'
tags: ["first"]
author: "Me"
showToc: true
TocOpen: true
draft: true
hidemeta: true
comments: false
description: "Desc Text."
canonicalURL: "https://canonical.url/to/page"
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
---