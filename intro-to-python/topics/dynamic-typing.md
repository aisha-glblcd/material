---
layout: slide
title: Dynamic Typing
description: An Intro to Python - Dynamic Typing
transition: slide
permalink: /python-dynamic-typing/
---
<section data-markdown>
    <textarea data-template>
        ## Dynamic typing
        * The *type* of a variable is determined at runtime
        * Not compile time
        * What's the difference?
        ---
        ## Dynamic typing
        * Useful for writing code quickly
        * Fewer compiler errors
        * Where do the errors go?
        ---
        ## Dynamic typing
        Sometimes they go nowhere:
        ```sh
        >>> print (names)
        ['John', 'Paul', 'George', 3]
        ```
        ---
        ## Dynamic typing
        Sometimes things break:
        ```sh
        >>> len(3)
        Traceback (most recent call last):
          File "<stdin>", line 1, in <module>
        TypeError: object of type 'int' has no len()
        ```
        ---
        ## Next:
        [Dictionary](https://aisha-glblcd.github.io/material/python-dictionary/)
      
      </textarea>
</section>
