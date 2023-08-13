---
layout: slide
title: Hello Python
description: Hello Python
transition: slide
permalink: /python-hello-python/
---
<section data-markdown>
    <textarea data-template>
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
        ---
        ## Next
        [Data Types](https://aisha-glblcd.github.io/material/python-data-types/)
 </textarea>
</section>
