---
id: checkbox-row
title: CheckboxRow
---

RowItem with Chackmark Icon on right side.

![CheckboxRow component](assets/checkbox-row.png)
 
Example usage:
```jsx
<CheckboxRow
  selected={this.state.checkboxSelected}
  onPress={() =>
    this.setState(state => ({
      checkboxSelected: !state.checkboxSelected,
    }))
  }
  title="CheckobxRow"
  subtitle="Selectable row"
/>
```

## Theme
Uses following `theme` properties:
- `primaryColor` - checkmark icon color


## Props

### [RowItem props...](row-item.html#props)

Other props accepted by `RowItem` component.

### `onPress`
**type:** `void => void`

Event fired when Row is pressed in.

### `selected`
**type:** `boolean`

Indicates whether checkbox is selected or not.

### `theme` (optional)
**type:** [`Theme`](theme.html)
 
Custom theme for component. By default provided by the ThemeProvider.

