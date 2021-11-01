# HTML
### End of subject html test for my students

### 1. Suppose we want a paragraph element, with an anchor element insde which links to https://www.google.com - how would that look?

A: 
```
<p>
  <a="https://www.google.com">Go to Google</a>
</p>
```
B:
```
<p><a href="https://www.google.com">
```
C:
```
<p>
  <a href="https://www.google.com">Go to Google</a>
</p>
```
D:
```
<p>
  <a target="https://www.google.com">Go to Google</a>
</p>
```
### 2. Excluding the "<!DOCTYPE>" flag, which element are all other elements in an html document contained by?
  
A: ```<all></all>``` <br>
B: ```<html></html>``` <br>
C: ```<body></body>``` <br>
D: ```<head></head>``` <br>
  
### 3. Why would we use the "h3" element?

A: As a subheading <br>
B: At the top of an article <br> 
C: It doesn't matter what tag you use since we can change it's appearence with CSS <br>
D: When there is already a heading and a subheading, but there should be yet another <br>
subheading before the main content begins

### 4. What is a _semantic_ element?

A: Elements that have more than one attribute <br>
B: Elements that link to some semantic text <br>
C: Elements which give meaning in a human- and machine-readable way <br>
D: None of these <br>

### 5. Of these sets of elements which are _all_ semantic elements

A: ```<section> <div> <span> ``` <br>
B: ``` <article> <form> <header> ```  <br>
C: ``` <nav> <a> <main>```  <br>
D: ```<section> <aside> <p>``` <br>

### 6. Which of these belongs in the ```<head>``` element rather than the ```<body``` element?

A: ```<span>``` <br>
B: ```<link>```  <br>
C: ```<header>```  <br>
D: None of these <br>

### 7. Which of these HTML snippets is _not_ a good practice

A:
```
<p>
    <span>here is some text</span>
</p>
```
B:
```
<article>
    <p>here is some text</p>
</article>
```

C:
```
<p>
    <h1>here is some text</h1>
</p>
```

D:
```
<section>
    <h1>here is some text</h1>
</section>
```
### 8. What is the difference between a block level element and an inline element?

A: A block element has a block of padding around it and inline elements do not <br>
B: An inline element does not take all of the horizonatl space on either side of it but a block element does <br>
C: A block level element has a block of text inside but an inline element has images or other forms of data <br>
D: None of these <br>

### 9. What is the purpose of a ```<div>``` element

A: It is used to divide sections of content <br>
B: It is used to group content <br>
C: It is used as a placeholder element <br>
D: All of these <br>

### 10. Which options have a set of tags that do not need to be closed

A: ```<img> <span> <br>``` <br>
B: ```<p> <a> <span>``` <br>
C: ``` <img> <br> <hr>``` <br>
D: ```<br> <img> <p>``` <br>

### 11. What is an HTML _attribute_?

A: Code inside of an element that informs text reading devices for the blind <br>
B: Code inside of an element that tells the element how to behave <br>
C: Code that tells an image tag which image to display <br>
D: All of these <br>

### 12. Which of these will make a numbered list:

A:
```
<ol>
    <li>item 1</li>
    <li>item 2</li>
    <li>item 3</li>
</ol>
```

B:
```
<ul>
    <li>item 1</li>
    <li>item 2</li>
    <li>item 3</li>
</ul>
```

C: Both of these <br>
D: Neither of these <br>

### 13. Which of these is a correctly implemented table with one row of headers and 3 rows of cells

A:
```
<table>
    <tr>
        <thead>
            <th>User</th>
            <th>Name</th>
            <th>Password</th>
        </thead>
    </tr>
     <tr>
        <tbody>
            <td>User1</td>
            <td>Name1</td>
            <td>Password1</td>
        </tbody>
     </tr>
     <tr>
        <tbody>
            <td>User2</td>
            <td>Name2</td>
            <td>Password2</td>
        </tbody>
     </tr>
     <tr>
        <tbody>
            <td>User3</td>
            <td>Name3</td>
            <td>Password3</td>
        </tbody>
     </tr>
</table>
```

B:
```
<table>
    <thead>
        <tr>
            <th>User</th>
            <th>Name</th>
            <th>Password</th>
        </tr>
    </thead>


    <tbody>
        <tr>
            <td>User1</td>
            <td>Name1</td>
            <td>Password1</td>
        </tr>
        <tr>
            <td>User2</td>
            <td>Name2</td>
            <td>Password2</td>
        </tr>
        <tr>
            <td>User3</td>
            <td>Name3</td>
            <td>Password3</td>
        </tr>
    </tbody>
</table>
```

C:
```
<table>
    <tr>
        <th>User</th>
        <th>Name</th>
        <th>Password</th>
    </tr>
     <tr>
        <td>User1</td>
        <td>Name1</td>
        <td>Password1</td>
     </tr>
        <td>User2</td>
        <td>Name2</td>
        <td>Password2</td>
     </tr>
     <tr>
        <td>User3</td>
        <td>Name3</td>
        <td>Password3</td>
     </tr>
</table>
```

D: All of these <br>

### 14. What does the 'action' attribute of a form do?

A: The code inside the attribute executes when the form is submitted <br>
B: The browser makes a request to the url inside the attribute (usually sending the data within the form as parameters <br>
C: Both of these <br>
D: Neither of these <br>

### 15. Which of these is a properly formed checkbox element?

A: ```<checkbox>``` <br>
B: ```<check>``` <br>
C: ```<input type="check">``` <br>
D: ```<input type="checkbox">``` <br>

### 16. What is the correct way to make a form element that accepts basic text

A: ```<textfield>``` <br>
B: ```<input type="textfield">``` <br>
C: ```<input type="text">``` <br>
D: none of these <br>

### 17. What is the correct way to make a drop-down list?

A: ```<list>``` <br>
B: ```<input type="dropdown">``` <br>
C: ```<input type="list">``` <br>
D: ```<select>``` <br>

### 18. Which of these is a properly formatted image element?

A: ```<image src="bear.jpg" alt="a bear">``` <br>
B: ```<img src="bear.jpg">``` <br>
C: ```<img src="bear.jpg" alt="a bear">``` <br>
D: ```<image src="bear.jpg">``` <br>

### 19. HTML comments start wtih ```<!--``` and end with ```-->```

A: true <br>
B: false <br>

### 20. Which semantic element should we use to define navigation links?

A: ```<navigation>``` <br>
B: ```<nav>``` <br>
C: ```<navigate>``` <br>
D: None of these




