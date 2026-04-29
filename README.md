<div align="center">
<h1>💌 Love Link Generator 💌</h1>

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/12e2a109b84d4276b1d675e7f31c5ee6)](https://app.codacy.com/gh/R0mb0/Love_link_generator/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![pages-build-deployment](https://github.com/R0mb0/Love_link_generator/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/R0mb0/Love_link_generator/actions/workflows/pages/pages-build-deployment)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/R0mb0/Love_link_generator)
[![Open Source Love svg3](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/R0mb0/Love_link_generator)
[![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/license/mit)

<p>
A cute and incredibly easy-to-use companion web app to generate custom, interactive Valentine's Day proposal links! Just type the name of your special someone, hit generate, and share the magic instantly. No coding skills required to spread the love!
</p>

<div align="center">
  <a href="http://paypal.me/R0mb0">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/R0mb0/Support_the_dev_badge/blob/main/Badge/SVG/Support_the_dev_badge_Dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://github.com/R0mb0/Support_the_dev_badge/blob/main/Badge/SVG/Support_the_dev_badge_Light.svg">
      <img alt="Saved you time? Support the dev" src="https://github.com/R0mb0/Support_the_dev_badge/blob/main/Badge/SVG/Support_the_dev_badge_Default.svg">
    </picture>
  </a>
</div>



<h2><a href="https://r0mb0.github.io/Love_link_generator/">👉 Click here to create your custom link! 👈</a></h2>

</div>

[![01.png](https://github.com/R0mb0/Love_link_generator/blob/main/ReadmeImgs/01.png)](https://r0mb0.github.io/Love_link_generator/)

<div align="center">
<h2><a href="https://r0mb0.github.io/Love_link_generator/">👉 Or click here to discover the main project! 👈</a></h2>
</div>

[![01.png](https://github.com/R0mb0/Be_my_valentine/blob/main/Readme_Imgs/01.png)](https://r0mb0.github.io/Be_my_valentine/)

<hr>

<h2>🌟 What is this?</h2>
<p>This project is the official <strong>Link Generator</strong> for the <a href="https://github.com/R0mb0/Be_my_valentine" target="_blank"><strong>Be my valentine</strong></a> project. While the main project provides the interactive "proposal" experience, this tool allows <em>anyone</em> (even those with zero coding experience) to safely generate a custom URL injected with their loved one's name.</p>

<h2>🚀 Features</h2>
<ul>
<li><strong>Bulletproof URL Encoding</strong>: Uses native JavaScript <code>encodeURIComponent()</code> to ensure spaces, emojis, and line breaks are safely translated. Your link will never break!</li>
<li><strong>Native Mobile Sharing</strong>: Integrates the powerful <code>navigator.share</code> API. On mobile devices, clicking the share button opens the native OS sharing menu (WhatsApp, Telegram, iMessage, etc.) instantly.</li>
<li><strong>One-Click Clipboard Copy</strong>: Generates the link and automatically copies it to your clipboard with a smooth, user-friendly visual feedback.</li>
<li><strong>Consistent Aesthetic</strong>: Features the same dreamy, interactive cloud-painting background canvas and cute GIFs as the main Valentine project.</li>
<li><strong>Infinite Text Area</strong>: A sleek, rounded text area that prevents layout-breaking resizing but allows vertical scrolling for endless messages.</li>
</ul>

<h2>🛠️ How it works</h2>
<ol>
<li><strong>Type a Name:</strong> The user enters a name (or a short message) into the cute text area.</li>
<li><strong>Generate/Share:</strong> The JavaScript captures the input, sanitizes it for the web, and appends it to the base URL of the main project (using the <code>?name=</code> parameter).</li>
<li><strong>Delivery:</strong> The user copies the link or shares it directly via native apps. When the recipient opens it, the main project parses the URL and welcomes them by name!</li>
</ol>

<h2>🏆 Why make a separate Generator?</h2>
<ul>
<li><strong>User Experience</strong>: Manually typing URL parameters (like converting spaces to <code>%20</code>) is confusing for non-technical users. This abstracts the complexity away.</li>
<li><strong>Virality & Growth</strong>: By providing an easy-to-use tool, users are encouraged to create and share their own versions, drastically increasing the reach of the original open-source project.</li>
<li><strong>Monetization & Open Source Support</strong>: The hosted version of this tool can include ads or banners, supporting the developer's open-source efforts while keeping the core GitHub repository clean and free for forks!</li>
</ul>

<h2>⚡ Getting Started</h2>

<h3>Online</h3>
<p>Just visit the <a href="https://r0mb0.github.io/Love_link_generator/">Live Demo</a>, type a name, and share!</p>

<h3>Local Installation</h3>
<p>To run this tool locally:</p>
<ol>
<li><strong>Clone this repository</strong> or download the source code ZIP.</li>
<li>Double-click <code>generator.html</code> to open it in your browser.</li>
<li><em>Note: If you are hosting the main project on a different URL, remember to update the <code>baseUrl</code> variable inside the JavaScript!</em></li>
</ol>

<br>

<div align="center">
  <h3>Dedicated with love to Lucia ❤️</h3>
</div>

<br>

<a href="https://github.com/R0mb0/Crafted_with_AI">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/CraftedWithAIDark.svg">
<source media="(prefers-color-scheme: light)" srcset="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/NotMadeByAILight.svg">
<img alt="Not made by AI" src="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/NotMadeByAIDefault.svg">
</picture>
</a>
