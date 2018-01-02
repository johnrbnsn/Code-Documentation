# Code-Documentation
Quick reference for Python documentation

User Changeable Parameter
-------------------------

When following a tutorial, the user usually doesn't want the same variable names that you use. There are often times when case/ naming etc. change depending on where the paramter is used in the code, and that is not always apparent by reading the tutorial. My proposal is to show user changeable parameters in either `{}` or `<>`, TBD if there is a standard. Specify case/ camelCase/ snake-case/ underscore_case when relevant to the documentation. Note, capital letters at the beginning of the name represent when you need to use capitals, and same for lowercase. For example `{name}` and `{Name}` both refer to the same variable, but in the `{name}` instance a lowercase first letter is required, and `{Name}` requires uppercase first letter.

Optional Parameters
-------------------

Python documentation shows optional parameters in `[]`.

Example::

    get(key[, default])

Terminal
--------

Show terminal with required environment or location, this will help the user to know when virtual envs are activated/ deactivated, and if/when a certain user/host is required. the pwd parameter shows what the current directory being used is. Note that not all parameters have to be shown all the time, just when it contributes to the understanding. 

Terminal Example::

    ({env}) {user}@{host}:{pwd}$ 
    
Python Prompt Example::

    >>> a = 5
