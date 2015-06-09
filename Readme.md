# AMO description of RequestPolicy

This repository is simply a place for managing RequestPolicy's description,
summary and screenshots for its [AMO page](https://addons.mozilla.org/en-US/firefox/addon/requestpolicy-continued/).
If you find a typo or if you think something could be changed, simply create
a pull request. Note however that the main place for information about
RequestPolicy is the project's [website](https://requestpolicycontinued.github.io/).

## Description

You might prefer to read this description in a text editor or on [AMO](https://addons.mozilla.org/en-US/firefox/addon/requestpolicy-continued/).

```html
<b>RequestPolicy's new version is under development as <a href="http://requestpolicycontinued.github.io/requestpolicy/">RequestPolicy Continued</a>.</b> Ultimately, I'd like RequestPolicy Continued to replace RequestPolicy.

RequestPolicy development has been slow because I am working on <a href="https://serverpilot.io">ServerPilot</a>, a cPanel alternative for DigitalOcean servers. Thankfully, some great community members are taking over development of RequestPolicy.

----

RequestPolicy is an extension that improves the privacy and security of your browsing by giving you control over when cross-site requests are allowed by webpages you visit.

Cross-site requests are requests that your browser is told to make by a website you are visiting to a completely different website. Though usually legitimate requests, they often result in advertising companies and other websites knowing your browsing habits, including specific pages you view throughout the day. Among the attacks that cross-site requests are used in, they are particularly dangerous with Cross-Site Request Forgery (CSRF) attacks where your browser is told to make a request to another website and that other website thinks you (the person) meant to make the request.

With RequestPolicy, the default for any cross-site request is to deny it. Users are notified when requests on the current page have been blocked (the status bar flag icon at the bottom right of your browser turns red). Clicking on this status bar flag icon gives you a menu where you can view and modify which requests are blocked and allowed. You can whitelist requests you approve of by origin site, destination site, or specific origin-to-destination.

More information on the privacy reasons for using RequestPolicy is available at:
<a href="https://www.requestpolicy.com/privacy">https://www.requestpolicy.com/privacy</a>

More information on the security reasons for using RequestPolicy is available at:
<a href="https://www.requestpolicy.com/security">https://www.requestpolicy.com/security</a>

RequestPolicy is not a replacement for NoScript! Each focuses on different, important issues. For the best security, we recommend using both RequestPolicy and NoScript. More information on the difference between the two is available here:
<a href="https://www.requestpolicy.com/faq#faq-noscript">https://www.requestpolicy.com/faq#faq-noscript</a>

`*********************************************************************************`
NOTE: As with any extension that blocks content, some websites will not work properly until you have allowed the required content. If a website you visit isn't working, you can use the RequestPolicy menu to allow the cross-site requests the website needs. After a short while of using RequestPolicy, you will have whitelisted all of the required cross-site requests for sites you frequently visit and you will use the RequestPolicy menu much less.
`*********************************************************************************`
```

Some notes for editing:

  * newlines are automatically converted to <br>
  * allowed HTML: `<a href title>` `<abbr title>` `<acronym title>` `<b>` `<blockquote>` `<code>` `<em>` `<i>` `<li>` `<ol>` `<strong>` `<ul>`


## Summary

Be in control of which cross-site requests are allowed. Improve the privacy of your browsing by not letting other sites know your browsing habits. Secure yourself from Cross-Site Request Forgery (CSRF) and other attacks.

(220 characters)

---

The summary is a short explanation of the add-on's basic functionality
that is displayed in search and browse listings, as well as at the top of the
add-on's details page.

Max. 250 characters, no HTML.

## Screenshots

<img src="https://raw.githubusercontent.com/RequestPolicyContinued/amo-description/master/images/001.png" />

You can see which requests have been allowed and chose to revoke permissions that you granted earlier.

<br />

--

<br />

<img src="https://raw.githubusercontent.com/RequestPolicyContinued/amo-description/master/images/002.png" />

You can allow requests from a specific origin site to a specific destination site. This way, you don't have to allow either all requests from that origin or all requests to that destination.

<br />

--

<br />

<img src="https://raw.githubusercontent.com/RequestPolicyContinued/amo-description/master/images/003.png" />

An example of a single website (lemonde.fr) that tries to have your browser make requests to many destinations.
