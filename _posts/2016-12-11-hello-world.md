---
layout: "post"
title: "Hello World!"
date: "2016-12-11 11:42"
---

# Welcome to the amazing blog of Carl!

I'll start with a small rant on C++.  
I like C++ for the power it gives the user but there are many things wrong with it, like the syntax. It's so bad. Let's look at an example.

```cpp

//No .h extention because reasons?
#include <iostream>

// Only C++ standard libary lacks extentions
#include <someFileWithFunction.h>

int main() {

  // There are tree ways of declaring a variable.
  // Best part is that they all do it in difrrent ways.
  // Type 3 is the recomended way of doing it if you
  // have support for it. But why not change type 1 to
  // work like type 3?

  int type1 = 2;
  int type2(2);
  int type3{2};

  // No clue that this function is from
  // someFileWithFunction.h
  fileFunction();

  // Wtf is '<<' supposed to be?
  // Why not std::cout("Hello World!");
  std::cout << "Hello World!";
  return 0;
}
```

And what even is a header file? It's kindof like a summary of a class file. But shouldn't the complier be able to figure that out by itself?

Anyway, these are just my opinions based on my limited understanding of C++. There might be reasons for things being as they are and I'm just misinforemed.

**Thanks for reading <3**
