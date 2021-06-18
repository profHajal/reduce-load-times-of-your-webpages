<h1>47% of website visitors quit if the website doesn't load within 5 seconds.

Here are a few tips to reduce load times.</h1>

# 6 tips to reduce load times of your webpages.
## 1: preload CSS
At the top of the head tag, keep a link referring to the CSS file with rel attribute as `preload`.

Then have a link with rel as `stylesheet` to apply the CSS.

This makes the CSS file available as soon as its required for the rendering of the page later on.
![](./images/preload.jpg)

## 2: preconnect to resources

It tells the browser to create a connection to the link in advance and makes it aware that you might fetch images or data from this URL.
![](./images/preconnect.jpg)


