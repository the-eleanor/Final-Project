# Final Project Paradata: Cookbooks and Women's History

This is the paradata accompanying my Cookbooks and Women's History project, which can be found [here](http://the-eleanor.github.io/Final-Project/index.html).

## Introduction and Aims

This project was developed for Dr. Shawn Graham's Crafting Digital History course (HIST3907O) at Carleton University. My own background is as an undergraduate student in her third year of pursuing a BA in History at Carleton, with interests in women's history and food history.

My aim for this project was to depict how cookbooks can be used as a viable and useful source of data to determine information about women's lives during the time period the cookbook depicts. By using a dataset consisting of historical cookbooks, I sought to show how information about women's experiences could be determined using an unconventional source. I attempted to use digital analysis methods, using online tools to extract and depict information. I then analyzed these results; this involved finding trends in word usage, discussing specific passages within the cookbooks, and comparing information in the cookbooks to the historical events contemporary to the time period.

## Research Sources

The dataset used in this project was Michigan State University's [Feeding America: The Historic American Cookbook Dataset](https://www.lib.msu.edu/feedingamericadata/). It is a compendium of 76 cookbooks from 1798 to 1922. It was chosen due to my own interests in cooking, and was applied to the topic I chose due to my own interests in women's history. 

The most valuable places to find secondary sources for this project were on scholarly databases like JSTOR. I obtained other articles discussing the historic significance of cookbooks through this site. I also downloaded the articles I found, as a precautionary measure. 

Some of the sources I found, especially through JSTOR, focused on a later time period in regard to cookbooks – this is understandable, as cookbooks became significantly more common and fashionable toward the mid-20th century. However, they still allowed me to prove my point, which was that cookbooks are a site for women's experiences. I also found a source through Google Scholar (the piece by Hélène Le Dantec-Lowry) and one source entirely by accident through Google Images (the Smithsonian Library online exhibit by Erin C. Clements) that related more closely to cookbooks in the 19th century.

Secondary sources:

Boles, Frank. "'Stirring Constantly': 150 Years of Michigan Cookbooks." _Michigan Historican Review_ 32.2 (2006): 33-62. http://www.jstor.org/stable/20174168

Clements, Erin C. "The Making of a Homemaker" digital exhibit by _Smithsonian Institution Libraries._ 2003. http://www.sil.si.edu/ondisplay/making-homemaker/intro.htm 

Le Dantec-Lowry, Hélène. "Reading Women’s Lives in Cookbooks and Other Culinary Writings: A Critical Essay." _Revue française d’études américaines_ 2.116 (2008): 99-122. https://www.cairn.info/revue-francaise-d-etudes-americaines-2008-2-page-99.htm 

I did not end up actually using the following article, but I found it an interesting article regarding food history nonetheless.

Elias, Megan. "Summoning the Food Ghosts: Food History as Public History." _The Public Historian_ 34.2 (2012): 13-29.  
http://www.jstor.org/stable/10.1525/tph.2012.34.2.13

Introduction picture initially found on [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Good_housekeeping_1908_08_a.jpg) and cropped.

## Process and Tools

I found a basis for my theory in the secondary sources I used, with a few explaining that cookbooks, indeed, were a useful source of history. Because these tended to focus on mid-20th century cookbooks, I also looked up some basic information about 19th century women's experiences to add to the knowledge I had going into the research.

To prove this, I took the dataset of cookbooks and placed it in Overview. Overview was my most useful resource in this endeavour, due to the fact that it allowed me to search multiple documents for keywords and then examine the occurrences of those words within the documents. It was a constant companion with this project.

My first course of action was to create a graph showing the frequency of many of the keywords. I chose words I felt would reflect women's experiences during this time, and Laurel Rowe recommended a couple of extra words to me. I was unable to use words such as “war” (these cookbooks encompass both the American Civil War and World War I) and “man” or “men,” due to that Overview's multisearch included words that contained those letters and surrounding them in quotation marks yielded no results. I graphed the amount of cookbooks each word appeared in within the dataset, with a maximum value of 76. I used the site “Online Chart Tool” because it seemed to be a very straightforward site to use to produce a graph. I then analyzed the results of the graph.

I also wanted to make a word cloud of a few of the cookbooks. I found Overview's word cloud tool fairly useless, however, as I did not know how to filter its results and it only reflected the entire dataset, not individual files. I instead turned to Lexos, as recommended to me by. It allowed me to filter through the results using custom stop word lists.

I attempted to filter out many of the words involving cooking and ingredients, but this ended up being an amazingly difficult endeavour. I could not find an exhaustive list of food names and cooking terms online, and my own attempts were limited. I did, however, utilize an online list of common stop words (found on Ranks NL through a quick Google search) to reduce the amount of common terms in the word clouds. Once I attached the text file of stop words, Lexos continued to ignore them. I realised that the list I had found online, as well as all of the words about cooking that I already compiled off the top of my head, were divided by line breaks instead of by commas. Instead of going through the hundred-plus words manually to add commas, I actually utilized some regular expressions to find all of the line breaks and replace them with commas. I found the string to use with a search online, and it worked. 

I also used Voyant, as it seemed to provide a more thorough cloud for “The American Woman's Home” by Harriet Beecher Stowe and Catharine Esther Beecher. I uploaded that specific document to the site and took the resulting word cloud. I continued to use Lexos for the other two clouds, depicting the commonality of the word “Mrs,” because I had already scrubbed that data and had it ready to go. I was unable to determine anything of significance when producing a word cloud of the entire dataset using Lexos, and Voyant did not let me upload more than one document at a time and thus could not be used for this goal.

In creating the website for my project, I chose to use the Github Page Generator. It provided an attractive and simple way to display the results. I initially wanted to go with the Merlot theme, as I found it stylistically attractive and relevant to the feel of the older subject matter. However, the text on the chart became difficult to see due to size, and the colourful text of the word clouds did not fit the mellow tones of the layout. I instead chose the Cayman theme, as I found it was simplistic enough that the colourful clouds did not clash with it and the chart was more visible. I had initially envisioned placing my paradata on another page of the same site, but in the end it was easier just to create a markdown file in the same GitHub repository. This repository also includes the graph, word clouds, and my stopword list.

I created the site not realising that it would be converted into HTML and I would not be easily able to get back to the markdown version of it. I had not quite finished adding everything, so I ended up drawing on the very basic (and probably outdated and not very neat) knowledge of HTML I had learned years ago to add some of the pictures and links. I also centred each section title while I was at it, as I felt it was more visually pleasing that way. I also found an image from a housekeeping magazine from the early 20th century on Wikimedia Commons that I thought would make a good header, and added it.

## What Worked and Where to Go

The content of the cookbooks certainly reflected what I wanted to prove. I was able to find ample information about women's lives, especially during the late 19th and early 20th century. The two most useful documents within the dataset were the aforementioned “The American Woman's Home” and “Mary at the Farm and Book of Recipes” by Edith M. Thomas. “The American Woman's Home” was a clear example of the expectations and lives of mid-19th century women, and “Mary at the Farm” contained a large passage regarding growing support for women's suffrage. These and several of the other passages of the cookbooks showed just how useful these old cookbooks could be when researching women's history.

Overview was, as mentioned, an incredibly useful tool in going through all of the information. It allowed me to find out which documents contained the most information, and also gave me a broad view of the information in order to make further decisions of where to go with it. I found that Lexos and Voyant were both useful tools in their own ways, especially in terms of depicting data. Lexos does not come pre-equipped with a stopword list, and I was able to use both online resources and what I had learned during the course (especially regular expressions) to develop a list with useful terms in the proper format. 

This project could certainly be built upon, as it is by no means whatsoever an exhaustive account of the correlation between cookbooks and women's history. One might apply this line of research to cookbooks from other eras to depict the experiences of women from these time periods. As well, a more thorough examination of this period, perhaps with a larger sample group of cookbooks, might reveal even more correlations between the social expectations of women during a given time and the information provided within the books.

## Productive Failure and Final Thoughts

The biggest flaw with my plan was that I was attempting to depict qualitative information with the frequently-qualitative analysis tools provided within this class. I played around with multiple analysis and visualization tools such as DocuBurst (which only took individual text files and claimed it found no recognisable words when I entered the “American Woman's Home” book into it) and Gephi (I was not sure how to effectively use it to depict anything in particular), trying to enter the dataset into them before realising that they would not be useful in helping me depict my point. 

The dataset was also very hard to use for the purpose – the amount of words about food and cooking told me nothing about my project's goal, and they dominated most of the word clouds and visual depictions of the data. Despite all my efforts to extend my list of stop words when scrubbing the text, they felt impossible to weed out. As well, even if there words that specifically related to women's history within the text, often they would only appear a few times verbatim, even if the text discussed the subject thoroughly, making them hard to visualize upon extracting.

Throughout my project, I kept finding new tools that would assist me better, which meant that I was not able to focus thoroughly enough on any one of them to fully utilize it properly. I know that there were probably better tools and ways to go about this project, but between lack of time and lack of experience, I was not able to find a way to present the information that accurately reflected my points. I had ideas for creating timelines to depict word usage over time, but they never came to fruition because I did not know if I could find the right tools and whether or not it would even be worth the time – due to the variety in contents of the cookbooks, it may not have provided any trends whatsoever.

While I definitely feel that the point of my project is still valid, it was not appropriate for this course's final project and did not allow me to utilize the tools I had learned to use from the module exercises. I feel that I could have done a much better job with this final project if I had chosen a different topic to use with this dataset, relying more heavily on the ingredients and recipes in the data rather than other excerpts and advice. I recognise that the dataset contains a huge amount of information that could be used to make any number of points about history, but not all of them were appropriate for this course. This likely includes my own topic.

The last issue was my own fault: a complete lack of proper time budgeting that led to an inability to produce something more in-depth. I usually provide myself more time with schoolwork, but I severely underestimated the time that this project would take me. I have certainly learned my lesson, considering how much stress it led to down the line. I regret this mistake bitterly.

I learned a lot from this experience, which is why I do believe it is appropriate to call it a productive failure, even if it certainly feels like a failure. I wish that I had been able to more accurately depict the methods and tools I learned in this course. I should have thought more carefully about how to use my data, as well as which tools to use to depict what I wanted to prove with it. It was hasty to pick a topic without being more careful about how I would go about proving it. I should also be more careful and aware of how much scrubbing the data might need in order to find the information needed. Lastly, I need to remember that things take time, especially projects using tools that I am new to, and to give myself a more reasonable amount of time to work with. 

Still, I think that despite all of these shortcomings and issues, I was able to learn both what to do and not to do in a project like this, and also a surprising amount about just how useful cookbooks are. I knew from past experience that turning to unusual sources for history often yields useful results, which is why I chose to do this topic. However, I was also intrigued by just how wide a variety of information the cookbooks contained, and even the different forms they took. I am very accustomed to the format of modern cookbooks, and it was fascinating to see how different cookbooks contained different information about things that were not directly about cooking recipes.

As I keep telling my friends, life is a learning process, and I certainly learned a lot about digital history from this project and this course, even if it did not always work out the way I wanted it to.
