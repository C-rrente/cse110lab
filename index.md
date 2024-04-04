theme: jekyll-theme-minimal

# I am Logan 

![Image of Logan Corrente from Linkedin](https://media.licdn.com/dms/image/C5603AQFWRp3G5Iu92A/profile-displayphoto-shrink_800_800/0/1650402655338?e=1717632000&v=beta&t=66oSWCAG3hes_FP7hMdApp3aHoUlVJcKWyy7XeqvT50)


## About me 

I am currently studying Mathematics-Computer Science at the *University of California, San Diego*
> I mostly enjoy computing and electronics, math is fun but quite painful at times

Of all the code I've seen, here is my favorite chunk of code:

```
float Q_rsqrt(float number)
{
  long i;
  float x2, y;
  const float threehalfs = 1.5F;

  x2 = number * 0.5F;
  y  = number;
  i  = * ( long * ) &y;                       // evil floating point bit level hacking
  i  = 0x5f3759df - ( i >> 1 );               // what the ****?
  y  = * ( float * ) &i;
  y  = y * ( threehalfs - ( x2 * y * y ) );   // 1st iteration
  // y  = y * ( threehalfs - ( x2 * y * y ) );   // 2nd iteration, this can be removed

  return y;
}
```

This code is from Quake and is a function that computes the inverse square root. I enjoy game development and often awe at the insane ways programmers solve problems, especially when those problems are virtual.
> [Inverse Square Root Wiki](https://en.wikipedia.org/wiki/Fast_inverse_square_root)

[Here, I provide some insight on my academic journey](school.md)

## Favorite Subjects

- Computer Science
- Game Design
- Graph Theory
- Math
- All sciences

## Favorite Programming Languages

1. C++
2. Python
3. C#
4. C

## Goals for this course 

- [ ]  Finish tasks on time
- [ ]  Contribute well to team
- [ ]  Stay organized