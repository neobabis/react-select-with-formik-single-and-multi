# react-select-with-formik-single-and-multi

### `npm install react-select`

# usage:
## for Single Selection

```
<Field
    name="singleSelectCustom"
    id="singleSelectCustom"
    placeholder="Single Select"
    isMulti={false}
    component={MultiSelect}
    options={[
        { value: 'one', label: 'One' },
        { value: 'two', label: 'Two' },
        { value: 'three', label: 'Three' },
    ]}
/>
```


## for Multi Selection

```
<Field
    name="multiSelectCustom"
    id="multiSelectCustom"
    placeholder="Multi Select"
    isMulti={true}
    component={MultiSelect}
    options={[
        { value: 'one', label: 'One' },
        { value: 'two', label: 'Two' },
        { value: 'three', label: 'Three' },
    ]}
/>
```


View more: [React-select with Formik for Single and Multi Selections](https://neobabis.gr/react-select-with-formik-for-single-and-multi-selections/)
