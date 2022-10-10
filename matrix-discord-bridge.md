**Why a matrix bridge is bad (for a public server)**

(yeet/yote are equivalent to ban or mute)

 - Yeet evasion is encouraged & easier than it already is.
   * Some people will join on both matrix/discord, get yote on one platform, then complain about the yeet on the other platform or just continue as normal there.  If you're yote on one side of the bridge, you're yote on both, end of story.
 - Yeeting matrix users if you're on discord will be a lot more tedious.
 - Selecting matrix users is harder.
   * You cannot right click -> copy ID.
   * You cannot use @​user autocomplete.
   * Left clicking a username opens a random webhook profile that doesn't change until the client is refreshed.  So compact mode users won't be able to view PFPs.
 - The best solution to the previous 3 points would be requiring a matrix account to be "registered" to their discord account before they are able to join the matrix.
   * This would, of course, be done by the bot.  I'm not sure how to confirm that the matrix account is actually theirs though.
   * After they are registered, the names (user or nick?) would be synced, and if one gets yote, they both get yote.  If the discord account manually leaves, the matrix account gets kicked.
   * But a valid counter-argument to this is that matrixers won't be able to actually de-discord.  And if you don't like this solution, give a better one.
 - Usernames will be needlessly long.
   * Best case, it will be `[BOT] user`
   * Worst case, it will be `[BOT] user:instance.com` (Yes, you can join from other matrix instances, that's like the whole point of matrix)
   * (Instead of just `user`)
   * This makes a significantly bigger difference on compact mode, where usernames are prefixed to the message, instead of being above a message group.
 - You can't block a matrix user if you use discord!
 - Syncing message deletions/edits is annoying.
   * Editing messages on matrix reposts them on discord.
   * Deleting a webhook message doesn't show in the audit log.
