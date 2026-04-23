# Changelog

This document lists all notable changes to Elden Ring Cheat Sheets with each deployment.
Dates follow the ISO 8601 standard (YYYY-MM-DD).

## 2026-04-23

### Added
- East Scadu Altus, 77 walkthrough steps, 25 npc steps, and 1 boss step.
- Trophy emojis to mark all 42 achievement-earning steps in the Walkthrough (and also to the Bosses sheet to highlight all trophy bosses).
- New unfinished questlines: Count Ymir and Swordhand of Night Jolan.
- New merchant: Count Ymir.

### Changed
- Rewritten several steps in Limgrave to sound better.

## 2026-04-08

### Added
- Rauh Base, 88 walkthrough steps, 1npc step, and 3 boss steps.

## 2026-03-27

### Added
- West Scadu Altus, 97 walkthrough steps and 11 npc steps.
- New unfinished questline: Dryleaf Dane.

## 2026-03-17

### Added
- Ellac River.
- Cerulean Coast.
- Charo's Hidden Grave.
- Castle Ensis.
- New unfinished questline: Ancient Dragon Florissax.
- Added Ghostflame Breath spell to the Merchants sheet.
- Added Rellana's remembrance and its items to the Resources, Merchants, and NG+ sheets.

### Changed
- Split the Cathedral of Dragon Communion step in the base game Walkthrough into three easier-to-follow steps.

## 2026-03-06

### Added
- Belurat, Tower Settlement.
- New unfinished questlines: Hornsent Grandam, Fire Knight Queelign.
- New unfinished resource table for DLC remembrances.
- New missable in Hornsent's questline.
- Remembrance of the Dancing Lion added to NG+ sheet.

### Changed
- Updated some of the uncertain questline steps in Gravesite Plain that had question marks now that I've completed some testing.

## 2026-03-04

### Added
- East Gravesite Plain.
- Thiollier's inventory to the Merchants sheet.

## 2026-02-26

### Fixed
- Missable tag on the FAQ page not showing when hovered.

### Added
- Extensively tested and added tooltip explanations for all MISSABLE tags. These can be viewed when hovered over.
- New Show/Hide info button on sheets with lists of items. With the addition of many MISSABLE tags and item descriptions, the UI can get cluttered on smaller sizes. The Hide info button hides all MISSABLE tags and item location descriptions for a cleaner UI.
- New missable tags to many steps that I hadn't tested properly before due to requiring specific conditions in a playthrough.
- Two new steps to Leyndell, Royal Capital in the walkthrough for farming the Duelist and Guardian missable items. These items have also gotten descriptions on the Weapons and Armor sheets.
- New optional step added to Varre's questline and the walkthroughs.
- New note about missable Info item "About Invasion Multiplayer" and how to obtain it.
- Added Dark Moon Ring as a secondary condition to make Blaidd spawn outside Ranni's Rise.
- Added a reminder step during the Mountaintops to remind the player to finish Rya's questline once Rykard has been defeated.
- Updated missables in Yura's questline, made the first step in his questline required, and tagged killing Agheel as optional.
- With the updates to missable tags, some items in the list-style sheets (Weapons, Armor, Spells, etc.) now have text describing how it can be obtained. With time, all items will have descriptions, but I'll most likely keep adding missable ones over time, then add the rest once the DLC Walkthrough is finished.
- Various other changes like removing incorrect Optional and Missable tags, as well as updates to existing Missables too many to name here.

### Changed
- Rewritten Diallos's step in Liurnia to make it a lot easier to find him in Academy Gate Town.

## 2026-02-10

### Breaking Changes!
- Large rewrite of profile logic. If you were previously on your own created profile, you may have to manually switch back. Make sure to create a new backup, and consider deleting your old ones since they might be invalid.
- If you lost your progress due to the rewrite, you can now click the section totals (e.g. Tutorial [0/14]) to quickly complete entire sections at a time.
- Split the Legendary Equipment checklist on the Achievements sheet into separate sections. You may need to recheck several items you had already completed.

### Fixed
- Mobile users can now benefit from back/forward-caching. All pages will now correctly restore visual checkbox, collapse states, profiles, and color themes when switching between pages (previously worked around by forcing a full page refresh on each load).
- Checkbox-related keyboard shortcuts "/" and "h" can no longer be used on pages without checkboxes.
- Closing the sidebar on mobile would trigger a background color in the navbar to linger until tapped away.

### Added
- All section progress numbers are now CLICKABLE BUTTONS! Clicking them will check all unchecked checkboxes in that section, or uncheck them if a section is "DONE".
- MISSABLE tags can now be hovered over to see why they're missable. For users on mobile, simply tapping on the tag will toggle its visibility. I am still in the process of writing these, so it could be some time until they all have explanations.
- Table of contents can now be collapsed for returning users. The preference is stored and synced across all pages, meaning collapsing it on one page will collapse it everywhere else.
- New Talismans sheet with all talismans in the base game and DLC.
- New content in the Miscellaneous Items, Key Items, and New Game Plus sheets (will receive more updates after the DLC is written).
- All steps and items related to the DLC are now marked with "SOTE".
- Collapsed checklists and color theme now sync across multiple open tabs, no longer requiring a page reload.
- New "System" color theme option applies light or dark mode automatically based on your operating system's theme.
- New keyboard shortcut "t" will click the to-top button for you, moving you to the top of the page.
- Now uses the "Inter" variable font for all users instead of using the default system fonts, which resulted in misaligned text and checkboxes all across platforms.
- Note to a Golden Rune [11] in Leyndell Catacombs that may be bugged and not show for all players.
- Note to the Endings section in the walkthrough that all endings can still be gotten without Miquella's Needle.
- Links to the DLC sheet where mentioned in the walkthrough.
- The Resources sheet now uses tabular numbers for tables.
- Improved wording of some sentences across various sheets.

#### Accessibility Features
- Added skip links to all pages for keyboard users that want to skip navigation links.
- Everything now scales with the browser's font size, whereas before users would have to manually zoom in/out.
- Screen readers should now announce the action of keyboard shortcuts.
- Keyboard users can now call the sidebar from any focused element with the "s" keybind and return where they were (no longer forces focus to the menu).

### Changed
- Keyboard shortcut "q" for toggling the sidebar has been replaced by the more obvious "s" for "Sheets" or "sidebar".
- The color theme now defaults to the user's system preference if not set on the Options page.
- Heavily modified the colors in both light and dark mode for better contrast and readability. Dark mode now has a warmer and less cool tone, but most importantly the progress numbers are now white instead of dark.
- Complete code refactor. Unnecessary code will no longer run unless needed so the website should feel slightly faster, at least on phones loading the Walkthrough sheet with Vodafone 3G.
- Reduced the amount of inline styles required to load the website, which should result in faster load for slower connections.
- Simplified the way the search bar filters checklists, so searching should feel quite a bit faster.
- Searching on the Walkthrough sheet specifically is now slightly delayed on purpose to prevent your phone from overheating (Eh, it's still fast).
- Text should now be a lot bigger on mobile than before. Similarly, text has been slightly increased on desktop for readability.
- DLC in the NG+ Prep section now links to the DLC sheet.
- Achievement links in the walkthrough now go to Eldenpedia instead of the Achievements sheet.
- Changed group password from "ERSHEET" to "ERSHEETS" to fit the new name.

### Removed
- "Hide checked steps" button no longer persists across page reload; you'll need to click it or use the "h" shortcut every time. This was done to prevent FOUC and potential confusion for returning users.
- Old or unused localStorage keys should be automatically cleaned up the next time you load the website, freeing up some used space.

## 2026-01-16

### Added
- All sorceries and incantations to the Spells sheet.
- All Spirit Ashes and Ashes of War to the Ashes sheet.
- Simplified lead text across pages

## 2026-01-12

### Added
- All remaining armor pieces.
- All chest pieces to the Armor sheet.
- All headgear pieces to the Armor sheet.

## 2026-01-09

### Added
- Sticky notes to multiple Walkthrough, NPC Walkthrough, Questline, Merchant, and New Game Plus sections.
- Night labels to night bosses in Bosses.
- All melee armaments to Weapons.
- All ranged weapons, catalysts, and shields to Weapons.

## 2026-01-07

### Added
- Scadutree Fragment and Revered Spirit Ash tables to Resources.

### Changed
- Moved Remembrance table out of Runes section in Resources.
- Text should be slightly denser for legibility.
- Light and dark mode should be much more readable and accessible to all users.
- Links to regular font weight to improve readability.
- Sidebar will should no longer extend past the viewport height on smaller screens.

### Fixed
- Missable tags to Margit, Draconic Tree Sentinel, and steps in Fia's questline.
- First column links in tables on the Resources sheet are no longer bold.
- Collapse buttons appearing too low on mobile.

### Removed
- Multiple duplicate links across all sheets.
- Optional tags in Diallos's and Yura's questline.
- Scrollbar styling.
- Purple and green links that cluttered readability.
- Half implemented colorblind support (may implement a proper solution later).

## 2026-01-03

### Changed
- Armaments sheet renamed to Weapons.
- Miscellaneous sheet renamed to Miscellaneous Items.

## 2026-01-01

### Changed
- Site name (Elden Ring Cheat Sheet: 100% Completion Guide & Checklists -> Elden Ring Cheat Sheets).
- Page descriptions and lead text below the title.

### Removed
- Site name from each individual page (Walkthrough - Elden Ring Cheat Sheet -> Walkthrough).

## 2025-12-29

### Added
- Parenthesis behind every painting reward.

### Changed
- Use stele as a more accurate term for the map pillars.
- Slightly increased space between steps.
- Slightly decreased sidebar width.

### Fixed
- Missing reference to Seluvis in Nepheli's questline.
- Blurry checkboxes.
- Inconsistent text and header size depending on device.

## 2025-12-28

### Added
- West Gravesite Plain (DLC Walkthrough, NPC Walkthrough, Questlines, Bosses).
- Moore's inventory (Merchants).
- DLC divider in each Current Progress section.

### Changed
- Shortened URL fragments (e.g. /questlines#ranni-the-witch -> /questlines#ranni).
- Corrected all sentences where camp and campsite were used interchangeably.

### Fixed
- Missing mention of the Questlines sheet in the FAQ.

Older changes are not listed here.
