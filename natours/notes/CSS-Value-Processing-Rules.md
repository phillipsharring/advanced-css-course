CSS Value Processing Rules

1. Each property has an initial value, used if nothing is declared (and if there is no inheritance)

2. Browsers specify a root font-size for each page (usually 16px)

3. Percentages and relative values are always converted to pixels

4. Percentages are measured relative to their parent's font-size, if used to specify font-size

5. Percentages are measured relative to their parent's width, if used to specify lengths

6. em are meatures relative to their parent font-size, if used to specify font-size

7. em are measured relative to the current font-size, if used to specify lengths

8. rem are always measured relative to the document's root font-size

9. vh and vw are simply precentage measurements of the viewport's height and width
