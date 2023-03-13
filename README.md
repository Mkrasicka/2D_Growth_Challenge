# 2D_Growth_Challenge
Start with an infinite two dimensional grid filled with zeros, indexed from (1,1) at the bottom left corner with coordinates increasing toward the top and right. Given a series of coordinates (r,c) where r is the ending row and c is the ending column, add 1 to each element in the range from (1,1) to (r,c) inclusive. Once all coordinates are processed, determine how many cells contain the maximal value in the grid.

Example: upRight = ["1 4", "2 3", "4 1"]

The two space-separated integers within each string represent r and c respectively. The diagrams the attached images show each iteration starting at zero. The maximal value in the grid is 3, and there is 1 occurence at cell (1,1).

grid image 1

grid image 2

Complete a function countMax to return the number of occurrences of teh final grid's maximal element. countMax has the following parameter(s): string upRight[n]: an array of strings made of two space-seperated integers, r and c.
