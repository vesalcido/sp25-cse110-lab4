### var declaration
1. Line 9 prints "values added: 20"
2. Line 13 prints "final result: 20"
3. The reason we shouldn't use `var` because it could lead to naming conflicts and scoping issues , it also can be accessed anywhere inside the function it's defined in.
4. Line 9 prints "vallues added: 20"
5. Line 13 prints an error because the `result` variable is only defined inside the if block, so it doesn't exist outside the if(add).

### const declaration
6. Line 9 prints an error because I used `const` to create `result`, whcih means I can't change it after its defined.
7. Line 13 prints an error because I then tried to change the `result` which is a `const` type, which isn't allowed.