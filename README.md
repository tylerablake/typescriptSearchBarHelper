# typescriptSearchBarHelper
A search bar helper class created with TypeScript

Add the TypeScript class to your scripts folder.

Then in your view: 
```html
<script src="~/Scripts/ts/SearchBarHelper.js"></script>
<script>
//To initialize
    //1st parameter is the gridId
    //2nd parameter is an array of fields you want to filter by (the helper uses the text in the search box on the page.)
    var helper = new SearchBarHelper('GridId', ['FirstName', 'LastName']);
</script>
```
