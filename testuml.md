# Diagram Test

![diagram](docs/diagrams/out/test.svg)

::uml::
Alice -> Bob: Authentication Request
Bob --> Alice: Authentication Response

Alice -> Bob: Another authentication Request
Alice <-- Bob: Another authentication Response
::end-uml::
