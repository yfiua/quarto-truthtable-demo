# quarto-truthtable-demo
Quarto demo for conditional content display based on a truth table.

## Example
When nothing is ticked, display nothing:

<img width="364" height="124" alt="image" src="https://github.com/user-attachments/assets/084b6dc6-3201-42e5-9a32-d76c9d672333" />

When only A is selected, display both blocks:

<img width="846" height="256" alt="image" src="https://github.com/user-attachments/assets/76e7d137-b9fe-4857-b6cf-8fe4a5c684fb" />

When A and B are selected, display the first block:

<img width="848" height="197" alt="image" src="https://github.com/user-attachments/assets/18bf1a60-fae6-4a73-bd19-7877da992bba" />

The rule is defined in a [truth table](https://en.wikipedia.org/wiki/Truth_table) as a JSON object:

```
const truthTable = {
  "10": ["x1", "x2"],
  "11": ["x1"]
};
```

## Live demo

https://yfiua.github.io/quarto-truthtable-demo/
