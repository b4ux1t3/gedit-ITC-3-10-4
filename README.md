This is just a simple fix of nymanjens' Intelligent Text Completion (ITC).

For installation instructions, see:
    https://github.com/nymanjens/gedit-intelligent-text-completion
    

My version simply removes the bracket completion, leaving everything else in. The reason for this is that the copy of Gedit that comes with Ubuntu 14.04, Gedit 3.10.4, has a built-in bracket completer, but does not automatically indent code blocks. When using both the stock ITC plgin and the built-in Bracket Completion, you get double ending brackets.

So, why not jst use ITC? Because it adds a closing bracket if you type it in, while Bracket Completion just skips the closing bracket if you type it. This way, if you forget to close a bracket, the bracket still gets closed, and if you don't forget to close the bracket, you don't get double closed brackets.

I'm working on a version of ITC that incorporates Bracket Completion's functionality, but it's buggy. For now, just give this a try!

-B4ux1t3
