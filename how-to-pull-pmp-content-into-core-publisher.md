#Core Publisher: Pulling and displaying stories from the Public Media Platform

There are two ways to pull PMP stories into your CP site. We'll cover those first, then we'll show [how to organize the display of stories on pages by topic, byline, etc.](create-landing-pages.md)

##Pulling stories into Core Publisher

###If you know the GUID of a specific PMP story you want:

1 Click on Find Content in the top navigation. 
2 Click the “Pull PMP Doc” tab. 
3 Paste the PMP story GUID into the Search term box.
4 Click the Get document button. 

You'll see a green box with a link to the story. Click the story link and it opens as a web page. You can now edit the story to assign it to a Category, add Tags, or relate it to a Program. This is how you can organize PMP stories on your Core Publisher page by Category, Tag, or Program, which we'll get to in a minute.

###But what if you don't know the GUID of the PMP story?

You can search for PMP stories, and find the GUID for each story you find, on the PMP support site here: 

https://support.pmp.io/

Click on Advanced Search to narrow your search, or simply use this url which does the same thing:

https://support.pmp.io/?advanced=1&profile=story&has=image

###There are also several ways to search the PMP for stories from inside Core Publisher:

1 Click on Find Content in the top navigation. 
2 Click on Search PMP docs.
3 In the Text search box, enter a search term. 
4 In the Filter By section, for the Profile select Story. There isn’t much point in searching for just an image, audio, or video if you want to pull in a complete story.
5 In the Creator and Program dropdown menus, make a selection to narrow the search, or leave the default All to search everything in the PMP.
6 Hit the Search button and see the results appear below.
7 Click on a story link to open it as a Core Publisher story page, and add a Category, Tab, Related Program, etc.

#### Options for fine-tuning your search

* To search just titles, you can enter title:election. 
* If you want a really specific search, you can enter something like title:”election results” which will find only stories with that exact phrase in the title. (Important: if your search term is more than a single word, enclose it in quotes.)
* To search for stories containing a subject in the body of the story, just enter the subject as a Search term without “title:” in front of the term. 
* In the Tag(s) box you can enter one tag or more separated by a space. This will find all stories so tagged. Tags are more specific than a Text search, so are likely to return fewer stories. 
* You can combine Text search and Tags to filter stories even further. 
* Note also that different producers use Tags in different ways, so a search for stories by Tags may produce inconsistent or incomplete results. 


Your search may turn up no stories or too many stories. You can adjust your search and hit the Search button again as needed. 

####Ways to super-fine-tune a PMP search

In the Search Term box you can use these prefixes to further narrow the search:

title:”search term”
teaser:”search term”
tags:”search term”
content:”search term” (seems to return fewer results that just ”search term”)
byline:”name”

##Creating a section page that displays one or more stories pulled from the PMP

There are at least three ways to create a landing page for a project or subject area, where you can pull in stories for the project or subject. The first two methods are very similar:

Create either a Category or Tag for the subject or focus of the page. Examples could include:

Election
Environment
Health Care
Anything else you want

If you create a Category or Tag, CP will create a page for it with a url of http://yoursite.org/term/categoryname. 

The third method of creating a project or subject landing page is to create a Topic page. A Topic page for (e.g.) the topic of Health Care will have a url like this: http://yoursite.org/topic/health-care

The only real difference with a Topic page is that you can associate it with up to five different Tags. So any story tagged with any of the associated tags will display on the Topic page. This might be handy when you want a landing page to display lots of existing stories that are tagged with different tags. For example, if we want a landing page for Health Care, and we know there are existing stories with tags like health, health care, hospitals, medicine, and wellness, we can simply add these as Associated Tags in the Topic page. Stories tagged with any of these will instantly display on on the Health Care topic page.

Adding PMP content to a Topic page is the same as for a Category or Tag page: Go to Find Content and either Pull a PMP Doc by its PMP GUID, or Search the PMP docs to find one or more stories you want to pull. Either way, after you pull a story you need to click the story Edit tab and add a Tag associated with the Topic Page.
