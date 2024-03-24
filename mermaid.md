## Game Theory

```mermaid
graph LR
Left -- Take Decision --> M(DMessenger) --> G((UN))
Right -- Take Decision --> M(DMessenger) --> G((UN))
G((UN)) -- Left Points --> P(PMessenger)
G((UN)) -- Right Points --> P(PMessenger)
P(PMessenger) --> Left
P(PMessenger) --> Right
```

## Points

|Decisions |Left Points |Right Points |
|----------|------------|-------------|
|`y` vs `y`|    `+3`    |     `+3`    |
|`y` vs `n`|    `+5`    |      `0`    |
|`n` vs `y`|    `0`     |     `+5`    |
|`n` vs `n`|    `+1`    |     `+1`    |