# Testing UML

## .iuml

![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/blavin3/uml-testing/master/images/test.iuml)

## Testing Mermaid

* Note: no Doxygen integration documentation
* Not compatibale with Bitbucket, but VS extensions available

```mermaid
graph TD
    A[Driver] --> B[Resources]
    A[Driver] --> C[SRC]
    C --> src.c
    C --> src.h
    B --> mermaid.txt
    B --> driver_ug.md
```
