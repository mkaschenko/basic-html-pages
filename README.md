## Contents

1. [A basic HTML page](#a-basic-html-page)
2. [The HTML meta element](#the-html-meta-element)
3. [The HTML script element](#the-html-script-element)
4. [The HTML style element](#the-html-style-element)
5. [The Open Graph protocol](#the-open-graph-protocol)

## A basic HTML page

See the specification at [https://html.spec.whatwg.org](https://html.spec.whatwg.org)

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>A basic HTML page</title>
  </head>
  <body>
    <h1>A basic HTML page</h1>
  </body>
</html>
```

## The HTML meta element

See the specification at [https://html.spec.whatwg.org/#the-meta-element](https://html.spec.whatwg.org/#the-meta-element)

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="x-ua-compatible" content="IE=edge">
    <meta name="author" content="">
    <meta name="description" content="">
    <meta name="keywords" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1">
  </head>
</html>
```

## The HTML script element

See the specification at [https://html.spec.whatwg.org/#the-script-element](https://html.spec.whatwg.org/#the-script-element)

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <script>
      window.alert("The HTML script element");
    </script>
  </head>
</html>
```

## The HTML style element

See the specification at [https://html.spec.whatwg.org/#the-style-element](https://html.spec.whatwg.org/#the-style-element)

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <style>
      h1 {
        font-style: italic;
      }
    </style>
  </head>
  <body>
    <h1>The HTML style element</h1>
  </body>
</html>
```

## The Open Graph protocol

See the specification at [https://ogp.me](https://ogp.me)

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta property="og:title" content="The Open Graph protocol">
    <meta property="og:type" content="website">
    <meta property="og:image" content="">
    <meta property="og:url" content="">
    <meta property="og:description" content="">
  </head>
</html>
```
