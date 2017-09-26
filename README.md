# active-defense
Ideas, code snippets, links, etc related to actively defending applications (particularly web apps), and deceptive programming.  This idea
was born out of my DerbyCon 2017 talk, and some great post-talk feedback I received.

I don't claim to be a pioneer in this area, or to have invented it.  The idea hit me during an internal web application test, when a tool I was using failed with odd results.  Turns out, the tool in question was unable to parse a server-side redirect from a default.aspx webpage to the actual starting page.  

So I thought, how can I undermine an attacker in the reconnaissance phase?  If an attacker gets false/misleading data early on, logic suggests this would taint the entire attack process, rendering an attack much less effective.  

Open an issue for ideas, suggestions, etc.  I'm happy to give credit! :)
