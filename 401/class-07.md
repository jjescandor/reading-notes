The concept of scope rules how variablesLinks to an external site. and names are looked up in your code. It determines the visibility of a variable within the code.
The scope of a name or variable depends on the place in your code where you create that variable.
The Python scope concept is generally presented using a rule known as the LEGB rule.
Two general scopes:

Global scope: The names that you define in this scope are available to all your code.

Local scope: The names that you define in this scope are only available or visible to the code within the scope.

Since Python is a dynamically-typedLinks to an external site. language, variables in Python come into existence when you first assign them a value.
Functions and classes are available after you define them using defLinks to an external site. or classLinks to an external site., respectively.
ModulesLinks to an external site. exist after you import them.
Local (or function) scope is the code block or body of any Python function or lambdaLinks to an external site.expression.

This Python scope contains the names that you define inside the function.

These names will only be visible from the code of the function.

It’s created at function call, not at function definition, so you’ll have as many different local scopes as function calls.

This is true even if you call the same function multiple times, or recursivelyLinks to an external site..

Each call will result in a new local scope being created.

Enclosing (or nonlocal) scope is a special scope that only exists for nested functions.

If the local scope is an inner or nested functionLinks to an external site., then the enclosing scope is the scope of the outer or enclosing function.

This scope contains the names that you define in the enclosing function.

The names in the enclosing scope are visible from the code of the inner and enclosing functions.

Global (or module) scope is the top-most scope in a Python program, script, or module.

This Python scope contains all of the names that you define at the top level of a program or a module.

Names in this Python scope are visible from everywhere in your code.

Built-in scope is a special Python scope that’s created or loaded whenever you run a scriptLinks to an external site. or open an interactive session.

This scope contains names such as keywordsLinks to an external site., functions, exceptionsLinks to an external site., and other attributes that are built into Python.

Names in this Python scope are also available from everywhere in your code.

It’s automatically loaded by Python when you run a program or script.

