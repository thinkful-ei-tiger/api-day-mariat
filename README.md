## Shopping List Starter

#### Created for the Thinkful EI Program.

1. Test an AJAX call to our API.
2. Create a new api module to handle all the API calls your application will make. Add it to your src directory.
3. Write a getItems() function that will make a GET request to /items and return the promise.
4. Write a createItem() function that will make a POST request to /items, sending JSON in the request body, and return the promise.
5. Use the api module's getItems() method to fetch data, place it in the store, and re-render the page.
6. Modify the shopping-list module's handleNewItemSubmit() to call api.createItem(), then place the response item in the store, then re-render.
7. Write an updateItem() function in your api module that takes 2 arguments: an id, and an object containing key-values intended to be updated.
8. Write a findAndUpdate function in your store module that takes 2 arguments: an id, and a newData object containing new key/value pairs to merge into the current store object.
9. Wire up the methods for editing the item name and toggling the item's completed property to use the new findAndUpdate methods in your api and store modules.
10. Get the delete action working completely in your app, syncing with the server
11. Add error handling to all your api functions.
