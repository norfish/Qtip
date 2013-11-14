#Tooltip
## qunar tooltip
**jquery plugin**
@name  **qtip**

- support title or data-title
- support html
- support tooltip window with a title
- set deriction easily
- support easing e.g. fade/slide/easing/... and so on
- base on tipsy
- auto adjust position to be show property


## Description
 **@Name** Qtip  
 **@Descripe** a jQuery plugin tooltip that change the default popup  
 **@user** Yongxiang.Li   
 **@base on** [tipsy](https://github.com/jaz303/tipsy)
 
 @Example  
 
 Html: 
 
```html
 <a href="#" id="tip" title="Title is Title">Hover Tip</a> 
	OR <a href="#" id="tip" qtip-title="Title is Title">Hover Tip</a>
```
 **simply:**   
 - ('el').qtip([options]);  
 - Param options {object}
 
```
{
   className: null, 
   delayIn: 0,
   delayOut: 0,
   fade: false,
   fallback: '',
   direction: 'b',
   html: false,
   on: false,
   offset: 0,
   opacity: 0.8,
   title: 'title', //can alse specify the content(string: html or text) 
   header: '提示', //default header when used  
   trigger: 'hover' 
}
```