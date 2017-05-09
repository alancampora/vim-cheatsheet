# vim-cheatsheet
My own examples to recall useful vim commands 

## Inner blocks 

Replace content between brackets: move cursor to content and then press `ci{` or `ci}` (saying to vim: "change inner content of curly brackets")

```javascript
function(){
    console.log();
}
```

press: ci{

```javascript
function(){
    >>cursor here to insert new content
}
```
