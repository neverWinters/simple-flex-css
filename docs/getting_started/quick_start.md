## Quick Start

Simple Flex CSS is based in the "Mobile first" principle, wich consist in carrying out a layout development from mobile device screens to desktop device screens. Thinking in this, the ```min-width``` css property is used for the break points in the code.

## Import

If you want to import the files locally:

```
    <link rel="stylesheet" href="css/normalize.css"/>
    <link rel="stylesheet" href="css/style.css"/>
    <link rel="stylesheet" href="css/style-md.css" media="screen and (min-width:768px)"/>
    <link rel="stylesheet" href="css/style-lg.css" media="screen and (min-width:1024px)"/>
```

If you want to import from CDN:

```
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/neverWinters/simple-flex-css/css/normalize.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/neverWinters/simple-flex-css/css/style.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/neverWinters/simple-flex-css/css/style-md.css" media="screen and (min-width:768px)"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/neverWinters/simple-flex-css/css/style-lg.css" media="screen and (min-width:1024px)"/>
```

## Implementation

Is strongly recommended the semantic HTML use to maintain the relation between the classes and the elements in the page.\

```
    <body>
        <header>
            <nav class="navbar">
                ...
            </nav>
        </header>
        <main class="container">
            ...
        </main>
        <footer class="footer">
            ...
        </footer>
    </body>
```
