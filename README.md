# abp-filters-ao3
Block tags on Archive of Our Own using an ad blocker (like Adblock Plus / uBlock Origin / etc.)

## Filters
**Block a work if a tag contains a keyword:**

`archiveofourown.org#?#li.group:-abp-has(li:-abp-contains(/First Tag|Second Tag|Third Tag/))`

**Block a work if a tag has an exact match:**

`archiveofourown.org#?#li.group:-abp-has(a[href*="/First%20Tag/" i], a[href*="/Second%20Tag/" i], a[href*="/Third%20Tag/" i])`



(Check out the [Wiki](https://github.com/quisquis/abp-filters-ao3/wiki) section for more details.)
