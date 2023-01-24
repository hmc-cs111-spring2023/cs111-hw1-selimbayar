# Language

_What is the name of the language? Link the name to its webpage
(if appropriate)._

The name of the language is BGD (BoardGameDescription). There is no official website for it but here is a link to a paper that describes it <https://essay.utwente.nl/79157/1/Schroten_BA_ewi.pdf> and here is a link for its GitHub <https://github.com/QWolf/BoardGameDescription/>

# Domain

_Describe the language's domain in five words._

Describe, record, replay board games

# Computational model

_We don't yet have a great definition of the term "computational model".
For now, try to come up with the clearest, most concise explanation of
what happens when a program in your DSL runs._

When a program runs in this DSL, a board game is expressed in a clear way and the entire rulebook of the game is captured by the BGD description of that game.
Then, it records the gameplay by tracking each move that is made.
Finally, those moves are re-playable to produce an exact copy of the match that was played to analyze how the game was won or lost.

# DSL-ness

_Fowler writes about a spectrum of languages, from general-purpose languages to
"purely" domain-specific. Where does the DSL you chose fall on this spectrum,
and why?_

I believe the DSL I chose falls in the middle of the spectrum, but closer to the domain-specific part. The task it aims and performs makes it a "pure" DSL; however, this syntax is very close to the syntax of Java, which was not originally intended, so that pulls it a little towards the general-purpose language side.  

# Internal or external?

_Is the language implemented as an internal or external DSL?
Justify your answer._

I believe the language implemented is an internal DSL, as it was intended to be a language for people with little to none programming experience could easily use, but it ended up somewhat of a less function-complete imitation of Java.
The syntax took inspiration in the Java syntax and shifted towards the general-purpose programming language.

# Host language

_What language(s) was (were) used to implement the DSL?_

Java was used to implement the DSL.

# Benefits

_Identify one potential benefit of the DSL: how is a programmer's life made
easier by the existence of this language?_

One potential benefit is that it can help create a program that masters any game it is given. To create a program that can master any given board game requires a way to fully describe that game, which this DSL can help with.
# Drawbacks

_Identify one potential drawback of the DSL: what does a programmer
lose by using this DSL instead of a general-purpose language?_

One potential drawback is that the descriptions are really long, and includes a lot of repetition which can make it harder to understand, inefficient, and can give it an ugly sight because there are some copy-pasted codes in it. 
