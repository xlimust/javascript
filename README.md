# javascript
speeds up page loading by a few seconds
# Unused JavaScript can slow down your page load speed :
- If the JavaScript is render-blocking, the browser must download, parse, compile, and evaluate the script before it can proceed with all of the other work that's needed for rendering the page.
- Even if the JavaScript is asynchronous (not render-blocking), the code competes for bandwidth with other resources while it's downloading, which has significant performance implications. Sending unused code over the network is also wasteful for mobile users who don't have unlimited data plans.

Reduce unused JavaScript and delay script loading until needed to lower bytes used by network activities
- *https://massa.net/_nuxt/8cc9329.js*
- *https://massa.net/_nuxt/fc77377.js*
- *https://massa.net/_nuxt/811156f.js*

These suggestions can help pages load faster. They do not directly affect Performance scores.
