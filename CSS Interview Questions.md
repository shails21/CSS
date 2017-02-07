#### 1. What are the components of a CSS Style?
Selector − A selector is an HTML tag at which a style will be applied. This could be any tag like \<h1\> or \<table\> etc.
Property − A property is a type of attribute of HTML tag. Put simply, all the HTML attributes are converted into CSS properties. They could be color, border etc.
Value − Values are assigned to properties. For example, color property can have value either red or #F1F1F1 etc.

#### 2. What are the different type of selectors?
Type selector : quite simply matches the name of an element type. eg below type selector give a color to all level 1 headings −
```
h1 {color: #36CFFF; }
```
Universal Selector: Rather than selecting elements of a specific type, the universal selector quite simply matches the name of any element type.
```
* {color: #365DFA}
```
Descendant Selector : Suppose you want to apply a style rule to a particular element only when it lies inside a particular element. As given in the following example, style rule will apply to \<em\> element only when it lies inside \<ul\> tag.
```
ul em { color: #000000; }
```
Class Selector:You can define style rules based on the class attribute of the elements. All the elements having that class will be formatted according to the defined rule.
```
.black {color: #000000; }
```
ID Selector : You can define style rules based on the id attribute of the elements. All the elements having that id will be formatted according to the defined rule.
```
#black {color: #000000;}
```
