---
layout: slide
title: Dictionary
description: An Intro to Python - Dictionary
transition: slide
permalink: /python-dictionary/
---
<section data-markdown>
    <textarea data-template>
       ## Dictionary
       A hash table
       * sequence of key-value pairs
       * efficient lookup & insertion
       * elements aren't ordered
       ---
       ## Dictionary
       ```sh
       >>> people = {"robert": 33, "john": 23, "steve": 44 }
       >>> people["robert"]
       33
       
       >>> people["janet"] = 25
       >>>
       ```
       ---
       ## Dictionary
       ```sh
       >>> del people["steve"]
       >>> people
       {"robert": 33, "john": 23, "janet": 25 }
       ]
       ```
       ---
       ## Dictionary
       ```sh
       >>> people.keys()
       ['robert', 'john', 'janet']
       ```
       > keys()
       
       ```sh
       >>> people.values()
       [33, 23, 25]
       ```
       > values()
       
       * items()
         * try it!
    ---
         ## Next:
         [Tuple](https://aisha-glblcd.github.io/material/python-tuple)
   </textarea>
</section> 
