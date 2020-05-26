# Flutter_Arrays
How to work with 1D and 2D Arrays in Flutter

# 1D Array

Here's an example of an array using numbers:
```ruby
  static var vLevels = [0, 4, 15, 37, 42, 55, 68, 81, 86, 98, 103, 116, 121, 134, 147, 160, 165, 178, 183, 196, 201, 214, 227, 240, 245, 250, 255, 260];
```

Here's an example of an array using letters:
```ruby
  static var vGrades = ['PreK', 'K', '1st', '2nd', '3rd', '4th', '5th', '6th', '7th', '8th', '9th', '10th', '11th', '12th'];
```


Calling a 1D Array value:
```ruby
  vMax = Home.vLevels[1]; // This will return 4, the second item in the array. 
  vGrade = Home.vGrades[3]; // This will return 2nd, the fourth item in the array.
```

# 2D Array

Here's an example of an 2D array using both letters and numbers:
```ruby
  static var vData = ([
    [("Airplane"), ("Airplane.jpg"), ("Airplane.wav"), (1)],
    [("Alphabet"), ("Alphabet.jpg"), ("Alphabet.wav"), (1)],
    [("Answer"), ("Answer.jpg"), ("Answer.wav"), (1)],
    [("Zipper"), ("Zipper.jpg"), ("Zipper.wav"), (27)],
    [("Zoo"), ("Zoo.jpg"), ("Zoo.wav"), (27)],
  ]);
```

For some reason, it was necessary to put each element into parentheses (). You can either use the single or double quote. I used double in this example because some of my words contained apostrophies.

Calling a 2D Array value:
```ruby
  vSound = Home.vData[0][2]; // This will return Airplane.wav.
  vWord =  Home.vData[0][0]; // This will return Airplane. 
```
# Notes
I used "static" so my variable would be accesible throughout my code. My variables were housed in a module called "Home", so you'll note that they are called with Home.variablename.
