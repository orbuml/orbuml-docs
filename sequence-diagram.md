# sequence-diagram

A [sequence diagram](https://en.wikipedia.org/wiki/Sequence_diagram "sequence diagram from wikipedia") shows object interactions arranged in time sequence. It depicts the objects involved in the scenario and the sequence of messages exchanged between the objects needed to carry out the functionality of the scenario. Sequence diagrams are typically associated with use case realizations in the Logical View of the system under development. Sequence diagrams are sometimes called event diagrams or event scenarios.

## basic example

```
@startuml
Pitcher -> Batter: Throw ball
Batter -> Batter: swings (misses)
Batter -> Catcher: miss
Catcher --> Pitcher: Return ball
@enduml
```





