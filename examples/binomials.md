```julia

julia> for x in 1:5
           for y in 1:x
               print(y + binomial(x,2), " ")
           end
           println()
       end
1
2 3
4 5 6
7 8 9 10
11 12 13 14 15

julia> for x in 1:5
           for y in 1:x
               print(binomial(x-1,y-1), " ")
           end
           println()
       end
1
1 1
1 2 1
1 3 3 1
1 4 6 4 1

```
