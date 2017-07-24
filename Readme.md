# AMO description of RequestPolicy

This repository is simply a place for managing RequestPolicy's description,
summary and screenshots for its [AMO page](https://addons.mozilla.org/en-US/firefox/addon/requestpolicy-continued/).
If you find a typo or if you think something could be changed, simply create
a pull request. Note however that the main place for information about
RequestPolicy is the project's [website](https://requestpolicycontinued.github.io/).

## Description

You might prefer to read this description in a text editor or on [AMO](https://addons.mozilla.org/en-US/firefox/addon/requestpolicy-continued/).

```html
*********************************************************************************

<b>Quick Start:</b>

<ul>
<li><a href="https://requestpolicycontinued.github.io/Quickstart.html">Learn how to use RequestPolicy</a></li>
<li><a href="https://requestpolicycontinued.github.io/FAQ.html">Frequently Asked Questions</a></li>
</ul>

<b>If you have've got problems</b>, please visit our <a href="https://github.com/RequestPolicyContinued/requestpolicy">GitHub repository</a>. Make sure you've read our <a href="https://requestpolicycontinued.github.io/FAQ.html">FAQ</a> and the <a href="https://requestpolicycontinued.github.io/Contributing">contributing notes</a>. The ChangeLog is available <a href="https://github.com/RequestPolicyContinued/requestpolicy/blob/dev-1.0/ChangeLog.md">here</a>.

<b>Regarding multiprocess compatibility and Firefox 57+</b>, I'm working on a WebExtension version of this add-on. If you want to help with the transition, please install the "Development Channel" version at the bottom of this page. Thank you.


*********************************************************************************
<b> Frequently Asked Questions (FAQ)</b>
*********************************************************************************

<b>What is RequestPolicy?</b>

RequestPolicy is an extension that improves the privacy and security of your browsing by giving you control over when cross-site requests are allowed by webpages you visit.

<b>What are cross-site requests?</b>

<i>Cross-site requests</i> are requests that your browser is told to make by a website you are visiting to a completely different website. Though usually legitimate requests, they often result in advertising companies and other websites knowing your browsing habits, including specific pages you view throughout the day. Among the attacks that cross-site requests are used in, they are particularly dangerous with Cross-Site Request Forgery (CSRF) attacks where your browser is told to make a request to another website and that other website thinks you (the person) meant to make the request.

With RequestPolicy, the default for any cross-site request is to deny it. Users are notified when requests on the current page have been blocked (the status bar flag icon at the bottom right of your browser turns red). Clicking on this status bar flag icon gives you a menu where you can view and modify which requests are blocked and allowed. You can whitelist requests you approve of by origin site, destination site, or specific origin-to-destination.

<b>Why should I use RequestPolicy?</b>

RequestPolicy improves both privacy and security when browsing.
Read more: <a href="https://requestpolicycontinued.github.io/#privacy">privacy reasons</a> • <a href="https://requestpolicycontinued.github.io/#security">security reasons</a>

<b>Is RequestPolicy intended to be a replacement for <a href="https://addons.mozilla.org/en-US/firefox/addon/noscript/">NoScript</a>?</b>

No. Each of the two add-ons focuses on different, important issues. For the best security, we recommend using both RequestPolicy and NoScript. <a href="https://requestpolicycontinued.github.io/#faq-noscript" title="more information on the difference between RequestPolicy and NoScript">Read more</a>.


*********************************************************************************
<b>Usage Note</b>
*********************************************************************************

As with any extension that blocks content, some websites will not work properly until you have allowed the required content. If a website you visit isn't working, you can use the RequestPolicy menu to allow the cross-site requests the website needs. After a short while of using RequestPolicy, you will have whitelisted all of the required cross-site requests for sites you frequently visit and you will use the RequestPolicy menu much less.


*********************************************************************************
<b>Version 0.5.x and Version 1.x</b>
*********************************************************************************

On "addons.mozilla.org", you can find three different RequestPolicy pages: "<a href="https://addons.mozilla.org/en-US/firefox/addon/requestpolicy/">RequestPolicy</a>", "<a href="https://addons.mozilla.org/en-US/firefox/addon/requestpolicy-legacy/">RequestPolicy v0.5 Legacy</a>" and "<a href="https://addons.mozilla.org/en-US/firefox/addon/requestpolicy-continued/">RequestPolicy Continued</a>" (this page)

<ul>
<li>"RequestPolicy" is the original version of this Add-on, created by Justin Samuel. Justin stopped working on RequestPolicy in 2012.</li>
<li>"RequestPolicy v0.5 Legacy" is a fork of the original Add-on. Several compatibility issues have been fixed.</li>
<li><b>"RequestPolicy Continued"</b> (this add-on) is a fork of <i>Version 1.x Beta</i> by Justin Samuel. Compared to above v0.5.x releases, it has an improved user interface, the possibility to subscribe to rules, and many more new features.</li>
</ul>

The main reason "v0.5 Legacy" is still maintained is because "v1.x" not yet supports the "strictness" feature, needed by some users, see <a href="https://github.com/RequestPolicyContinued/requestpolicy/issues/474">this github issue</a>.

*********************************************************************************
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
