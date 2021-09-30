# Introduction to Web Development 
A quick crash course by Junior Garcia
## Outline
- What is a website?
- Client-server model
- What is a website composed of?
- Make your own HTML page
- Style your Own HTML page
- (Optional )Add some Interactivity to your web page. 

### What is a website?
<img src ="website.png"/>

### Client-Server Model
<img src="client-server-model.png"/>

### What is a website composed of?
A typical website, as in the content that you access with your device, is usually composed of: 
    - One or more Hyper Text Markup Language (HTML) pages. 
    - Some styling, dictated by the Cascading Style Sheets (CSS) langauge. 
    - Some interactivity, provided by the Javascript programming Language. 
- Create your own HTML page
Creating an HTML page is all you need to make your own website. Everything you do after will be to improve your website, but is not neccessary by any means. 

### Make your own HTML page
- Use a text editor of your choice (Install Visual Studio Code)
- Create a new document
- Give it a title. The usual convention is to call the page (index.HTML), but you can name it however you want. 
- Add some HTML code to your page. Although HTML has its set of rules, just like other programming languages, it is just a markup language. This means that the rules are made to make the process easier for several people to collaborate with each other (like us, web developers). Therefore, we should not feel intimated by these rules as they can usually be found online (Google will alway be your friend when making websites).
- Add this code to your page 
```HTML
<HTML>
    <div>
        <p>Hello World, my name is [NAME]</p>
    </div>
</HTML>
```
- Add your name inside the brackets.
- Done, you created your own webpage!

### Style your Own HTML page
- Add a header tag in your HTML page
- Add a style tag 
- Change the color of all the text of your webpage
- Change the background of your HTML page
- Done! You have styled your own CSS Page.
- Reference:  https://www.w3schools.com/css/

```
<style>
html{
color: red;
background-color:aqua;
}
</style>
```
### (Optional )Add some Interactivity to your web page. 
- Interactivity is another one of the reasons why html tags are so important! They let us access the elements of a webpage we want to make interactive. 

- Add the following to your p tags. 
```
<p id="change-this" onclick="changeColor()">
```
- In the head tag in your HTML file, add a script tag.
``` 
    <head>
        <style>
            html{
                color:red;
                background-color: aqua;
            }
        </style>
        <script>
        </script>
    </head>
```

- Create a function called ```changeColor()```.

```html
        <script>
            function changeColor(){
            }
        </script>
```

- Now lets find the element we want to modify with Javascript. 

```javascript
    document.getElementById("change-this").style.color = "blue";

```

- Lets print something out to make it more fun. 
```javascript
function changeColor(){
    document.getElementById("change-this").style.color = "blue";
    console.log("wooohooo we changed color.")
}
```
- Lets try out our code 😊.
