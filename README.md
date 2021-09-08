# Match-3

Match-3 assignment from CS50G

Original code [by Colton Ogden](https://cs50.harvard.edu/games/2018/projects/3/match/)

Assignment:

1. ~~Implement time addition on matches (+1 second per matched tile)~~
2. ~~Ensure Level 1 starts just with simple flat blocks, with later levels generating the blocks with patterns on them, which are worth more points~~
3. ~~Create random shiny versions of blocks that will destroy an entire row on match, granting points for each block in the row.~~
4. ~~Only allow swapping when it results in a match. If there are no matches available to perform, reset the board.~~
5. (Optional) Implement matching using the mouse. 


# Playing

Keys:

* *space* or *enter*: Select item or tile
* *left*, *right*, *up*, *down* arrows: Move selection cursor
* *escape*: Quit game


# Bugs and Todos

* Fixed a bug in some calls to `setColor` which still used values 0-255 instead of 0-1.


# Credits

* Most of this code was written [by Colton Ogden](https://cs50.harvard.edu/games/2018/projects/3/match/) for the [CS50G EdX course](https://learning.edx.org/course/course-v1:HarvardX+CS50G+Games/home)
* Using [boon](https://github.com/camchenry/boon) to package releases
