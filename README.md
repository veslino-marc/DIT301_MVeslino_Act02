1. What did you observe about the app lifecycle when switching between screens or minimizing the app?
   I observed that the app doesn’t completely close when I switch screens or minimize it. Instead, the activity goes through different states like paused or stopped, and when I return, it can resume from where I left off.

2. What did you learn about activity management in Android?
   I learned that Android manages activities using a stack system. The current screen is on top of the stack, and when I open a new screen, it gets added on top. If I press back, the top activity is removed, and the previous one shows up again. This makes it easier to handle navigation between screens.
