CSS Positioning Schemes:

Normal Flow

    * default positioning scheme

    * Not floated

    * Not absolutely positioned

    * Elements laid out according to their source order

    Default

    position: relative


Floats

    * Element is removed from the normal flow
        shifted as far left or right as possible
        until it touches the edge of its containing box, or another floated element

    * Text and inline elements will wrap around the floated element

    * The container will not adjust its height to the element.
        usual solution is to use clearfixes which sucks

    float: left

    float: right


Absolute positioning

    * Element is removed from normal flow

    * No impact on surrounding content or elements

    * We use top, bottom, left & right to offset the element from its relatively positioned container

    position: absolute

    position: fixed

