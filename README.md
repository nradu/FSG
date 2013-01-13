#About
Based on the well known semantic.gs by Tyler Tate, Flawless-Semantics shares many of semantic.gs goals and allows for:
* column, gutter widths and the number of columns to be set; 
* switching between pixel and percentage based layouts;
* responsive fixed alayouts,
all without any unsemantic .grid_x classes in your markup. 

Starting out as a project to address several issues that I had with semantic.gs, Flawless Semantics is no currently not compatible with that project, and I have decided to create its own repository. I will continue to contribute to semantic.gs and will work to get both of these aproaches compatible with each other.

Go check out the [live examples here](http://laughingwithu.github.com/flawless-semantics-grid/).

#Differences
The most notable difference is the fact that Flawless-Semantics uses a column - gutter - column approach rather than a gutter - column - gutter approach. This solves the nesting problems I was having with Semantic.gs and also the fact that the outer most gutters where half the width of the inner gutters.

Other differences include:
* mixin to create equal height columns;
* mixin to specify the width, min-width, and max-width of a container;
* modification of .column mixin to allow for an omega attribute;
* feature to allow for automatic rows and columns;
* borders and padding don't affect grid;
* removal of padding as an option to be used as a gutter // this may be added in the future though it won't be implemented in the same way that it is in semantic.gs;
* support for less only at this time but this may change in the future.

#Issues
If you spot any issues or have ideas for improvement, feel free to make an issue on github or fork this project on GitHub and then issue a pull request. 

#License
Licensed under Apache 2.0. // Note that this may change as I prefer the MIT licence, but have left it the same as semantic.gs for the time being.

#Created by
Flawless-Semantics was created by Sean Steindl and has been heavily influenced by a range of projects including Semantic.gs, Zen grids, Neat, Flawless, and Centage. I claim no expertise in css, less or any programing language for that matter as I am a lawyer by profession. However, I have run my own design business  for close to six years mainly to support the cost of being a student and am proficient in php, css, html. Anyway here is to learning new things and I hope to hear from you regarding this project. Sean

#Acknowledgements
The Semantic Grid System was built by [Tyler Tate](http://twitter.com/tylertate/) at [TwigKit](http://twigkit.com/) and has had various contributions by the persons listed [here](http://github.com/twigkit/semantic.gs/blob/master/changelog.md). For more see  [semantic.gs](http://github.com/twigkit/semantic.gs).
