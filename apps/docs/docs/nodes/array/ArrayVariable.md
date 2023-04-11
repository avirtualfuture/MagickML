# Array Variable

## Inputs

| Input Name | Type | Description |
| ---------- | ---- | ----------- |
| Value | string | string to split into an array |
| Splitter | string | string used to split **Value** |
| Keep Empty Values | boolean | true : "" strings are kept in the result | 

## Outputs
| Output Name | Type | Description |
| ------------|------|-------------|
| output      | string[]   | array of strings |

## Description
Splits a **Value** string with a **Splitter** string into an array of strings.
If **Keep Empty Values** is true then empty strings will be kept in the resulting array.
The resulting array is sent through **output**.
