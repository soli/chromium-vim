#cVim Changelog

## 1.2.51
 * cVimrc setting are more strict (must use 'let' instead of set when using options requiring an equal symbol)
 * Lots of bug fixes

## 1.2.50
 * ```map``` automatically unmaps the existing binding if a conflict occurs (e.g. same key mapped to multiple functions). ```unmap``` is no longer necessary unless you wish to disable a default mapping
 * ```map``` can now point to other mappings as a reference (e.g. ```map j k```)
 * Improved mapping key compatibility
 * Minor CSS tweaks in the options page

## 1.2.49
 * Reworked domain blacklists engine. See https://developer.chrome.com/extensions/match_patterns for a description of the new URL match syntax
 * Fixed some iframe bugs

## 1.2.48
 * Fixed an issue where quickmarks wouldn't save
 * Minor bugfixes
 * Added basic support for Visual Line mode (V)
 * Updated DuckDuckGo search engine for completion
 * Added a restart chrome shortcut (zr). The same could be accomplished with the config ```map zr :chrome://restart&<CR>```
 * reloadAllTabs is still available for mapping, but the key binding ```cr``` now defaults to reloadAllButCurrent

## 1.2.47
 * Several bugfixes
 * Added reloadAllTabs (cr), toggleImages (ci), zoomPageIn (zi), zoomPageOut (zo), zoomOrig (z0), zoomImage (z&lt;Enter&gt;), and toggleCvim (&lt;C-z&gt;) mappings

## 1.2.46
 * Fixed a bug where bookmarks would be displayed multiple times on some sites

## 1.2.45
 * Fixed a CSS issue with the default font (if your font looks ugly, reset cVim to see changes).

## 1.2.44
 * Tiny bugfix

## 1.2.43
 * Added this changelog
 * Minor bugfixes
 * Fixed conflicting CSS styles
