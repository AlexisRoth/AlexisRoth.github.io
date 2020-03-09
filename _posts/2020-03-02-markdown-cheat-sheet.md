---
layout: post
title: Markdown cheat sheet
categories: technical
---
Principales balises markdown à connaître pour la mise en page de base. 

# h1 : `#`
## h2 : `##`
### h3 : `###`
#### h4 : `####`
##### h5 : `#####` 
###### h6 : `######`

## You can add emojis like this : :rocket:
https://emoji-cheat-sheet.com 

## Text formatting
*This text will be in italic*  
_Another way to be in italic_  
**This text will be bold**  
__Another way to be bold__  
*You **can** combine them*  

## Quoting text 
Famous quote from **CommitStrip**
>Tester c'est douter

## Lists
### Unordered
* Item 1
  * Item 1a
* Item 2
  * Item 2a
  * Item 2b

### Ordered
1. Item 1 
    * Item 1a
2. Item 2
3. Item 3
    * Item 3a
    * Item 3b

## Images
![Image test](/images/jekyll-logo.png)

## Links
* First way : just paste the link 
  * https://github.com
* Second way : similar to images 
  * [GitHub](https://github.com)
  
## Backslash escapes 
Markdown allows to use backslash escapes to generate litteral characters which would otherwise have a special meaning in Markdown's syntax. 
* \*
* \\
* \`
* \_
* \{
* \}
* \[
* \]
* \(
* \)
* \#
* \+
* \-
* \.
* \!

## Mentionning people 
You can use the '@' to mention people. The person will be notified that someone tagged her. You can also mention team if you are in an organization. 

## Issue reference 
You can refer to an **Issue** or **Pull Request** with the \# character followed by the issue's/pull request's number.

## Fenced code blocks 
You can wrap your code using \`\`\` + language (optional) 

```java 
class FirstApp {
 public static void main (String[] args){
  System.out.println("Hello World");
 }
}
```
## Task lists 
- [x] completed 
- [ ] todo

## Tables (to fix) 

First header | Second header 
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Conten column 2 
