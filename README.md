bookkeeper
==========

app demonstrate CRUD(CREATE, READ, UPDATE and DELETE) operations on Book Entity using symfony framework

Details of Controllers performing actions:
indexAction() :Display all the books
showAction($id): Shows individual book
newAction(): Displays new book details form and upon on submit will call createAction(Request $request) controller.
createAction(): performs validation of entered details and stores the book in the date base else shows error message

 editAction($id): This controller shows the editable book form and upon submit calls updateAction(Request $request, $id)
updateAction(Request $request, $id): performs validation of edited details and if valid stores the book in the database else shows error message

deleteAction(Request $request, $id): Deletes the book with given id and redirect to home page


