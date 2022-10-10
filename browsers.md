## Why every relevant web browser sucks.

In no particular order - OS tags refer to issues only present when using that OS.

### The Good
#### Firefox
 - `Shift+RMB` force-opens a context menu
 - Customization
 - Context menu allows opening an iframe's url directly
 - [Windows] Tab scrolling (`toolkit.tabbox.switchByScrolling`)

#### Chrome
 - Automatically adds search engines for visited sites
 - Cancelling URLbar input refocuses the page



### The Bad
#### Firefox
 - Less compatible
 - `Alt+Return` on the new tab page replaces the current tab, instead of opening a new tab
 - As of recent-ish, tab navigation on google is unresponsive for a solid second after results appear (certainly intentional)
  - Cancelling URLbar input keeps the focus on the URLbar, making going back to controlling the page with the keyboard fiddly
 - [Linux] No VDPAU (Nvidia) Video Acceleration
 - [Linux] Dotfile in home (`.mozilla`), contains actual data & is finnicky when spoofing $HOME.
 - [Linux] Credential autofill is unusably clunky in bspwm
 - [Linux] Can't screen-share a single monitor - Fails and makes the monitor in question unresponsive to mouse input
 - [Linux] In bspwm with tiled mode, the context menu is moved up and to the left in proportion to the border size, causing accidental clicks 
 
#### Chrome
 - Has no pure-CSS way to know window focus (`:-window-inactive`)
 - No customization, ugly
 - Cannot hold `Ctrl+T` or `Ctrl+W` to open/close multiple tabs
 - No proper way of force-opening a context menu
  - No option in the context menu to open an iframe's url directly
 - [Linux] No VDPAU (Nvidia) Video Acceleration
 - [Linux] Dotfile in home (`.pki`), doesn't contain actual data, but likes to keep reappearing.
 - [Linux] Changing focus to another desktop doesn't properly relay the focus loss to the focused tab (ex: discord notifications don't get made, and false unreads happen)
 - [Linux] Disabling EWMH fullscreen requires resizing the window to fix cropping
 - [Linux] Slow scrolling
 - [Linux] No autoscroll
 - [Linux] can't drag tabs/links to another monitor on bspwm, can only right click -> send to window.
 - [Windows] No tab scrolling

#### Brave
 - Basically everything from chrome
 - No side-scrolling for both normal webpages, and images (Arrow Keys & Shift+Scroll)
 - Scrollwheel is ignored on some videos (ex: fullscreen youtube)


### Other:
 - `full-screen-api.ignore-widgets` Fixes no-EWMH fullscreen on firefox


---

Sidenote; a couple extension recommendations:

 - **uBlock Origin** -- Indeed very popular, but I still have to shill it to far too many people.
 - **Scroll Anywhere** -- Replaces autoscroll, acts like you grabbed the scrollbar but is actually convienent.
 - **Purple Ads Blocker** -- Blocks ads on twitch
 - **FastForward** -- Skip redirect links.  Makes right click -> copy link on google useful, and many other things.
 - **Reddit Enhancement Suite** -- Makes reddit usable.
 - **SponsorBlock** -- Skip integrated ads/credits/interaction reminders in youtube videos
 - **Return Youtube Dislike**
 - **Notifier for Gmail** / **Gmail NotifierT**
 - **ViolentMonkey** -- Userscript Injector
   * **[YT: not interested in one click](https://greasyfork.org/en/scripts/396936)** -- Adds buttons to quickly dismiss a youtube video
   * **[Amazon Camel Graph Revived/Fixed](https://greasyfork.org/en/scripts/24854)** -- Adds price history graph directly to amazon pages
   * **[Hide Email Address From Title Bar](https://greasyfork.org/en/scripts/38152)**
 - **Stylus** -- CSS Injector
   * **[rainbow](https://github.com/6gk/gkay)**
 
(I have ~27 extensions, ~29 custom stylesheets, and ~18 userscripts... Most are minor fixes hence not mentioned here)
