

1. Steps I took to create and manage branches?

By default when I created the git repo I started on the main branch, but from there, I created the feature branches using “git checkout \-b feature/something”. I used the command  to create the branches and switch to them in one go. For existing branches I would switch to a branch using   
“git switch branch-name”. A challenge I found  when creating branches was I had to keep in mind all the feature branches had to start in the main branch. When you create branches you can end up carrying over changes you didn’t want. I always made sure to check what branch I was in.

2. How I handled merge conflict?

The way I handled the merge conflict was by checking the current code against the change  
I was initially merging. When I combine those two pieces  do they make sense together or does one fit the code better? Is a small edit all I need?. Those were questions I would ask. So in my case, to resolve my merge conflict between the footer tags “The Crab Collective” and “The Turtle Collective” I just combined the text into one footer tag “Turtle and Crab Collective”.

3. How the pull request process helped to ensure code quality and collaboration?  
   

I found the pull request to be useful because it gives your colleagues a chance to look over your work. There is always at least something you didn’t think about when committing a change.  This is something a senior developer would use to provide feedback. Or a tool for people who like to add features to an open-source project. In big projects that allow for pull requests the main team is too busy to implement a feature you need.  Rather than wait, you can add it yourself as a pull request.