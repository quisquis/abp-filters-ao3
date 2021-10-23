# abp-filters-ao3
Block tags on Archive of Our Own using an ad blocker (like Adblock Plus / uBlock Origin / etc.)

## Filters
**Block a work if a tag contains a keyword:**

archiveofourown.org#?#li.group:-abp-has(li:-abp-contains(/First Tag|Second Tag|Third Tag/))

**Block a work if a tag has an exact match:**

archiveofourown.org#?#li.group:-abp-has(a[href*="/First%20Tag/" i], a[href*="/Second%20Tag/" i], a[href*="/Third%20Tag/" i])

## References
* [How to create your own adblock list — For dummies](https://sproutsluckycorner.wordpress.com/2018/07/21/how-to-create-your-own-adblock-list-for-dummies/)
  * filter lists on GitHub
* [How to create your own personal filter list](https://help.getadblock.com/support/solutions/articles/6000165012-how-to-create-your-own-personal-filter-list)
  * filter lists on Google Drive
* [Adblock Plus filters explained](https://adblockplus.org/filter-cheatsheet)
  * filter rules cheatsheet
* [How to write filters](https://help.eyeo.com/adblockplus/how-to-write-filters)
  * another filter rules guide
### Other Sources
* [Hide tumblr posts (using Adblock Plus)](https://admung.tumblr.com/post/83797567505/hiding-on-tumblr)
  * the inspiration for this
* [CSS Tutorial](https://www.w3schools.com/css/)
  * knowing CSS is helpful if you want to know how the filters work
* [AO3's Unofficial Browser Tools FAQ](https://archiveofourown.org/faq/unofficial-browser-tools?language_id=en#modifysearch)
  * other options for tag blocking
