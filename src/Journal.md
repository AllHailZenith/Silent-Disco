Phase 1
I used setInterval() to change the panel colors every 1.5 seconds. I used random numbers to generate RGB colors. Keeping a consistent interval makes the lights change regularly.

Phase 2
Event bubbling happens when a click on an element also triggers events on its parent elements. I used stopPropagation() so clicking the dancer changes the emoji without changing the dance floor color.

Phase 3
A global keyboard listener works even when I am not clicking a specific element. Holding a key down can trigger the event multiple times, which may cause the dancer to change moves repeatedly.
