---
title: dfr columns
categories: |
  dataframe
version: 0.93.0
dataframe: |
  Show dataframe columns.
usage: |
  Show dataframe columns.
feature: dataframe
---
<!-- This file is automatically generated. Please edit the command in https://github.com/nushell/nushell instead. -->

# `dfr columns` for [dataframe](/commands/categories/dataframe.md)

<div class='command-title'>Show dataframe columns.</div>

::: warning
Dataframe commands were not shipped in the official binaries by default, you have to build it with `--features=dataframe` flag
:::

## Signature

```> dfr columns {flags} ```


## Input/output types:

| input | output |
| ----- | ------ |
| any   | any    |

## Examples

Dataframe columns
```nu
> [[a b]; [1 2] [3 4]] | dfr into-df | dfr columns
╭───┬───╮
│ 0 │ a │
│ 1 │ b │
╰───┴───╯

```
