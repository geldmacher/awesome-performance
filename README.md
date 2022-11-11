# Awesome web **performance** list

A curated list of awesome web performance stuff

## How-To’s

- [Optimizing resource loading with Priority Hints](https://web.dev/priority-hints/) - Priority hints indicate the relative importance of resources to the browser. They can enable optimal loading and improve Core Web Vitals.
- [Measure and debug performance with Google Analytics 4 and BigQuery](https://web.dev/vitals-ga4/) - Learn how to send Web Vitals data to Google Analytics 4 properties and export the data for analysis in BigQuery and Data Studio.
- [Optimizing Web Vitals using Lighthouse](https://web.dev/optimize-vitals-lighthouse/) - Finding opportunities to improve user-experience with Chrome's web tooling
- [Web Performance Recipes With Puppeteer](https://addyosmani.com/blog/puppeteer-recipes/) - This guide has recipes for automating Web Performance measurement with Puppeteer
- [Performance Checklist](https://www.smashingmagazine.com/2020/01/front-end-performance-checklist-2020-pdf-pages/) - Everything you need to know in 2020
- [perf.rocks](https://perf.rocks/) - Find resources that help you build lightning fast websites
- [Metrics](https://web.dev/metrics/) - Measure and optimize performance and user experience
- [Fast load times](https://web.dev/fast/) - Guarantee your site loads quickly to avoid user drop off
- [Network reliability](https://web.dev/reliable/) - See consistent, reliable performance regardless of network quality
- [Measuring Performance With Server Timing](https://www.smashingmagazine.com/2018/10/performance-server-timing/) - The Server Timing header provides a discrete and convenient way to communicate backend server performance timings to developer tools in the browser. Adding timing information to your application enables you to monitor back-end and front-end performance all in one place.
- [Your first performance budget with Lighthouse](https://bitsofco.de/your-first-performance-budget-with-lighthouse/) - We can now define a simple performance budget in a JSON file, which will be tested as part of the lighthouse audit!
- [Accurately measuring layout on the web](https://nolanlawson.com/2018/09/25/accurately-measuring-layout-on-the-web/) - So in this post, I want to demystify some of these concepts, and offer techniques for accurately measuring what’s going on when we render things on the web.
- [Optimize First Input Delay](https://web.dev/optimize-fid/) - First Input Delay (FID) is a Core Web Vitals metric that captures a user's first impression of a site's interactivity and responsiveness. It measures the time from when a user first interacts with a page to the time when the browser is actually able to respond to that interaction.
- [Optimize Cumulative Layout Shift](https://web.dev/optimize-cls/) - Cumulative Layout Shift (CLS) - a Core Web Vitals metric, measures the instability of content by summing shift scores across layout shifts that don't occur within 500ms of user input. It looks at how much visible content shifted in the viewport as well as the distance the elements impacted were shifted.
- [Optimize Largest Contentful Paint](https://web.dev/optimize-lcp/) - Largest Contentful Paint (LCP) is a Core Web Vitals metric and measures when the largest content element in the viewport becomes visible. It can be used to determine when the main content of the page has finished rendering on the screen.
- [content-visibility: the new CSS property that boosts your rendering performance](https://web.dev/content-visibility/) - content-visibility enables the user agent to skip an element's rendering work, including layout and painting, until it is needed. Because rendering is skipped, if a large portion of your content is off-screen, leveraging the content-visibility property makes the initial user load much faster. It also allows for faster interactions with the on-screen content.

## Articles

- [Improving Core Web Vitals, A Smashing Magazine Case Study](https://www.smashingmagazine.com/2021/12/core-web-vitals-case-study-smashing-magazine/)
- [Picture perfect images with the modern img element](https://stackoverflow.blog/2022/03/28/picture-perfect-images-with-the-modern-element/) - The humble <img> element has gained some superpowers since it was created. Given how central it is to image optimization on the web, let’s catch up on what it can do and how it can help improve user-experience and the Core Web Vitals. 
- [How focusing on web performance improved Tokopedia's click-through rate by 35%](https://web.dev/tokopedia/) - Tokopedia is one of the largest e-commerce companies in Indonesia. With 2.7M+ nationwide merchant networks, 18M+ product listings, and 50M+ monthly visitors, the web team knew that investment in web performance was essential. By building a performance-first culture, they achieved a 35% increase in click-through rates (CTR) and an 8% increase in conversions (CVR).
- [How Mercado Libre optimized for Web Vitals (TBT/FID)](https://web.dev/how-mercadolibre-optimized-web-vitals/) - Optimizing interactivity of product details pages for a 90% reduction in Max Potential FID in Lighthouse and a 9% improvement in FID in Chrome User Experience Report.
- [Milliseconds make millions](https://web.dev/milliseconds-make-millions/) - A 0.1 second improvement in 4 speed metrics can improve progression rates across the full purchase funnel.
- [Web Vitals: essential metrics for a healthy site](https://blog.chromium.org/2020/05/introducing-web-vitals-essential-metrics.html?m=1) - Measuring the quality of user experience has many facets. While some aspects of user experience are site and context specific, there is a common set of signals — "Core Web Vitals" — that is critical to all web experiences.
- [Why Performance Matters](https://developers.google.com/web/fundamentals/performance/why-performance-matters) - Performance issues vary. At best, they create small delays that are only briefly annoying to your users. At worst, they make your site completely inaccessible, unresponsive to user input, or both.
- [WPO stats](https://wpostats.com/) - Case studies and experiments demonstrating the impact of web performance optimization (WPO) on user experience and business metrics.
- [The Impact of Web Performance](https://simplified.dev/performance/impact-of-web-performance) - I’m going to show that rendering performance is more important than any of the Lighthouse page load metrics
- [Move Fast & Don’t Break Things](https://www.filamentgroup.com/lab/dontbreakthings/) - It’s true, new web technology is exciting, but we already have the tools to build amazing things and deliver them efficiently today.
- [Smaller HTML Payloads with Service Workers](https://philipwalton.com/articles/smaller-html-payloads-with-service-workers/) - A service worker can request just the bare minimum of data it needs from the server (e.g. an HTML content partial, a Markdown file, JSON data, etc.), and then it can programmatically transform that data into a full HTML document.
- [Using Native JavaScript Modules in Production Today](https://philipwalton.com/articles/using-native-javascript-modules-in-production-today/) - The technique allows you to ship significantly less code to module-supporting browsers, and it’s now supported by most web frameworks and CLIs.
- [ECMAScript modules in browsers](https://jakearchibald.com/2017/es-modules-in-browsers/) - All you need is type=module on the script element, and the browser will treat the inline or external script as an ECMAScript module.
- [Loading Polyfills Only When Needed](https://philipwalton.com/articles/loading-polyfills-only-when-needed/) - The solution to this problem is to only load polyfills when they’re needed, but as it turns out, in practice that’s a lot harder than it sounds.
- [When CSS Blocks](https://timkadlec.com/remembers/2020-02-13-when-css-blocks/) - Preload is a bit of a blunt instrument—whatever you apply to it is gonna jump way up in line to be downloaded. The use of preload means that these stylesheets, which you’re presumably making asynchronous because they aren’t very critical to page display, are given a very high priority by browsers.

## Implementations

- [Youtube Embed Component](https://github.com/paulirish/lite-youtube-embed) - Provide videos with a supercharged focus on visual performance. This custom element renders just like the real thing but approximately 224X faster.

## Tools

- [sitespeed.io](https://www.sitespeed.io/) - Sitespeed.io is a set of Open Source tools that makes it easy to monitor and measure the performance of your web site.
- [Turbolinks](https://github.com/turbolinks/turbolinks) - Get the performance benefits of a single-page application without the added complexity of a client-side JavaScript framework.
- [Quicklink](https://getquick.link/) - Faster subsequent page-loads by prefetching in-viewport links during idle time ([Angular module](https://www.npmjs.com/package/ngx-quicklink)).
- [Instant.page](https://github.com/instantpage/instant.page) - instant.page uses *just-in-time preloading* — it preloads a page right before a user clicks on it.
- ["constant-locals-loader" for Webpack](https://www.npmjs.com/package/constant-locals-loader) - This loader optimizes the output of mini-css-extract-plugin and/or css-loader, entirely removing the potentially large CSS classname mappings normally inlined into your bundle when using CSS Modules.
- [Speed Measure Plugin for webpack](https://www.npmjs.com/package/speed-measure-webpack-plugin) - This plugin measures your webpack build speed.
- [Layout Shift GIF Generator](https://github.com/workeffortwaste/layout-shift-gif) - Visualise the Core Web Vitals metric Cumulative Layout Shift (CLS) with a simple GIF.

## Converter

- [webp](https://developers.google.com/speed/webp) - WebP is a modern **image format** that provides superior **lossless and lossy** compression for images on the web. Using WebP, webmasters and web developers can create smaller, richer images that make the web faster.
- [FFmpeg](https://www.ffmpeg.org/) - Converting **video** and **audio** has never been so easy.
- [svgo](https://github.com/svg/svgo) - **SVG O**ptimizer is a Nodejs-based tool for optimizing SVG vector graphics files ([Web GUI](https://jakearchibald.github.io/svgomg/)).

## Other awesome lists

- https://github.com/davidsonfellipe/awesome-wpo#readme
- https://github.com/csabapalfi/awesome-web-performance-metrics#readme
- https://github.com/pajaydev/awesome-web-performance-budget#readme
