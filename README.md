# typescriptSearchBarHelper
A search bar helper class created with TypeScript

Add the TypeScript class to your scripts folder.

Then in your view: 
<script>
//To initialize
    var gridId = 'CoachRosterGrid';

    //1st param is the gridId
    //2nd param is an array of fields you want to filter by (the helper uses the text in the search box on the page.)
    var helper = new SearchBarHelper('CoachRosterGrid', ['FirstName', 'LastName']);

//To use
helper.filterGrid(gridId);

</script>
