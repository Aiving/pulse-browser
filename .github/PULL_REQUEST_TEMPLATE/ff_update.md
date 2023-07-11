# Firefox Update

This bumps Firefox up to `{NEW_VERSION}` for security and performance reasons. Reviewers check the following before continuing:

## QA Requirements

- [ ] Sidebar

  - [ ] The sidebar exists
  - [ ] The settings and addons button are visible down the bottom
  - [ ] The bookmarks, history and synced tabs icons are in the sidebar
  - [ ] The sidebar can be resized properly
  - [ ] An [installed extension](https://addons.mozilla.org/en-US/firefox/addon/sidebar-note/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search) will appear in the sidebar
  - [ ] Sidebar-Tabs is Loaded and has a button visible down the bottom
  - [ ] Sidebar-Tabs can add a sidebar item to the sidebar
  - [ ] Sidebar-Tabs can remove a sidebar item to the sidebar
  - [ ] The sidebar keeps tabs active while closed when keep sidebar tabs active is set to true
  - [ ] The sidebar overwrites tabs when keep sidebar tabs active is set to false

- [ ] Extensions

  - [ ] Tabliss is loading correctly
  - [ ] Tabliss does not have the webextention symbol in the title bar
  - [ ] uBlock origin is loading correctly
  - [ ] QRCode generator is loading correctly

- [ ] About dialog

  - [ ] The new about dialog is present
  - [ ] The dialog has not significantly changed

- [ ] Pocket

  - [ ] Pocket is not present in the browser

- [ ] Preferences

  - [ ] All tabs in preferences open
  - [ ] The "More from {Vendor}" option is not present
  - [ ] The sidebar preferences are present and work as expected

- [ ] Welcome experience

  - [ ] The import button opens the import wizard
  - [ ] The theme picker is present and works as expected
  - [ ] The search engine picker is present and works as expected

- [ ] Pulse theme

  - [ ] The tabs appear to be consistent

- [ ] Mozilla theme

  - [ ] The sidebar tabs are correct

- [ ] Useragent

  - [ ] The user agent is reporting as Mozilla Firefox

- [ ] Vertical tabs

  - [ ] Vertical tabs can be enabled and disabled without a restart
  - [ ] Tabs can be rearranged

- [ ] Are all extensions up to date?
- [ ] Has `better-fox.js` been updated to the relevent version?
  - [ ] Have `user_pref`s been changed to `pref`?
