# UI Cleaner UserStyles

A collection of **UserStyles** designed to declutter Twitch, NotebookLM, X.com/Twitter, and YouTube by removing promotional elements, unnecessary buttons, and other distractions for a cleaner browsing experience.

---

## Features

### **Twitch UI Cleaner**

* Removes **Bits icons, balances, and buttons**.
* Hides **Stories** and **Story navigation buttons**.
* Collapses leftover spacing for a cleaner top bar.
* Hides **"More options"** buttons in chat.
* Removes **promotional buttons** like *"Go Ad-Free For Free"*.
* Hides **top-bar triple-dot menus** and **new item indicators**.

### **NotebookLM UI Cleaner**

* Hides **footer and disclaimers**.
* Removes **discovery and promotional sections**.
* Hides **share buttons, non-CTA buttons, and “Add Note” button**.
* Removes **Google Apps menu** and **featured notebooks** on the main page.
* Hides **feedback buttons** (thumbs up/down) and **Upgrade / Pro buttons**.
* Removes **Interactive Mode button** for a streamlined experience.

### **X.com / Twitter UI Cleaner**

* Hides **sidebar panels** including Grok, Trends, “Who to Follow”, and “Trending now”.
* Removes **Super Upsell Cards** (Premium prompts) and **Promotional tabs**.
* Hides **Articles** and **Highlights** tabs.
* Removes **Grok buttons**, **Tag location**, and **Schedule post** buttons.
* Hides **monetization links**, **ads links**, and other clutter from the sidebar.
* Cleans up **profile settings tabs** like Premium, Creator Subscriptions, and Monetization.
* Collapses leftover spacing from hidden buttons and tabs for a streamlined layout.

### **YouTube UI Cleaner**

* Removes **Upload (camera)** and **Voice Search (microphone)** buttons from the header.
* Hides **Notifications bell** and unread count badges.
* Removes **experimental UI elements** such as *Ask* buttons and **Tags** features.
* Cleans the **left sidebar (Guide)** by removing:
  * **Explore** and **More from YouTube** sections.
  * **Help**, **Send feedback**, and **Report history** links.
  * The entire **sidebar footer** (About, Press, Copyright, Terms, Privacy).
* Preserves essential navigation while eliminating clutter.
* Completely hides the **recommended videos sidebar** on the watch page.
* Removes **AI-generated summaries** and **filter chips** above recommendations.
* Forces the **video player and main content** to expand to full width for a distraction-free viewing experience.
* Eliminates wasted space caused by hidden elements for a clean, focused layout.

---

## Installation

1. Install a **UserStyle manager** in your browser:

   * [Stylus](https://add0n.com/stylus.html) (Recommended)
   * [UserCSS](https://chrome.google.com/webstore/detail/usercss/...)

2. Install directly from GitHub using the **raw CSS URLs**:

   * [Twitch UI Cleaner](https://github.com/RaspberryKitty1/UserScripts/raw/refs/heads/main/twitch-ui-cleaner.user.css)

   * [NotebookLM UI Cleaner](https://github.com/RaspberryKitty1/UserScripts/raw/refs/heads/main/notebooklm-ui-cleaner.user.css)

   * [X.com / Twitter UI Cleaner](https://github.com/RaspberryKitty1/UserScripts/raw/refs/heads/main/x_twitter-ui-cleaner.user.css)

   * [YouTube UI Cleaner](https://github.com/RaspberryKitty1/UserScripts/raw/refs/heads/main/youtube-ui-cleaner.user.css)

   > Click the link, and Stylus should prompt you to **install the style automatically**.

3. Enable the style in Stylus.

4. Reload the site to see the cleaner interface.

---

## Compatibility

* Tested on **Firefox** and **Chrome**.
* Works with modern versions of **Twitch**, **NotebookLM**, **X.com/Twitter**, and **YouTube**.
* Some selectors use dynamic class names; if elements reappear after a site update, you may need to tweak the style.

---

## Notes

* These styles **do not remove essential functionality** like chat messages or notebook content.
* They focus on **visual decluttering** only.
* If you notice gaps or layout issues, inspect the element and adjust `display: none` or `gap` values in the CSS.

---

## Contributing

* Pull requests welcome for:

  * Adding new hidden elements.
  * Improving selector robustness.
  * Fixing layout issues after site updates.

---

## License

* MIT License
* Author: **Raspberrykitty1**
