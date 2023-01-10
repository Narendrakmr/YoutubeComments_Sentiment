Performed a detailed sentiment analysis of the comments that is in the form of text and emojis.

Tracing of wordcloud 

At first performed an oral visualization of the dataset containing 691400 rows * 4 columms . 
Various tools used to perform EDA but mainly I prefered Alteryx to clean and filter the data set. 
After the EDA done once it was ready for further analysis then the dataset imported to Jupiter notebook and with the help of Pandas 
done many type of data many types of data manipulation. Since the column upon which analysis is supposed to be done is in the form of text 
and then with the help of TextBlob polarity converted into numeric form that can be either +1 (for positive sentiment) and -1 (for negative sentiment).
once for particular comments the polarity generated then I am able to group the dataset into two parts one containing positive comments and other 
negative comments . For both such type of dataset a word cloud can be generated with the help of TextBlob.

Tracing of Emoji graph 

Although the dataset was very bulky and due to some limited resources this was done on first one thousand sample of the dataset.
With some iterable statements emojis can be extracted from the comments column . Here the main challenge was to convert the emojis dataset in the 
dictionary format having key:(the type of the emoji) and value:(frequency of the particular emoji).
Now extraction of keys and values done in two different lists and then plotted bar graph (X-axis containing type of the emoji & Y-axis 
containing frequency of the emojis) and pie chart with the help of plotly.