# Markdown notes 

## Different ways to highlight text.  
1. Italic  
*Italic* or _Italic_
1. Blod  
**Blod** or __Blod__
1. Monospace  
`monospace` 

## Set header  
Don't skip blank afer '#' to create header,number is not allowed in header.
# header one
## 	header two
### header three
#### header four

## Paragraphs  
1. To create another paragraph:use a blank line to seperate the paragraphs.
1. To create new line in the same paragraph:use two or more blanks ,or '\' as line break,often use in poem.  

## Lists  
1. List with numbers  
Automatically sorted list ,dont's leak blank after dot,and you should use them in the same paragraph,which means that don't add blank line between paragraphs.(Quoteis not allowed in list?) 
	1. List item one     
		1. Indent four spaces   
			1. Indent eight spaces  
		1. Indent four spaces
	1. List item two
	1. List item three
1. List whithout numbers
	- Indent four spaces 
		- Indent eight spaces  
1. Use '\\.' or leak the blank after '.' to turn off list  
1994.03.08 is my birth day.
		
## Block quote
- Nested quotes  
>    	Quote1
>>		Quote2,nested quote in quote1
>>>		Nested quote in quote2  

- Embed a list in block quote  
>1. List item one
>2. List item two  
  
- Show how to use block in list item  
	- Use block quote in list item one,you should add one or more tabs before '>',the number of tab depends on the list level.   
	>It's a quote.  
	>Anoter quote. 
	>The list is of level one,so we only add one tab before '>'  
	- List item two
		1. List level two.
		1. Add two tabs before '>'  
		>It's a quote.

## Links  
1. Add link to the tag  
Don't put any blanks between (Tags) and \[links\].And in windows system,you should replace \ with / when links to local file.   
[Git config](C:/Users/lenovo/.gitconfig)  
1. Add tooltip on the tag  
[Git config](C:/Users/lenovo/.gitconfig "The configuratin file of Git")  
1. URLs link  
Just enclose the URL or email address in angle brackets
<https://www.markdownguide.org/>
1. Formatting links  
Italic format *[Guide](https://www.markdownguide.org/)*  
Blod format **[Guide](https://www.markdownguide.org/)**  
1. Reference-style links  
Place a lable after the tag [Guide][lable]   
And then place the lable anywhere,but must a new line ahead of the lable.  
So that you can use the lable more than one time.
And it's better not to place the lable in the list,because there's a blank line before the lable.  
Use the lable again [Guide book][lable]   
<!--A blank line here-->   
[lable]: https://www.markdownguide.org/


## Images  
1. Embed image from local file  
![Lifecycle of git](E:/Git/notes/lifecycle.png) 
2. Reference-style image  
![Lifecycle of git][p1]

[p1]:E:/Git/notes/lifecycle.png
   

## Codes
1. Denote a word as Code   
`code`
1. Code blocks,and palce a tab in front of  \`\`\` when in list    
	```	
	{  
			"name":"John"  
	}
	```  
1. Item3

## Horizon rule
1. Three ways to use horizon rule
***
---
___

## Tables  
-  normal tables  
<!--A blank line here-->
| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This       |        This |     This     |
| column     |      column |    column    |
| will       |        will |     will     |
| be         |          be |      be      |
| left       |       right |    center    |
| aligned    |     aligned |    aligned   |

##Footnotes
When click the footnote identifer[^1],it can jump to the note.  
No matter where you place the footnote, it will appear at the end of the page.
[^1]: This id the first footnote.

##Backslash escapes  
You should use backslash escapes for follwing characters: 
<!--A blank line here-->
|Character|Description|
|---------|-----------|
|\|backslash|
|`|backtick|
|*|asterisk|
|_|underscore|
|{}|curly braces|
|[]|square brackets|
|()|parenthesis|
|#|hash mark|
|+|plus sign|
|-|minus sign|
|.|dot|
|!|exclamation mark|

End of article.:)



