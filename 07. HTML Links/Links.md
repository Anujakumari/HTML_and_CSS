# HTML Links
- HTML links are hyperlinks.
- You can click on a link and jump to another document.

## Syntax
The HTML `<a>` tag defines a hyperlink. It has the following syntax:
```
<a href="url">link text</a>
```
  
## Example:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Links</title>
</head>
<body>
    <a href="https://google.co.in"> Go to Google </a> 
</body>
</html>
```
  
## Output
![HTML_Links](https://github.com/Anujakumari/HTML_and_CSS/blob/master/img/Link_1.png) 
  

**By default, links will appear as follows in all browsers:** <br>

- An unvisited link is **underlined and blue**.
- A visited link is **underlined and purple**.
- An active link is **underlined and red**.

# The target Attribute
By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.<br>
The target attribute specifies where to open the linked document.<br>
<br>
The target attribute can have one of the following values:

- _self - Default. Opens the document in the **same window/tab as it was clicked**.
- _blank - Opens the document in a **new window or tab**.
- _parent - Opens the document in the **parent frame**.
- _top - Opens the document in the **full body of the window**.
 
## Example:
  
```
 <a href="https://google.co.in" target="_blank"> Go to Google </a>
```
  
# Absolute URLs vs. Relative URLs
  
- **Absolute URLs**(a full web address) : An absolute URL contains the entire address from the protocol (HTTPS) to the domain name (www.example.com) and includes the location within your website in your folder system (/foldernameA or /foldernameB) names within the URL.
  
An example of an absolute URL is:
```
<a href = http://www.example.com/xyz.html>
```

<br>
  
- **Relative URLs**(without the "https://www" part) : The relative URL does not use the full web address and only contains the location following the domain. It assumes that the link you add is on the same site and is part of the same root domain. <br>
The relative path starts with the forward slash and leads the browser to stay within the current site. <br>

An example of a relative URL is:
```
<a href = "/xyz.html">
```
  
## Example:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Links</title>
</head>
<body>
    <h2>Absolute URL</h2> <br>
    <a href="https://google.co.in" target="_blank"> Go to Google </a> <br> <br>   
    <h2>Relative URL</h2> <br>
    <a href="../2. Headings/Heading.html" target="_blank"> See the view </a>
</body>
</html>
```
  
## Output:
![HTML_LINKS](https://github.com/Anujakumari/HTML_and_CSS/blob/master/img/Link_2.png)
  
