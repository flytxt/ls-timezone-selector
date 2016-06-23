# ls-timezone-selector
`<ls-timezone-selector>` is a time zone selector for Labor Sync. It may be used as a form element.  

Typically, <ls-timezone-selector> is used in a form element.  

```html
    <ls-timezone-selector name="timezone" label="Time Zone" value="America/New_York">  
    	</ls-timezone-selector>  
```

##Properties:
    name: Name of input  
    value: Value of the dropdown  
    label: Label for the dropdown  
    error-message: Message to display when selection is invalid  
    required: Whether selection can be blank/not a value  
    invalid: True if the last call to validate is invalid.  
    horizontal-align: The orientation against which to align the menu dropdown horizontally relative to the dropdown trigger.  

##Methods:
    validate(): sets `invalid` to true if `required` is truthy and value is blank.  

Todo: Add population of timezone options from ajax request  
