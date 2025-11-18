# UI Cleaner UserStyles

A set of **UserStyles** to declutter the Twitch and NotebookLM interfaces, hiding promotional elements, unnecessary buttons, and other distractions for a cleaner browsing experience.

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

---

## Installation

1. Install a **UserStyle manager** in your browser:

   * [Stylus](https://add0n.com/stylus.html) (Recommended)
   * [UserCSS](https://chrome.google.com/webstore/detail/usercss/...)

2. Install directly from GitHub using the **raw CSS URLs**:

   * [Twitch UI Cleaner](https://raw.githubusercontent.com/raspberrykitty1/UserScripts/twitch-ui-cleaner.user.css)

   * [NotebookLM UI Cleaner](https://raw.githubusercontent.com/raspberrykitty1/UserScripts/notebooklm-ui-cleaner.user.css)

   > Click the link, and Stylus should prompt you to **install the style automatically**.

3. Enable the style in Stylus.

4. Reload Twitch or NotebookLM to see the cleaner interface.

---

## Compatibility

* Tested on **Firefox** and **Chrome**.
* Works with modern versions of **Twitch** and **NotebookLM**.
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
