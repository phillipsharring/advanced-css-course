CSS Importance

1. User !important declarations
2. Author !important declarations
3. Author declarations
4. User declarations
5. Default browser declarations

Specificity

1. Inline styles
2. IDs
3. Classes, pseudo-classes, attribte
4. Elements, pseudo-elements

Factored as a specificity value:
Inline, IDs, Classes, Elements
(0, 0, 0, 0)
(0, 1, 2, 2)
(0, 0, 0, 1)
(0, 1, 2, 1)

Cascaded value

Source order
Last declaration in code will override all other declarations and will be applied.

CSS declarations w/ !important have the highest priority
Only use !important as a last resource. It's better to use correct specificities = more maintainable code
Inline styles in HTML will always have priority over styles in externals stylesheets, but this is not good practice
A selector that contains 1 ID is more specific than one w/ 1000 classes
A selector that contains 1 class is more specific than one w/ 1000 elements
The universal selector * has no specificty value (0, 0, 0, 0)
Rely more on specificity than on the order of selectors
But ely on order when using 3rd-party stylesheets. Always put your author stylesheet last
