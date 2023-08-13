---
layout: slide
title: Loops
description: An Intro to Python -Loops
transition: slide
permalink: /python-loops/
---
<section data-markdown>
    <textarea data-template>
        ## Loops
        ```python
        names = ["John", "Paul", "George", "Ringo"]
        for beatle in names:
            print (beatle)
        ```
            John
            Paul
            George
            Ringo
        ---
        ## Loops
        Also tuples:
        ```python
        hostport = ("accdev1", 3213)
        for item in hostport:
            print (item)
        ```
            "accdev1"  3213
        * "," supresses the newline!
        ---
        ## Loops
        * nested *control flow statements*
        
        ```python
        names = ["John", "Paul", "George", "Ringo"]
        for beatle in names:
            if len(beatle) > 4:
                print (beatle)
        ```
        Output:

        ```python
            George Ringo
        ```
        ---
        ## Loops
        `while` loops until condition returns false
        ```python
        num = 0
        while num < 5:
            num = num + 1 
            print (num)
        ```
            1 2 3 4 5
        ---
        ## Next:
        [Functions](https://aisha-glblcd.github.io/material/python-functions)

   </textarea>
</section>
