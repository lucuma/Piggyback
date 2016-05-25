# PiggyBack #

![You gotta WORK, WORK, WORK, WORK, WORK, WORK!](https://media.giphy.com/media/xYFyobamFyqfS/giphy.gif "You gotta WORK, WORK, WORK, WORK, WORK, WORK!")

PiggyBack is a simple CSS Framework (Sass based).
Created by Mariella Miranda at Lúcuma Labs's Evil Lair.

It has (in this version) a basic responsive grid, normalize as CSS base, and typographic settings.

### Basic Sass, very sassy ###

* You can find: A responsive grid, CSS normalize and typographic settings.
* Version 1.0

### How do I get set up? ###

* Super easy, just download it. It contains the scss files if you want to modify. The main.css has everything inside.

### Who do I talk to? ###

* You can contact me (Maku) or open a Ticket.

# Now, tell me more about the framework, work, work! #

Let's see what you can do right away with this little and convenient framework.

## Responsive Grid ##

As you've been told before, this is a 12 columns responsive grid. It's inspired by Bootstrap, but I needed it not to have paddings, so it works with margins instead.

This is how they work.

Screen Size         | Column Name | Gutter Size | Column Size    
------------------- | ----------- | ----------- | --------------
**1220px and up**   | col-#       | 20px        | 83.333px aprox 
                    | col-xl-#    | 20px        | 83.333px aprox 
**980px to 1219px** | col-#       | 20px        | 63.333px aprox 
                    | col-l-#     | 20px        | 63.333px aprox 
**740px to 979px**  | col-#       | 20px        | 43.333px aprox 
                    | col-m-#     | 20px        | 43.333px aprox 
**490px to 739px**  | col-#       | 10px        | 31.666px aprox 
                    | col-s-#     | 10px        | 31.666px aprox 
**489px and down**  | col-#       | 2%          | 98% 
                    | col-xs-#    | 2%          | 6.333% 

* Every "normal" column (col-#) works on every breakpoint. And gets assigned size and gutter indicated in the table above.
* Every "special" named column (col-xl-#, col-l-#, col-m-#, col-s-# and col-xs-#) works only in their specific breakpoint.
* Columns in all breakpoints are pixel-sized, except in 489px and down (XS breakpoint), which are percentage-sized.


:license: MIT, see LICENSE for more details.
