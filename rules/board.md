## The game board

Play takes place on a grid, with the edges of rooms drawn onto it. Heroes and monsters largely occupy one square
at a time, and most actions can only be taken against units in 'line of sight', and also within a specified 'range'
of the source of the ability.

Line of Sight is determined thusly: if a straight line can be drawn through some point on the source square and
the destination square that does not pass *through* a wall or an opponent (of the source), then LoS exists. Nicking
the corner of an obstruction does not block LoS, and allies do not block LoS.

For two squares to be 'adjacent', they must share an edge.
