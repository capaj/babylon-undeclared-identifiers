# babylon-undeclared-identifiers
given a javascript source code, returns undeclared identifiers

Previously I used esprima where it was quite complicated task. Thankfully, babylon offers `path.scope.globals` where we get all undefined identifiers right out of the box which makes this package trivial.