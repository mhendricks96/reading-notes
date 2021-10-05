# React 2 Readings

## Conditional Rendering

- JavaScript operators like if or the conditional operator create elements representing the current state

- variables can store elements

## Lists and Keys

- Keys help React identify which items have changed, are added, or are removed

- may use the item index as a key as a last resort

- Keys used within arrays should be unique among their siblings, but dont need to be globally unique

## Forms

- form elements naturally keep some internal state.

- want to alwasy have a "single source of truth" in the state

## Lifting State Up

- if multiple components are using the same state, it should come from the same ancestor

- Instead of trying to sync the state between different components, you should rely on the top-down data flow.
