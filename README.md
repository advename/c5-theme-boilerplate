# c5-theme-boilerplate
A simple boilerplate to create a concrete5 theme.

Concrete5 theming tips:
- C5 has a build in LESS compiler. Use it to your adventage to have a build in CSS preprocesser in a C.M.S. (This boilerplate uses LESS too)
- Use class'es instead id's for blocks as it should be possible to re-use a block multiple times on a page (there can be exceptions)
- code in a way that you can insert block's wherever on a page and that it works out of the box (Some blocks can/may/should be page specific, such as don't be concerned with widget blocks which are not inserted inside a widget made area)
- If you see similar blocks, try to combine them into one generic block. This saves development time but also gives more controll to the user later on.

Notice:
Creating blocks later on in Concrete5 can be difficult. Therefore, it's recommended to use the (Block designer)[https://www.concrete5.org/marketplace/addons/block-designer] extension as it drastically simplifies the implementation of a block!
