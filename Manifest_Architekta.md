```
graph TD
    A[Start] --> B{Decyzja?};
    B -- Tak --> C[Akcja 1];
    B -- Nie --> D[Akcja 2];
    C --> E[Koniec];
    D --> E;
```
