---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Password Generator"
date: 2022
published: true
labels:
  - Software dev
  - Python
  - C++
summary: "I developed a password generating application using python and kivy for the UI."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

Password generator is a program that helps clients to come up with strong passwords as per the requirements of most websites.


The passwords generated are different everytime and are longer than eight characters in length and contain upper case letters, lower case letters, digits and special charactors all generated randomly and occupying random positions within the string they appear in.

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
