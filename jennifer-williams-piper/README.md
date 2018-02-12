##### How did you determine which rules should be placed in each new CSS file?

I made my best guess based on the SMACSS reading. Most of the rules went into modules.css. I also used the question: if this were a multi-page site, would this rule apply to all pages? Rules that would apply universally to all pages, I put in base.css. Rules that seemed layout-specific, having to do with the size and placement of large blocks on the page, I put in layout.css.  There were some that I could justify putting in either of two places, so I just made an intuitive choice and called it good, since we were instructed not to agonize over these choices. 

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I didn't. I thought about trying to use the naming convention of adding 'l-' to the start of layout rules, but realized that all my layout rules apply to html tags, not classes or ids. And I can't very well change the name of an html tag. I think I will make use of this naming convention when we have more complex projects with more classes and ids.
