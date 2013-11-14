nil
===

Natural interactive language

A mixture of ruby, bash and gawk scripting; NIL Natural Interactive Language provides a subshell for Gnu/Linux process automation.

More specifically, NIL interacts between the business process model and the Posix automated processes, through a DSL (Domain specific language) for automation. This suite of DSL commands are jargon-adopting the usual business ontology, serving as a layer to the more strict posix automation tools.

Morevoer, NIL is not a NLP (Natural language processing) complete parser. Otherwide, NIL interface is based on the paper «Natural language interface based on keyword extraction using AWK» (Prasad, 1987), uses a complete description of cases (commands) to actions, using a extended version of REGEX (Regular Expressions), mainly on Gawk. Although this adoption could be viewed as simplistic, Gawk pattern/action methdology and beyond, the powerful of regular expressions reasoning, provides a really simple and fast way to create, modify, and expand natural perceived commands. So in many cases, the user can adopt, build o reuse the well-known onliner solutions, as Gawk permits express patterns and actions in one or more lines.

Wrapping those commands, the user can test a ruby version, a subshell bash script version, and a Gawk REPL (read, evaluate, process loop) on a interactive way for patterns and actions. All about, can't afford the same
semantic precission as bnf parsers achieve, nor the same robustness as the real shells provide, but the NIL's subshell can certainly helps to keep in mind the automation word(s) could means for regular sized business.

Ie;

<code> nil>>  send group A invoices tonight </code>

Consolidadate group A mail list of invoices, generate their PDF's, attach to a template email and finally, send tonight at 00:00AM from the cloud server]

The philosophy of automation is really simple; Invest your time in the kind of things that a machine can't do as well: Create and expand views and actions for your business, and let and order the mechanical thoughs and actions, to the best purpose-suited posix machines. As simple as is.

And why a text captive user interface (CUI?). Well, on the next version, the user will get isolated NIL commands on the Bash Shell.


Steve.
