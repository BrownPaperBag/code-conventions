# Selector Names

All selector names must use the hyphenated style.

- - -

```CSS
.class-name {

}
#element-id {

}
```

- - -

```HTML
.class-name,
.different-class-name {

}
```

### Note
 - Separate multiple selectors with a `,` and a newline

``CSS
input[type="email"] {

}
[data-important] {

}
```

### Notes
 - Attribute selectors may be used with the following *except* for the
 `input[type="text"]` selector. This relies on the redundant `type="text"`
 attribute being applied to the target elements. Automated optimisers will
 strip such redundant attributes, rendering such selectors useless
 - Selecting by the presence of an attribute is acceptable

