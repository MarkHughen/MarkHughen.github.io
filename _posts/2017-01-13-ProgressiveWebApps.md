---
layout: post_page
title: Progressive Web Apps (PWA) - Should We Continue Developing Native Mobile?
date: 2017-01-13
tags: Programming
---
Progressive Web Apps (PWA) address concerns of native mobile application development (offline availability, data sparing, networking connectivity) with regular HTML, CSS, and JavaScript. As a development shop should we continue devoting resources to native mobile development? Portfolio management perspectives appreciate consolidation of development frameworks. These are raw notes from [.NET Rocks podcast](https://www.dotnetrocks.com/?show=1396).

Creates a web site application which is good enough to be installed on homescreen.
<ul>
<li>Google promoting with documentary. Indexable PWAs. https://developers.google.com/web/progressive-web-apps/</li>
<li>progressive vs native comparison - https://medium.com/dev-channel/why-progressive-web-apps-vs-native-is-the-wrong-question-to-ask-fb8555addcbb#.dnexmvcoz</li>
<li>O'Reilly's take on it with their top web trends for 2017 https://www.oreilly.com/ideas/5-web-trends-for-2017</li>
</ul>
<h2>Notes from .NET Rocks podcast</h2>
<ul>
<li>Is the distribution model in place without the app store?</li>
<ul>
<li>Closed App Stores are a thing of the past. Will Safari play ball.</li>
<li>Questionable how these work on iPhone.</li>
<li>SEO makes more discoverable than app store.</li>
</ul>
<li>*Service Worker* - build offline clients. Background syncing. Programmable HTTP router in code intercepting HTTP requests.</li>
<li>*Push notification engine* - best UX for these, overuse from marketers</li>
<li>*Manifest File* - don't need to type URL, notifications, offline</li>
<ul>
<li>Icons on phone instead of URLs</li>
</ul>
<li>Consider, don't use JavaScript frameworks, saves overhead processing on mobile device.</li>
<li>Turn regular websites into PWA. Don't need to start from scratch.</li>
<li>Local Storage lets you store on user's computer. Many cache options.</li>
<li>React - doesn't matter what front-end framework you use.</li>
<li>Electron - Slack, creates native installs on mobile environment. What is Electron?</li>
<li>Instant Articles - is this the same technology Facebook is using with IA?</li>
<li>This is not a new framework, but works with the web: HTML, CSS, JavaScript</li>
<li>Symmetrical implementation between the browsers.</li>
</ul>

PS - Have a look at WebCrypto and IndexedDB as an alternative to localstorage. Could fit nicely with PWAs https://medium.com/@mobitar/moving-beyond-localstorage-991e3695be15#.ergzpe6le
