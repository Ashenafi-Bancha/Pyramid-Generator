# Pyramid-Generator
 
This JavaScript program generates a pyramid pattern based on the specified configuration. The pyramid can be either normal or inverted, depending on the `inverted` flag.

## Features
- Uses the `#` character to form the pyramid.
- Supports both normal and inverted pyramid structures.
- Adjustable pyramid height using the `count` variable.

## How It Works
1. The `padRow` function generates each row of the pyramid by adding spaces and characters accordingly.
2. A loop constructs the pyramid, either adding rows from the top (`unshift` for inverted) or from the bottom (`push` for normal).
3. The final pyramid is stored as a string and printed to the console.

## Usage
Modify the following variables to customize the pyramid:
- `const character = "#";` → Change the pyramid character.
- `const count = 8;` → Adjust the height of the pyramid.
- `let inverted = true;` → Set `true` for an inverted pyramid or `false` for a normal one.

## Example Output
### Normal Pyramid (`inverted = false`)
    
    #       
   ###      
  #####     
 #######
#########
   
