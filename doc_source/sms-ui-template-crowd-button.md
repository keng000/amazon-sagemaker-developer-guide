# crowd\-button<a name="sms-ui-template-crowd-button"></a>

A styled button that represents some action\.

## Attributes<a name="button-attributes"></a>

The following attributes are supported by this element\.

### disabled<a name="button-attributes-disabled"></a>

A Boolean switch that, if present, displays the button as disabled and prevents clicks\.

### form\-action<a name="button-attributes-form-action"></a>

A switch that either submits its parent [crowd\-form](sms-ui-template-crowd-form.md) element, if set to "submit", or resets its parent <crowd\-form> element, if set to "reset"\.

### href<a name="button-attributes-href"></a>

The URL to an online resource\. Use this property if you need a link styled as a button\.

### icon<a name="button-attributes-icon"></a>

A string that specifies the icon to be displayed next to the button's text\. The string must be either the name of an icon from the open\-source *[iron\-icons](https://github.com/PolymerElements/iron-icons)* set, which is pre\-loaded, or the URL to a custom icon\.

The icon is positioned to either the left or the right of the text, as specified by the *icon\-align* attribute\.

### icon\-align<a name="button-attributes-icon-align"></a>

The left or right position of the icon relative to the button's text\. The default is "left"\.

### icon\-url<a name="button-attributes-icon-url"></a>

A URL to a custom image for the icon\. A custom image can be used in place of a standard icon that is specified by the *icon* attribute\.

### loading<a name="button-attributes-loading"></a>

A Boolean switch that, if present, displays the button as being in a loading state\. This attribute has precedence over the *disabled* attribute if both attributes are present\.

### target<a name="button-attributes-target"></a>

When you use the `href` attribute to make the button act as a hyperlink to a specific URL, the `target` attribute optionally targets a frame or window where the linked URL should load\.

### variant<a name="button-attributes-variantl"></a>

The general style of the button\. Use "primary" for primary buttons, "normal" for secondary buttons, "link" for tertiary buttons, or "icon" to display only the icon without text\.

### wrap\-text<a name="button-attributes-wrap-text"></a>

A Boolean switch that, if present, prevents the button's text from wrapping\.

## Element Hierarchy<a name="button-element-hierarchy"></a>

This element has the following parent and child elements\.
+ **Parent elements**: [crowd\-form](sms-ui-template-crowd-form.md)
+ **Child elements**: none

## See Also<a name="button-see-also"></a>

For more information, see the following\.
+ [Amazon SageMaker Ground Truth](sms.md)
+ [HTML Elements Reference](sms-ui-template-reference.md)