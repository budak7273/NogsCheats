New "Trigger Building Construction" feature, hold Ctrl to Loop-Give items, fixed bug with Give buttons sometimes not appearing.




This update brought to you by Robb.
If you enjoy my work, please consider my [completely optional tip jar](https://ko-fi.com/robb4).

## New Stuff

- Can now trigger the construction of buildings you haven't unlocked yet
  - Buildings now show a hammer button in Quick Search and the codex
  - Clicking the hammer button will select the building for construction with your buildgun, even if you don't have the recipe unlocked yet
  - Doesn't give you the required materials, use the No Build Cost advanced game setting for that
  - It uses the first valid recipe it finds in game and mod files, so if clicking the button does nothing, there is no valid recipe.
- "Hold Ctrl to Loop-Give" added to Give buttons
  - This was partially already in the mod but undocumented and poorly visualized
  - Hold ctrl over a give button to, after a delay, continually give the item until you let go of ctrl
  - Gives in multiples of 1 at a time unless you're holding shift, then it gives in multiples of 1 stack
  - A progress bar will appear while you're holding ctrl to show you how long you need to hold it for
  - Tooltips updated to reflect this

## Changed Stuff

- General code cleanup

## Bugfixes

- Fixed that Give Item buttons would sometimes not appear correctly after reloading saves or rejoining a multiplayer session
