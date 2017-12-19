# New Requirements

* Network operations cannot make a definite list of file formats (what a surprise!)
* Message body can come from a database, instead of the content of a file

## The Exercise

This new requirement needs to be implemented, but be careful to not violate LSP with your implementation!.

## Hint

A sure way to screw up with LSP is downcasting in order to do stuff differently depending of the implementation of the abstraction.

## Hint #2

A wisely chosen abstraction will make little to no impact to consuming code.
