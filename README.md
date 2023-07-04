# SICP Completion


I am going to be going through the Structure and Interpretation Of Computer Programs from MIT. This is so I can get a better understanding of the said title, as well as refresh my
memory of functional programming languages.

My only prior experience in functional programming languages has been Erlang, so playing with Lisp should be an interesting experience.

Using Racket to test code/do exercises

Expressions: 
	- As in mathematics
	- Book uses examples of addition and subtraction using polish notation (e.g. (+ 1 3))
	
define: This keyword defines variable

E.G:
(define fred 2)

You use defines as you'd imagine with any other language

Compound Procedures: 
	- Nesting combinations to join together multiple expressions to a net result
	- Basically a function as in other languages
	
	E.G.
	(define (square x)    (* x x))
	   ^func  ^name ^param  ^expression(s)

The book defines it as:
	(define (*name* *formal parameters*)
*body*)

These can be called by going (*name* *params*), including inside other procedures


Conditionals:
	- defined by cond 
	- Same notation as other expressions, just logical expressions (> x 4) 
	- = is =, unlike in many imperative languages, in which it tends to be ==
	- These are evaluated in the order they are stated
	- else can be used at the end as an alternative
	- if the if keyword is used, else doesn't seem to have to be, an alternative can just be mentioned at the bottom
	
	
