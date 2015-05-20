# From simple to complex

*[UWDC, May 2015](http://2015.uwdc.ru/lectures/koding/ot_prostogo_k_slojnomu.html)*

A mobile phone has almost the same processing power as a computer.
But slow and unstable network, small screens imposes significant limitations to they usage.
Luke Wroblewski in his book “[Mobile First](http://www.abookapart.com/products/mobile-first)”
describes some principles of designing user interaction in such “extreme” conditions.
This talk focuses on the implementation of certain principles:

* responsive images and lazy loading;
* dynamic style and script injections;
* optimization of the page rendering;
* building the project.

Also, I explain following topics:

* Why we have started using “Mobile First” approach.
* Why numbers of network requests matter especially for mobile environment.
* How to use `matchMedia` to tracking environment.
* How we improved process of compilation of styles.
* How to implement responsive images using `<picture>` tag and its polyfills.
* What benefits you can get from external image hosting and CDN.
