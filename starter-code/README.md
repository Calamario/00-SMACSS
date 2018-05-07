##### How did you determine which rules should be placed in each new CSS file?

Putting the body and other * css into base.css was given. For layout and modules, I decided to split them up if the css selector needed children selectors. (ie, nav ul). If they needed more than one selector, I placed them in the module. There also a few that didn't have anything to do with the layout of the page to module.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I did not. I was unsure whether to refractor. I thought it was more readable if the css on the element was all in one css file rather than split up. But thinking back, seems like refactoring just the margin or just the layout dependent might be helpful. 
