CSS Inheritance

every css property must have a value

is there a cascaded value
    yes -> specified value = cascaded value
    no v

is the property inherited (specific to each property)
    yes -> specified value = computed value of parent element (this is inheritance)
    no -> specified value becomes initial value (specific to each property)


1. Inheritance passed the values for some specific properties from parents to children - more maintainable code

2. Properties related to text are inherited: font-family, font-size, color, etc.

3. The computed value of a property is what gets inherited, not the declared value.

4. Inheritance of a property only works if no one declares a value for that property.

5. The inherit keywork forces inheritance on a certain property

6. The initial keyword resets a property to its initial value

