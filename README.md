Problem 1 – scraping quotes
Scrapes all the quotes, authors, tags and author page hyperlinks from quotes.toscrape.com. Your code
should meet the following conditions:
1. All pages should be scraped,
2. Pagination (going from a page to the next one) should be handled using the hyperlink behind
“Next” button (instead of changing URL inside the for loop as we did in the classroom),
3. The tags for a given quote, should be separated from the tags of other quotes. (expected output
for the first two quotes: [ [“change”, “deep-thoughts”, “thinking”, “world”] , [“abilities”,
“choices”], … ]

Problem 2 – scraping movies
Scrape all the top 100 movies from the following page: https://www.imdb.com/chart/moviemeter/.
Your code should meet the following conditions:
1. You should not use the pd.read_html(…) function. Instead you should use scrapy and css
selectors.
2. Your output should be a DataFrame with the following movie information:
a. Title,
b. Year
c. Ranking,
d. Rating,
e. Hyperlink (movie page url).
Note: cleaning data (e.g. removing brackets from year etc.) is not required, yet highly encouraged (at
least trials).
Problem 3 – scraping books
Scrape all the books from books.toscrape.com. The following info should be scraped:
1. Title,
2. Rating,
3. Price,
4. URL to book page,
5. URL to book picture,
6. In stock or not.
Note: cleaning data (e.g. removing British pound sign from price etc.) is not required, yet highly
encouraged (at least trials). Using functions and classes is optional yet highly encouraged
