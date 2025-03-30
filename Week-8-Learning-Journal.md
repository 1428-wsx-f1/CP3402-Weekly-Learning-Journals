# Week 8 Learning Journal

## Learning Activities And Resources
- Lecture
- Lecture Recordings

Links:
- [Original Learning Experiment Document](https://docs.google.com/document/d/1n1iV3FdM8Ov0N6YiNnf0K8U3Gprw1wopmQhCd_-2ZGM/edit?usp=sharing)
- [Appendix](https://docs.google.com/document/d/1cj4U1r27M1ENYgjE4w8wEAz0AvM_rayBXhMiKikGBNA/edit?tab=t.0)
- [WordPress Theme Handbook](https://developer.wordpress.org/themes/)


Learning Experiment: Classical Vs Metal Music Genres


Alternate Hypothesis:
Studying while listening to classical music compared to metal music will result in a higher average test score.

Null Hypothesis: Studying while listening to classical music compared to metal music will not result in a higher average test score.

The experiment will be set up using ChatGPT as follows:
+ Transcribe notes for topic 1: Introduction to Psychology
+ Read over notes
+ Take a 5 minute break
+ Complete the three related tests
+ Transcribe notes for topic 2: Introduction to Economics
+ Read over notes
+ Take a 5 minute break
+ Complete the three related tests
+ Calculate the average result from the three tests for each topic
+ Calculate the significant difference
+ Discuss result


Prompts Used: 
+ Can you generate a course for two different subjects with the same difficulty. The course for each subject must be at least 1 hour long, i will be writing your notes down on paper so take this into consideration. 
At the end of each subject I want you to generate 3 lists of 10 questions for each subject. Withhold the answers to all questions until I ask in my next response.
+ Can you please fill in the dot points you provided as part of your course
+ Keep everything the same except i need three sets of 15 multiple choice questions for each subject

Control Variables: Knowledge on topics (basic), Environment, Time (1 hour)


<img width="474" alt="experiment-results" src="https://github.com/user-attachments/assets/92b97e93-e190-4df1-b24a-db49dc4578cb" />


Conclusion:

Results from this learning experiment have proved the null hypothesis to be true and the alternate hypothesis to be false. This is due to the calculated P value being greater than 0.5 which indicates no significant difference. 
These two genres were chosen because classical music is more relaxing and allows for clear concentration. Metal music meanwhile was percieved to be more chaotic and distracting.

There was a limitation in terms of the quality of tests provided by ChatGPT. For example, in set 2 of the multiple choice tests for psychology there was a question on mixed economies. Additionally, in the second topic questions
were repeated. For example “In a mixed economy, the role of the government is to” was asked twice. Furthermore, there was a question on production possibility curves which was not included in ChatGPT's notes.

A redirection for this learning experiment would be to test how listening to any music compared to no music at all will affect test scores.


## Estimated Hours
This week I spent 3 hours learning for this subject.


## Content Insights
WordPress custom themes must be reusable, meaning nothing is hard coded. Starter themes are used as a blank template, which saves a large amount of time with unnecessary coding unrelated to the theme itself. Template files are 
modularised in order to generate different parts of the theme (e.g. header.php). During this process it is important to refer to the WordPress hierarchy, to understand which section of the page each PHP file modifies. 

The style.css file is crucial for including details about the theme in order to ensure WordPress loads it properly. A file header with the following details is required: Theme Name, Theme URI (URL of web page where 
users can research further details about the theme), Version, Author, Text Domain (for translations), Tested up to (WordPress version), Requires at least (WordPress version), Requires PHP (version), Licences and Licence URI. Within this file additional customisation can be performed. For example, changing the background colour or font as a normal style.css file would.

WordPress also comes with a functions.php file. This file acts as a WordPress plugin and allows the addition of custom PHP functions, classes, interfaces, etc. When activated though, a child themes functions.php will 
load before a parent themes. This file can also be used for adding actions or filters to hooks (entry points to extending WordPress' functionality to add custom code), theme setup functions, loading scripts and styles 
and include other PHP files.

When producing themes in WordPress, regular testing is recommended. A local environment is valuable for providing a controlled space to develop a theme outside the live production site. In addition, it is 
important to make sure the theme can handle a variety of content. To do this there is theme unit test data available online as an XML file containing a collection of posts, pages, comments and media.
For example, [Theme Test Data](https://github.com/WordPress/theme-test-data/blob/master/themeunittestdata.wordpress.xml).
In the theme file 
debugging can be enabled via the wp-config.php file. This PHP file will log errors, notices and warning to a debug.log file. As mentioned in the week 4 learning journal, a staging environment should be used alongside the 
local and live as part of a workflow for development and integration of the website.


For themes in WordPress, a different PHP control structure is used to allow for improved mixing between PHP and HTML.
<img width="662" alt="Screenshot 2025-03-30 234245" src="https://github.com/user-attachments/assets/562f84a4-9677-4ffe-ba7a-4faaad368189" />

The inclusion of "endif" compared to a "}" improves readability as it is easier to identify. This method allows for direct HTML, without the need for embedding HTML through echo statements. Once themes are complete 
they are zipped and can be hosted on the WordPress.org repository as a primary or additional source of individual income.



## Career/Employability/Learning Insights
From the learning experiment this week, I uncovered that the genre of music I listen to has little impact on my learning. This challenged my initial belief that music with vocals/lyrics would distract my learning as the words spoken in the songs
would conflict with my thoughts. I have also discovered that creating WordPress themes could be a potential side hobby for making money. Currently there are over 31,000 themes available both free and paid. The average wordpress theme can 
sell for anywhere between $25 to $250. This means if I created a theme and sold it for $120, this theme could generate $60,000 in total from just 500 unit sales. Interestingly, I also found a website called UpWork where users post jobs
and developers can take on these jobs on a fixed cost or hours needed basis. Freelance jobs for WordPress themes (creating and fixing issues) were available, paying as high as $4,000. This website also includes jobs for other areas such as PHP, Javascript, UI design, HTML and more.

