# Dynamic Resume Building App
_____

### Folder structure
  * css/style.css
  * js/main.js
  * data/data.json
  * assets/img/
  * index.html
  
### Software requirements
  * CSS (Flexboxes & Media queries)
  * HTML-5 (Semantic-elements)
  * JavaScript (Promises - fetch)
  * VS-code
  * 200 OK (Web server for chrome)
  
### Code- structure
```html
    <html>
      <head></head>
      <body>
        <header> Resume Building App </header>
        <main class="parent">
           <section class="child1">
             
          </section>
          
          <section class="child2">
             
          </section>
        </main>
      </body>
      <script src="js/main.js"> </script>
    </html>
```

#### JavaScript
```javascript
    fetch('data/data.json').then()
```

#### data.json
```json
    {
      "profile":{
        "basics":{
          "name":"xxxxxxxxxx",
          "email": "xxxxx@xxxxx.xx",
          "address":"xxxxxxxxx"
         }
      },
      "summary":[
        "summary1","summary2"
      ]
    }
```
