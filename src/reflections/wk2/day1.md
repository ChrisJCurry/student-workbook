1. What is Scope ?
    Scope is the accessability of a key/value. A variable placed inside a function would have the scope of the function, whereas a variable placed outside the function would have the scope of the entire file.

2. What is Hoisting ?
    Hoisting is variables being pushed to the top. A var would be pushed up and be undefined, whereas a let would throw a reference error, should either be called prior to being initialized.

3. In what cases might you use let vs const vs var?
    let: I would use let inside a function that doesn't need to update a global variable.
    const: If I needed a variable to never change, I would use a const.
    var: I would use a var if it needed to be a global variable that functions could also modify.