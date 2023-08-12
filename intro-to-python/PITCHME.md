---
layout: slide
title: Introduction to Python
description: An Intro to Python
transition: slide
permalink: /intro-to-python/
---
<section data-markdown>
    <textarea data-template>
      ## Python
      ##### Global Code | 2023
        
      ![Python](../assets/img/python-360x361.png)

      ---

      ## What is Python?
        * A programming language!
        * Built-in data types
        * Control flow
        * Modules
        * Loads of open-source (free!) code you can use

        ---

        ## Hello, Python!
        ```python
        x = 1
        if x == 1:
            # indented four spaces
            print ("x is 1.")
        ```
        > hello.py
        
        ---
        
        ## Hello, Python!
        Can be executed from a file:
        ```sh
        $ python hello.py
        x is 1
        ```
        ---
        
        ## Hello, Python!
        Or interpreted using the REPL:
        ```sh
        $ python
        >>> print ("hello, Python!")
        hello, Python!

        ---
        
        ```
        Useful for experimenting. Try it!
        
        ---
        
        ## Hello, Python!
        Or using UNIX's shebang syntax:
        ```python
        #!/usr/bin/python
        
        print ("hello from Python!")
        ```
        > hello.py
        
        ```sh
        $ chmod +x hello.py
        $ ./hello.py
        ```
        
   </textarea>
</section>











