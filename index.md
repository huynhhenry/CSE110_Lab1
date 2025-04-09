# Hello! I'm Henry 

Welcome to my GitHub Page. 
---
[Visit my GitHub Profile](https://github.com/huynhhenry)
[Favorite Algorithm](#about-me-as-a-programmer)
[My VS Code screenshot](/screeenshots/VSCode_UI.png)

## About Me as a Programmer

- I'm currently learning JavaScript for this quarter.
- I have worked with the Hypixel API

> *"You need a little bit of rain to have a little bit of rainbow."*  
> – Félix Lengyel

### Languages I Speak:
- English
- Vietnamese
- Spanish (Very Basic Level)

### Top 2 Priorities This Quarter:
1. Build a cool website project
2. Learn Git fluently

## Favorite Algorithm
```c
// I recently learned about this Fast Inverse Square Root Algorithm
float Q_rsqrt( float number )
{
    long i;
    float x2, y;
    const float threehalfs = 1.5F;

    x2 = number * 0.5F;
    y  = number;
    i  = * ( long * ) &y;                     // evil floating point bit hack
    i  = 0x5f3759df - ( i >> 1 );             // what the 
    y  = * ( float * ) &i;
    y  = y * ( threehalfs - ( x2 * y * y ) ); // 1st iteration
//  y  = y * ( threehalfs - ( x2 * y * y ) ); // 2nd iteration, can be removed

    return y;
}
```

### Goals

- [x] Learn Basic Markdown
- [x] Relearn Basic Git
- [ ] Finish Lab 1
