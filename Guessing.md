``` mermaid
flowchart TD
   Start([Start]) --> B([Generate Random Number])
  B --> C[User input]
  C --> D{Is Guess correct?}
  D --> |Yes| E[Game Over]
  D --> |No| F{Low number?}
  F --> |Yes| G[Guess Higher]
  F --> |No| H[Guess lower]
  G --> C
  H --> C
```
### The process :
- I used the template in the instructions to get started and using the exmaples about the flowchart syntaxs to use certain shapes for my inputs. First i started with the topic of my task which is guessing a random number
  , i then added a input for users to guess a number then yes or no scenarios if the user guessed right or wrong.
