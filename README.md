## How it work
- User visits Book page through URL `/books/`. </br>
- Django uses [URLconf](./demo/urls.py) to determine that view `book_list` to be called. </br>
- View [`book_list`](./books/views.py) gets all data from model [`Book`](./books/models.py). </br>
- View pushes list of books data to template [`book_list.html`](./books/templates/books/book_list.html). </br>
- Template use for loop to display information of each book. </br>
- Then generate a html page and sends/responses to User and is displayed on browser </br>