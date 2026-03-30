<b>Analysis of the book reading service database</b>

<b>Project goal:</b> To analyze the database of a large book subscription service.

It contains information about books, publishers, authors, and user reviews. This data will help formulate a value proposition for the new product.

<b>Data Description</b>

Table `books`:

Contains data about books:
- `book_id` — book identifier;
- `author_id` — author identifier;
- `title` — book title;
- `num_pages` — number of pages;
- `publication_date` — book publication date;
- `publisher_id` — publisher identifier.

Table `authors`: 

Contains data about authors:

- `author_id` — author identifier;
- `author` — author name.
  
Table `publishers`

Contains data about publishers:

- `publisher_id` — publisher identifier;
- `publisher` — publisher name;

Table `ratings` 

Contains data about user ratings of books:
- `rating_id` — rating identifier;
- `book_id` — book identifier;
- `username` — name of the user who left the rating;
- `rating` — book rating.

Table `reviews`

Contains data about user reviews:
- `review_id` — review identifier;
- `book_id` — book identifier;
- `username` — name of the reviewer;
- `text` — review text.

Let's count how many books were published after January 1, 2000;

For each book, we'll calculate the number of reviews and the average rating;

We'll identify the publisher that has released the largest number of books longer than 50 pages—this way, we'll exclude brochures from the analysis;

We'll identify the author with the highest average book rating—considering only books with 50 or more ratings;

We'll calculate the average number of reviews from users who have rated more than 48.
