> Notes on writing Maintainable CSS. source: [maintablecss.com](https://maintainablecss.com/)  

#MaintainableCSS

**Short Summary**

Maintainable CSS is an approach to writing modular, scalable and maintainable CSS. 

The CSS code that we write must be modular, scalable and maintainble.

The convention is to make use of module-component-state.

Keep in mind that module consists of components not the other way around.

If two modules are similar don't reuse but create unique modules. This way the css is maintable. 

ex. For the navigation element on a site the module would be .navigation and then the logo component would be .navigation-logo and finally is comes the state, if the state for this module is to be hidden the class would be .navigation-hidden. 

