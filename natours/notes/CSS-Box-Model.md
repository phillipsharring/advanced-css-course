CSS Box Model

width, height, padding, margins & border

* Content:  text, images, etc.

* Padding:  transparent area around the content, inside of the box

* Border:  goes around the padding and the content

* Margin:  transparent area around the border - space between boxes

* Fill area:  area that gets filled in with background color or background image


Total width = right border + right padding + specified width + left padding + left border

Total height = top border + top padding + specified height + bottom padding + bottom border


Box sizing: border box

Total width = specified width

Total height = specified height


Box types (display property):


    block: (display: block, flex, list-item, table)

        * Elements formatted visually as blocks

        * 100% of parent's width

        * Vertically, one after another

        * Box-model applies as shown


    inline (display: inline)

        * Content is distributed in lines

        * Occupies only content's space

        * No line-breaks

        * No height and widths

        * Paddings and margins only horizontal (left and right)


    inline-block (display: inline-block) - work as a block level block on the inside

        * A mix of block and inline

        * Occupies only content's space

        * No line breaks

        * Box model applies as shown

