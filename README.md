# maverick

decent hugo theme

# example configure
```toml
newContentEditor = "vim"
languageCode = "en-us"
baseURL = ""
title = "Zyprex's Blog"
theme = "Maverick"
paginate = 50
summaryLength = 200
hasCJKLanguage = true
enableEmoji = true

[params]
    author = "zyprex"
    subtitle = "Maverick"
    description = "Zyprex's Awesome Hugo Site"
    avatar = "/img/git_face.png"
    favicon = "/img/git_face.png"

[markup.goldmark.renderer]
    unsafe = true

[markup.tableOfContents]
    startLevel = 1
    endLevel = 6
    ordered = false

[markup.highlight]
    anchorLineNos = false
    codeFences = true
    guessSyntax = false
    hl_Lines = ""
    lineAnchors = ""
    lineNoStart = 1
    lineNos = true
    lineNumbersInTable = true
    noClasses = true
    style = "monokai"
    tabWidth = 2
```

# FrontMatter
```yaml
# use katex
math: true
# use mermaid
mermaid: true
```
