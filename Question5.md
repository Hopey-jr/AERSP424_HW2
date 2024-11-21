One of main issues that could occur would be that a new robot would try to pick up the tool between them as the first robot finished its tasks. If the original robot was then immediatly assigned to pick up the tools again, there would be nothing to pick up. Another option would be essentially the inverse of this where the orignal robot was able to pick up the tools back up first and the then the new robot would be stuck without any tools. 

One way to potentially fix this would be a time dependent check before any robot could pick up any tools, regardless of when it was assigned the task. After an x second wait, the robots would then check to see if the tools are available before picking them up. This would hopefully mediate any of the issues. 