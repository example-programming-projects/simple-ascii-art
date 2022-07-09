# simple-ascii-art

## Inputs
1. Shape: "square" | "diamond" | "triangle"
2. Size: int
3. Character: 1 character string

## Output
It should print the specified shape at the specified size with the specified character to the console

## Example IO

### Medium Star 

#### Inputs
1. square
2. 5
3. a

#### Output
```
aaaaa
aaaaa
aaaaa
aaaaa
aaaaa
```

Note: Square size = height = width

### Large Triangle

#### Inputs
1. triangle
2. 10
3. `*`

#### Output
```
         *
        ***
       *****
      *******
     *********
    ***********
   *************
  ***************
 *****************
*******************
```

Note: Triangle size = height

### small Diamond

#### Inputs
1. diamond
2. 3
3. b

#### Output
```
  b
 bbb
bbbbb
 bbb
  b
```

Node: Diamond size = side length;

## Notes:
1. Validate user input / the program shouldn't just fail if they enter bad input

## Ways to extend the program:
1. Add additional shapes
2. Add an option for whether or not to fill the shape in
3. Allow the user to print the output to a file
