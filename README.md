<h1>53% of mobile website visitors will leave if a webpage doesn’t load within three seconds

Here are a few tips to reduce load times.</h1>

# 6 tips to reduce load times of your webpages.
## 1: Preload CSS
At the top of the head tag, keep a link referring to the CSS file with rel attribute as `preload`.

Then have a link with rel as `stylesheet` to apply the CSS.

This makes the CSS file available as soon as its required for the rendering of the page later on.[ read more ](https://web.dev/preload-critical-assets/)
![](./images/preload.jpg)

## 2: Preconnect to resources

It tells the browser to create a connection to the link in advance and makes it aware that you might fetch images or data from this URL.
![](./images/preconnect.jpg)

## 3: Lazy load the media

The loading attribute specifies whether a browser should load an image immediately or to defer loading of off-screen images until the user scrolls near them.
![](./images/lazyload.jpg)

## 4: Use a CDN to load images faster

Content Delivery Networks cache the media in their world-wide spread server networks and serve the images to the client from the nearest server.
![](./images/CDN.jpg)

## 5: Minify your CSS files to reduce size

Indentation and spaces in code are for human readability but browsers don't need it.

[Minify](https://web.dev/minify-css/) your files using a bundler such as webpack or rollup to reduce your file size. 

## 6: Handle your scripts wisely

- Put the script at the bottom of the page. Then it can see elements above it, and it doesn’t block the page content from showing.
- Add an `async` or `defer` attribute to your script tags to load the files without blocking the HTML rendering.
[read more](https://javascript.info/script-async-defer)
