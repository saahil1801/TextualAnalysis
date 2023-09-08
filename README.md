# TextualAnalysis
Extracting textual data articles from specified URLs and performing text analysis to calculate various variables 

Data Extraction:

I have successfully completed the data extraction task as outlined in the assignment. Here's a summary of the steps taken:
I began by utilizing the provided input data in the form of an Excel file named "Input.xlsx."For each article mentioned in "Input.xlsx," I meticulously extracted the textual content. This involved a careful process to ensure that only the relevant article title and the main article text were extracted.To maintain organization and traceability, I saved each extracted article as a separate text file. The file name for each article was derived from its unique URL_ID.During the extraction process, I took great care to exclude any extraneous content, such as website headers, footers, or any unrelated information. Only the meaningful article content was retained.For the data extraction phase, I employed the Python programming language and made use of Selenium to perform web scraping efficiently.

Data Analysis:

I have also successfully completed the data analysis phase of the assignment. Here's a summary of the steps involved:After extracting the text from each article, I conducted thorough textual analysis.
The objective of the analysis was to calculate and compute the various variables specified in the "Output Data Structure.xlsx" file. These variables cover aspects such as sentiment, readability, and linguistic characteristics.To ensure conformity with the assignment requirements, I organized the computed variables in the exact order as outlined in the "Output Data Structure.xlsx" file. This meticulous attention to detail was critical to meet the assignment's expectations.Throughout the data analysis process, Python programming was exclusively utilized to implement the required calculations and generate the desired results.

These variables provide insights into the characteristics of the extracted textual data. Here's a description of each of the variables mentioned in the assignment:

Positive Score: This score measures the positivity or positive sentiment in the text. It indicates the degree of positive language or emotions expressed in the article.

Negative Score: This score quantifies the negativity or negative sentiment in the text. It represents the extent of negative language or emotions conveyed in the article.

Polarity Score: Polarity score indicates the overall sentiment polarity of the text. It can be calculated as the difference between positive and negative scores or as a normalized value between -1 (negative) and 1 (positive).

Subjectivity Score: Subjectivity score measures how subjective or objective the text is. A higher score suggests that the text is more subjective, while a lower score indicates objectivity.

Average Sentence Length: This variable computes the average number of words per sentence in the article. It provides insights into the article's readability and complexity.

Percentage of Complex Words: It represents the proportion of complex words in the text. Complex words typically have multiple syllables and are considered to be less common in everyday language.

FOG Index: The FOG (Gunning FOG) index is a readability index that estimates the years of formal education required to understand the text. It considers sentence length and the percentage of complex words.

Average Number of Words per Sentence: This variable calculates the average sentence length in terms of the number of words. It provides a simpler measure of sentence length compared to characters or syllables.

Complex Word Count: This count indicates the total number of complex words present in the text. It is useful for assessing the text's vocabulary richness and complexity.

Word Count: Word count measures the total number of words in the article. It provides a basic measure of the article's length.

Syllables per Word: Syllables per word is the average number of syllables in each word in the text. It helps assess the linguistic complexity of the vocabulary used.

Personal Pronouns: This variable counts the number of personal pronouns (e.g., "I," "you," "he," "she," "we," "they") used in the text. It provides insights into the author's perspective and engagement with the audience.

Average Word Length: Average word length calculates the average number of characters in each word in the text. It can be an indicator of the article's style and vocabulary.
