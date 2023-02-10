# FlexBox  
##### to centeraize an object :  
```
div.parent {
  display: flex;
}
  
div.object{
  margin: auto;
}
```  

##### to create a grid of boxes:  
```
div.parent{
    max-width : 1200px;
    display : flex;
    justify-content : center;
    flex-wrap : wrap;
    margin: 20px auto;
  }

  div.box{
    width : 250px;
    height: 300px;
    background-color: brown;
    margin: 10px;
    padding: 10px;
    box-sizing: border-box;

  }
```
---
## some notes:  
##### you can use ` flex-basis : x% ` instead of width.
##### you can use ` flex : x ` to resize width of a obj depended on other objects.
##### you can use ` flex-direction : column; ` you can flex objects in vertical way.
