# Expression
A scripting programming language focused on providing a simple way to evaluate math expressions in the terminal.

# When
Not entirely sure **when** or **if** I will start this project but I really want to make an interpreted programming language and the use case for this makes sense to me. 


# What will be expected to be possible

Simple math expressions evaluated in the terminal like 

``expression (1*2 + 3^4) / 4``
or even 
``expression expression1.exp * expression2.exp``
Allowing the programmer to write expressions in files and call reference them within other code as already evaluated statements

# Ideas for myself

Would be cool to allow the programmer to use the ∀ symbol or /forall to create a generator given some expression like 

evens = ∀ x ∈ ℕ, x / 2 == 0 (AKA only even numbers)

And then the developer can use this later to say evens[12]

and it will return the 12th term in that generator (this is EXTREMELY ambitious but its a cool idea)
