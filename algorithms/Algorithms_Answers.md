Add your answers to the Algorithms exercises here.

1a) O(n)

1b) O(n3) ~ O(n2.5)?

1c) O(1)

2) I would want to devise a solution that includes dropping the egg initially from half the max height, and then continuing up or down from that level. (if the egg breaks move half the remaining height down, and redrop, etc. & if not move half the remaining height up, etc.) Repeat halving the remaining distance in whatever direction until correct height/floor is found.