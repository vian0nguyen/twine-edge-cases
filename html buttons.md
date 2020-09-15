in sugarcube if you want to change the size of the button make sure to include "data-passage" and set it equal to the passage you want the button to go to.

    <button data-passage="page2" type= "button">[[next page|page2]]</button>

if you want a setter to work you need "data-setter" and set it equal to the variable you're setting. The multi setter rule applies here too.

    <button data-passage="page2" data-setter="$POL to $POL+10, $ACA to $ACA+10"  type= "button">[[next page|page2]]</button>
