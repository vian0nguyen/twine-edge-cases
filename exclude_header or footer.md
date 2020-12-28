# How to made a header/footer excluded by certain pages
1. Create header or footer passage (PassageHeader or PassageFooter)
1. Make a conditional on the special passage that looks something like this:

``<<if $clear==true>>
<<else>>
content to display
<<endif>>``

3. Go to all passages you want to exclude the special passage from
  `<<set $clear = true>>`
4. Don't forget in the "next" passage to set this variable back to `false`
