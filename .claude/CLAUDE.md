# Code style

- Use meaningful variable, function and class names (never abbreviate them)
- Function and method names start with the verb
- Never use single-letter variables
- Never use Hungarian Notation
- Always prefer early returns over nested logic
- Always use singular forms for types and single objects
- Always use plural forms for arrays
- Attempt to order long lists, including arrays, e.g. alphabetically
- Boolean variables do not use `is` or `has` prefixes - only functions that
  return boolean values. `-ing`, `-able`, `-ible` suffixes and the `in-` prefix
  are good alternatives.
- If an imported entity uses a "product placement", using some vendor- or
  brand-specific terms, alias them with more abstract ones (if the language
  supports import aliasing). E.g. disallow usage of things like _lodash_ or
  _redux_ in the code.
- camelCase acronyms
- Use British English spelling

## JavaScript and TypeScript
- Never use semicolons
- Never use trailing commas
- Avoid `else` clauses

## React
- Avoid complex and excessive JSX block of code
- Treat hooks as declarative orchestrators, extracting imperative code to plain
  JS collaborators

## Swift
- Prefer the `in` prefix for computed properties
- Use 2-space indentation
- Prefer `guard` over nested `if` for early returns
- Never add trailing commas in multi-line collections
