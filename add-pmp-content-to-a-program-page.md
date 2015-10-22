#Add PMP content to a Program page

You can pull in PMP content to an existing Program page, or create a new Program page and set up an automatic hourly pull of content from the PMP. 

1. In the Core Publisher control panel click Configure Corepublisher.
2. Under Content Management click Get PMP Content.
3. Assuming the API Settings are filled in, click the Queries tab.
4. Click the Add Query button to open a new Query form.
5. Begin filling out the form with a Query name. 
6. Use the Program dropdown to select which programs you want to pull PMP content from.
7. Use the Creator menu to select a content source as desired. 
8. You can limit the number of stories pulled from the PMP per hour for this query, but a good number is 10. 
9. Under Profiles just check “story.” 

##The “Search text” and “Tags” fields are the heart of the query. Here are all the ways to use them:

* In the Text search box, enter a search term.
* To search just titles, you can enter title:election.
* If you want a really specific search, you can enter something like title:”election results” which will find only stories with that exact phrase in the title. (Important: if your search term is more than a single word, enclose it in quotes.)
* To search for stories containing a subject in the body of the story, just enter the subject as a Search term without “title:” in front of the term.
* In the Tag(s) box you can enter one tag or more separated by a space. This will find all stories so tagged. Tags are more specific than a Text search, so are likely to return fewer stories.
* You can combine Text search and Tags to filter stories even further.
* Note also that different producers use Tags in different ways, so a search for stories by Tags may produce inconsistent or incomplete results.

Your search may turn up no stories or too many stories. You can adjust your search and hit the Search button again as needed.

###Ways to super-fine-tune a PMP search

In the Search Term box you can use these prefixes to further narrow the search:

* title:”search term”
* teaser:”search term”
* tags:”search term”
* content:”search term” (seems to return fewer results that just ”search term”)
* byline:”name”

##Now adjust the "After stories have been created" section

You can assign this query to a Category, so the PMP content will automatically get pulled into that Category's page.

You can also assign the query to a Program, so the PMP content will automatically go to that Program's page.

You can also assign the query to both a Category and a Program, and it will appear on both pages.

##Caveats

Queries set up in this way probably won't pull in PMP content right away. Content may begin to appear within 3 hours, but don't be alarmed if it takes up to a day.

Once the query is up and working, it should pull any fresh PMP content that matches the query about once an hour.

You can publish PMP content instantly on Program, Category, Tag, and Topic pages by using the [Find Content method of Pulling PMP content into Core Publisher](/pulling-pmp-content-into-core-publisher.md).
