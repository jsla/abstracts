# Sandboxing Untrusted Code in Node.js
## Joe Rozner
### Joe is on [github](https://github.com/jrozner/) and [twitter](https://twitter.com/jrozner)

Running untrusted code is always a difficult problem to deal with. This talk
will explore some of the potential problems with result from doing this
including: resource starvation, data security, remote code execution, and
unintended network access. It will then explore some of the design decisions
of Node.JS and show how these can be used to help control provide methods to
sandbox code to prevent these types of attacks, ending with an explanation of
some of the limitations of this technique and possible other solutions.

