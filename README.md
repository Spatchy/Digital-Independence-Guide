# Digital Independance Guide
A guide for moving your dependance away from big tech companies.

## How to use this guide
This guide will be split into three parts: Basic, Standard, and Complex.
- Steps in the Basic section, anyone should be able to do in a couple of minutes and see results with no downsides compared to the big tech product or service they were using before.
- Steps in the Standard section may be more in depth or time-consuming and may require following a tutorial external to this guide. After following these steps, some things may require tweaking or personalisation for you to be happy with the result.
- Steps in the Complex section require some level of technical knowledge and confidence, or may require buying your own hardware (such as a home server) to complete. Following steps in this section incorrectly may lead to device damage or data loss. Don't let this put you off though - if you've ever built a PC, installed Linux (even if you didn't use it for very long), or tinkered with custom ROMs on your Android phone, you have the right skills for following steps in this section.

> [!Tip]
> It's recommended to read each section through **completely** once, before you start to do anything as further steps may give more insight on what option is best for you.

#### Emoji Indicators
This guide will use emoji to indicate various information about the options at each step.
- 🌟 - My personal favourite. This is the option I use personally, it may not be for everyone.
- 🔮 - The absolute easiest option for beginners.
- ‼️ - This option is for more advanced users (even if in a basic or standard step).

If you think anything is missing, incorrect or can be improved in this guide, please submit an issue.

> [!NOTE]  
> Any steps for "mobile" in this guide are currently Android-only. Due the the "walled garden" nature of iOS, steps that can be taken are more limited but suggestions are welcome.

## Basic
All steps in this section should be easy enough for anyone to follow and complete in a few minutes, with no downsides at the end.

### Switch your browser
Chrome is still the most widely used web browser, and you may be using it without even knowing. Many other browsers including Edge, Brave, and Opera are just Chrome with a few tweaks. Google still has complete control over these browsers and can enforce its control over them, doing things like [breaking adblock extensions](https://www.digitaltrends.com/computing/your-favorite-chrome-extension-may-stop-getting-support-soon/). To avoid this, you should switch to an open-source Firefox-based browser. Good options include:
##### **For desktop:**
  - Zen Browser 🌟 - Has a really nice UI with a vertical tab layout.
  - Waterfox 🔮 - Sticks closer to the vanilla Firefox look and feel but with better privacy defaults
  - Librewolf - For the privacy concious user, has advanced tracking protections built-in. Librewolf does not allow syncing tabs, history, etc. to a Mozzilla account.
##### **For Mobile**
  - Waterfox 🌟🔮 - As with the desktop version, provides a vanilla Firefox-like expereince with better defaults for privacy and user sanity
  - Mull - A privacy hardened version of Firefox for Android
  - Ironfox - Another Firefox fork designed for privacy, popular amoung GrapheneOS users.
> [!Warning]  
> You may read Firefox and be tempted to just install the Firefox browser iteself. I can't recommend this as Firefox does conduct some user tracking by default, and while this can be turned off, it occasionally can turn itself back on. The default Firefox home page also contains sponsored articles (i.e. ads) sometimes from some not-so-reputable news sources. Finally, it's worth noting that a large majority of Mozilla's revenue comes from a deal with Google to set Google as the default earch engine in Firefox.
---
### Switch your search engine
Google is still the most used search engine in the world, even though many users have complained about declining quality of search results for several years. There are several search engines that are now completely independant from the search indexes made by the big tech companies and that don't force untrustworthy AI responses at the top of search results.
- Qwant 🌟🔮 - A privacy-protecting seach engine with a brand new search index, developed in collaberation with Ecosia.
- Ecosia - A search engine known for planting trees using revenue from sponsored results. Partnered with Qwant to develop a new independant search index.
- DuckDuckGo - Probably the most famous privacy-focussed search engine. Note though that their index is powered entirely by Bing, enough to make them no longer the top recommendation.
- SearXNG ‼️- A self-hosted frontend for aggregating results from other search engines.
> [!Tip]
> If your chosen browser doesn't list your chosen search engine in its settings, you can usually add it using an extension. See the following section on browser extensions.
> You can also add a search engine manually if you know its search URL and suggestions API URL.
---
### Install recommended browser extensions
With your browser changed, you'll likely want to install some extensions to make your browsing experience better. Here are some absolute essentials:
- uBlock Origin 🌟🔮 - More than just an ad blocker, this open source content blocker is the gold standard. Everyone should have this installed. **This can and should be installed in your browser on mobile too!**
- Consent-O-Matic 🌟🔮 - Automatically declines all optional cookies and tracking on most sites. No more messing with confusing checkboxes or switches.
- Return YouTube Dislike 🌟 - Brings back the dislike count on YouTube.
- Sponsorblock 🌟 - Automatically skips sponsor segments in YouTube videos.
- Your chosen search engine's extension if it's not available by default in your browser's settings.
- Your password manager's extension if you use one. (See the section below on Password Mangers).
---
### Switch to an open source office suite
Microsoft Office (Now just "MS365", although no one calls it that) is virtually synonymous with office suites as a whole, and Google Docs is the most well-known alternitive with its in-browser solution. Unless you are *absolutely* locked in to the real-time collaberation features of either one for work (where multiple users edit the same document at the same time together), you should absolutely switch to one of the following open source alternives:
- LibreOffice 🌟🔮 - A very solid office suite providing apps for documents, spreadsheets, presentations, desktop publishing (MS Publisher alternative) and a database frontend (MS Access alternative). There is also a beta mobile app which can be used for viewing and basic edits
- OnlyOffice - An open source solution that offers downloadable apps for both mobile and desktop, as well as in-browser editors for documents, spreadsheets, presentations and forms (Google Forms alternative). It is designed with collaberation in mind and allows multiple users to work on documents together if they have an account. Probably a better solution for businesses than individuals.
---
### Change your weather app
If you're using the weather app that came with your phone, it likely relies on big tech for some of its services. You can easily swap this for an open source weather app.
- Breezy 🌟🔮 - a very well designed open source weather app. You can change the information sources for virtually everything, but its defaults work just fine.

## Standard
The steps in this section are a little bit more involved or may take considerable time to complete. Most people should still be able to complete them, although there may be a few missing features compared to what you're used to without some tweaking.
### Change your email client app
Most people don't use email clients on desktop anymore, the exception being Outlook for business users who's company is locked into Microsoft's ecosystem. Most people on mobile are using the Gmail app, even if their primary email isn't their gmail account. You don't have to change your email provider to change the client you use, and using a client that supports multiple accounts makes switching your provider easier:
##### Desktop:
- Thunderbird 🌟 - Mozzilla's open source email client, has a layout similar to Outlook by default but is very customisable.
##### Mobile:
- Thunderbird 🌟 - The mobile app equivilent to Thunderbird on desktop. Its UI is very similar to other mobile email apps like Gmail.
> [!Warning]
> If you have Outlook account (e.g. @live.com or @hotmail.com), SMTP/IMAP access may be disabled by default. This must be enabled before you can use another email client. You can enable it in settings in the web version of outlook for personal accounts. For business, school, or university accounts, your administrator will have to do this for you through their admin portal.
---
### Use an alternative mobile app store
Most android apps are usually downloaded from Google Play, obviously this is a problem if you want to avoid using Google for as much as you can. Here are some alternative ways to download apps *and* keep them up to date (something that manually just sideloading APKs can't do). You may have to use more than one of these solutions depending on your needs.
- F-Droid 🌟 - A repository of thousands of open source apps. Many of the recommendations from this guide can be found here. Note that you'll only find open source apps on F-Droid, many of the apps you'd find on the Play Store aren't here.
- Aurora Store 🌟 - An anonymous frontend for the Google Play Store. You can also spoof which device you are using for even greater privacy. Note that apps that require payment cannot be downloaded unless you are using your actual Google account which isn't recommended due to account ban risk.
- Obtainium 🌟 - Get and update apps directly from their Git releases page (GitHub, GitLab, Codeberg, etc.). A little harder to use since there is no way to browse, you must already know the app you want to install.
- Accressent - Another, different open source app store specifically for privacy-hardened apps. There's not much in here at the moment, as it's relatively new.
- Droidify - An alternative frontend for F-Droid with a nicer GUI, you don't need the F-Droid app if you're using this instead.
---
### Use alternative apps for YouTube
YouTube is virtually unavoidable if you want to watch online video. There are alternative platforms, both paid like Nebula and free like FreeTube, if the creators you watch also post on those platforms, although most don't. The best way to continue watching YouTube without allowing Google to earn money from you, is to block ads and enable as many premium features for free as you can, depending on your needs. Watching youtube in a Firefox-based browser with the recommended extensions (see above) is one way to do this on desktop, although Google will still track everything you watch if you're signed in, and will use this to profile you.
##### Web/Desktop:
- Invideous ‼️ - A self-hosted service (public instances are available) that acts as a frontend for viewing YouTube videos in your browser without ads or tracking. Obviously you can't like or comment as you're not signed in. Can sometimes be slow if you use a public instance.
##### Mobile:
- NewPipe - An open source YouTube client for Android that blocks all ads and tracking. It also enables background playback when the screen is off for free. Subscriptions and view history are stored offline on your device and not synced anywhere, but you can import your subscriptions if you downloaded them via a data access request from Google.
- GreyJay - Open source and very similar to Newpipe but intended to follow creators across multiple platforms (YouTube, Twitch, Patreon, Nebula, etc.). Also allows enabling Sponsorblock and streaming to a TV with an Fcast reciever installed.
- YouTube ReVanced 🌟 - A mod for the official YouTube app that blocks ads, optinally enables sponsorblock and deArrow, and enables many YouTube Premium features for free, including screen-off playback and video downloads. All subscriptions, likes, comments and watch history continues to sync with official YouTube servers.
##### TV (Android TV, Google TV, Amazon Fire TV):
- Smart Tube 🌟 - An open source YouTube client for smart TVs, boxes and streaming sticks that blocks ads and some tracking and optionally enables Sponsorblock and DeArrow. Subscriptions, watch history and likes continue to sync to official YouTube servers.

## Complex
(coming soon)

## Tips and tricks
(coming soon)

## Todo
- [ ] Complex section
- [ ] Tips and tricks section
- [ ] Add contents section for easy navigation
- [ ] Add more steps for other services in Basic and Standard sections
- [ ] Add links to all mentioned alternatives
- [ ] Improve instructions and add links to external guides for some steps
