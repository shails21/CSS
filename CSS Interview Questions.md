#### 1. What are the components of a CSS Style?
- Selector : A selector is an HTML tag at which a style will be applied. This could be any tag like \<h1\> or \<table\> etc.
- Property : A property is a type of attribute of HTML tag. Put simply, all the HTML attributes are converted into CSS properties. They could be color, border etc.
- Value : Values are assigned to properties. For example, color property can have value either red or #F1F1F1 etc.

#### 2. What are the different type of selectors?
- Type selector : quite simply matches the name of an element type. eg below type selector give a color to all level 1 headings. eg. h1 {color: #36CFFF; }
- Universal Selector : Rather than selecting elements of a specific type, the universal selector quite simply matches the name of any element type. eg. * {color: #365DFA}
- Descendant Selector : Suppose you want to apply a style rule to a particular element only when it lies inside a particular element. As given in the following example, style rule will apply to \<em\> element only when it lies inside \<ul\> tag. eg. ul em { color: #000000; }
- Class Selector : You can define style rules based on the class attribute of the elements. All the elements having that class will be formatted according to the defined rule. eg. .black {color: #000000; }
- ID Selector : You can define style rules based on the id attribute of the elements. All the elements having that id will be formatted according to the defined rule. eg. #black {color: #000000;}
- Child Selector : This rule will render all the paragraphs in black if they are direct child of \<body\> element. Other paragraphs put inside other elements like \<div\> or \<td\> would not have any effect of this rule. eg. body > p {color: #000000; }
- Attribute Selector : You can also apply styles to HTML elements with particular attributes. The style rule below will match all the input elements having a type attribute with a value of text. eg. input[type = "text"]{ color: #000000;} 
The advantage to this method is that the \<input type = "submit" /\> element is unaffected, and the color applied only to the desired text fields.

#### What is the difference between Block and Inline?


#### Difference between JavaScript window.onload event and jQuery ready function?
- Window.onload : JavaScript onload event waits for DOM to be created also waits until all external resources are fully loaded including heavy images, audios and videos.  If loading images and media content takes lot of time that user can experience significant delay on execution of code defined in window.onload event. Onload(09 function can only be called once in a page.
- Document.ready() : Function only wait for DOM tree, and does not wait for images or external resource loading, means faster execution. Advantage of ready() function is that it can use it multiple times in your page, and browser will execute them in the order they appear in HTML page.
