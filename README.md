# CMSC320 Group Project: What Explains a Goodreads Rating?

## Group Members

- Chaitra Bhumula
- Anushmita Dey
- Emily Ho
- Riya Khatri
- Aakankshya Koirala

## Links

- **GitHub Repository:** https://github.com/akoiral1/CMSC320-Group-Project
- **Dataset:** [GoodReads Best Books (Kaggle)](https://www.kaggle.com/datasets/thedevastator/comprehensive-overview-of-52478-goodreads-best-b)

## Dataset

The dataset contains information for 52,478 books on Goodreads' Best Books Ever. It can be used to analyze trends for highly rated books, since it includes data like ratings, rankings, genre, pages, awards, and prices.

## Why

According to the National Literacy Institute, about 21% of American adults have low literacy skills, and more than half read below a sixth grade level (Barnes). Reading is a skill that is maintained through practice, and for many people the hardest part is picking something they will actually finish reading. This made our group start thinking about how people choose books in the first place. Most of us rely on a star rating without asking what that means. So we decided to use Goodreads data to find out how much a book's rating can be explained by things like genre, length, publication year, and how many people rated it.

In this way, we can encourage others to read more based on genres they've enjoyed reading in the past and choosing books that fit their interests. This also makes it really easy to pick up reading as a hobby, or help people continue it.

## Preliminary Ideas

### Hypothesis Testing

- Check whether books in a series are rated differently from standalone books.
- Check whether ratings differ across genres or publication decades.

### Exploratory Data Analysis

- Clean the data by parsing and cleaning missing and duplicate values, flagging outliers, etc.
- Create visualizations of average ratings by genre, as well as relationships between variables like series and standalone books.

### Machine Learning

- Predict a book's rating from things like genre, length, and year, and compare that to predicting how many people rated it, since being widely read and being well liked may not be the same thing.
- The dataset is very large, which gives us enough training data to build an accurate ML model.
- The dataset also includes information about several aspects of books, including the title, rating, description, and awards, which can allow for a more specific prediction.

## Citations

Barnes, Gustave. "The Literacy Crisis in America." USA Reads, 4 Nov. 2025, usareads.org/the-literacy-crisis-in-america/. Accessed 24 Sept. 2026.

The Devastator. "GoodReads Best Books." Kaggledatasets, 2 Jan. 2023, https://www.kaggle.com/datasets/thedevastator/comprehensive-overview-of-52478-goodreads-best-b. Accessed 24 Sept. 2026.
