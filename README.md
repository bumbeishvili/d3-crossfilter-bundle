# d3-crossfilter-bundle

Inspiration - https://dc-js.github.io/dc.js/


## Precondition

* [ ] User will have data like following format  
```javascript
var data = [
             {
               prop1:1,
               prop2:false,
               prop3:"prop3"
             },
              {
               prop1:1,
               prop2:false,
               prop3:"prop3"
             }
 ]

```


## Expectations
* [ ] User will be able to initialize bundle using following 
``` 
  var d3CrossBundle = d3crossbundle()
                         .data(data)
                         .inside("#myDiv") // can be raw node, selector string or  d3 selection
                         .run()

```


## Chart types

* [ ] Grid
  * [ ] Paging
* [ ] Bar chart
  * [ ] Clickable bars
