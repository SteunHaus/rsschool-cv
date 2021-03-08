### Eudakimenka Pavel Aleksandrovich

**Tel.** +375447261591
**E-mail** pavel.evdokimenko@gmail.com

# Personal Information

* My personal goal is to fully study JS and to master my skills in full-stack development for further productive work.

* My personal great traits are stress-resistance and responsibility. My ability to quickly learn new material in any direction is sure essential, so I can catch up in any moment.

# Skills

* HTML & CSS
* JavaScript
* git
* bash

# Code Example

Example of the code below is checking, whether the two arguments given are anagrams of each other:

'''
  // write the function isAnagram
var isAnagram = function(test, original) {
  if (test.length != original.length || test.length < 1) return false;
  
  test = test.toLowerCase();
  original = original.toLowerCase();
  
  let x = 0;
  
  while (x < original.length) {
    if (test[0] == original[x]) {
      test = test.replace(test[0], '');
      original = original.replace(original[x], '');
      console.log(test + " || " + original);
      x = 0;
    } else x++;
    
  }
  
  if (test == original) return true;
  else return false;
  
};

'''

# Experience

# Education

* Cisco IT Essentials (Certificate)
* IamIT courses (HTML & CSS, JS, php, React, jQuery)\

# Languages

* Russian (Native)
* English
  1. Reading (B1)
  2. Speaking (B1)
