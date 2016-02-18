#Pulling PMP Content into Core Publisher by Individual Story

The fastest way to get PMP content into Core Publisher is to find individual stories, and pull them instantly into your site. This has the advantage of allowing you to curate specific stories and put them wherever you want on your site. There are two distinct ways to do select and pull individual PMP stories. We'll cover those first, then we'll show:

- [How to create a landing page to display stories pulled from the PMP by category, tag, or topic](create-landing-pages.md).

- [How to set up an automatic, hourly pull of stories by program, category, or tag for display on Program or Category pages](/hourly-pull-to-a-page.md).

##If you know the [GUID](what-is-a-pmp-guid.md) of a specific PMP story you want

The GUID is a globally unique identifier assigned by the PMP to a story, image, audio, or video. You can find the GUID for a piece of content by using the [PMP search engine](https://support.pmp.io/). 

For more on PMP GUIDs, you can also see our documentation on [What is a GUID and how to use it](what-is-a-pmp-guid.md).

### Assuming you have the GUID of a story you want to pull into Core Publisher:

1) Click on `Find Content` in the top navigation, then click the `Pull PMP Doc` tab. Paste the PMP story GUID into the Search term box:

![PMP GUID pasted into the GUID box in Core Publisher]
(/img/pmp-pull-by-guid.png)

2) Click the `Get document` button. You'll see a green box with a link to the story:

![story from the PMP returned to Core Publisher]
(/img/pmp-story-pulled-by-guid.png)

3) Click the story link and it opens as a web page:

![story from the PMP ready to edit in Core Publisher]
(/img/pmp-story-pulled-page.png)

4) You can now edit the story to assign it to a Category, add Tags, or relate it to a Program. This is the most direct way you can organize specific PMP stories on your Core Publisher pages by Category, Tag, or Program.

##If you don't know the [GUID](what-is-a-pmp-guid.md) of a specific PMP story, search the PMP

### You can search the PMP for stories from inside Core Publisher:

1) Click on `Find Content` in the top navigation.

2) Click on `Search PMP` docs.

3) In the Text search box, enter a search term. Use quotation marks if you want to find an exact match.

4) In the `Filter by` section, for the Profile select `story`, unless you are searching for just an image, audio, or video element.

5) In the `Creator` and `Program` dropdown menus, make a selection (like `NPR`) to narrow the search, or leave the default `All` to search everything in the PMP. 

![search for PMP content by keyword in Core Publisher]
(/img/pmp-search-in-core-publisher.png)

6) Hit the `Search` button and see the results appear below:

![search for PMP content by keyword in Core Publisher]
(/img/pmp-story-search-results-in-core-publisher.png)

7) Click on a story link to see a short preview of the story as a PMP Document. You can `Cancel` if you don't want it, or hit the `Pull` button to add the story as a Core Publisher story page.

![PMP content preview in Core Publisher]
(/img/pmp-search-preview-core-publisher.png)

8) After you hit the `Pull` button you'll see a green box with a link to the story page. 

![PMP content preview in Core Publisher]
(/img/pmp-story-pulled-green-box.png)

9) Click the link to open the story as a Core Publisher post, then the `Edit` tab. You'll want to add a Category, Tag, and/or Related Program, which add the story to your category, tag, or program pages. 

10) Hit `Publish` and you're done.

Note that stories pulled from the PMP can't be pushed to NPR or NPROne, since they're already in the NPR system.

### Finding stories from PMP Partner websites

Instead of starting with a search for PMP content in Core Publisher, you might begin by finding stories you want on PMP partner websites, like Marketplace, PRI, and NPR. Then do your search using part or all of the story headline.

### Options for fine-tuning your search

* To search just titles, you can enter `title:election`. 
* If you want a really specific search, you can enter something like `title:”election results”` which will find only stories with that exact phrase in the title. (Important: if your search term is more than a single word, enclose it in quotes.)
* To search for stories containing a subject in the body of the story, just enter the subject as a Search term without `“title:”` in front of the term. 
* In the `Tag(s)` box you can enter one tag or more separated by a space. This will find all stories so tagged. Tags are more specific than a Text search, so are likely to return fewer stories. 
* You can combine `Text` search and `Tags` to filter stories even further. 
* Note also that different producers use tags in different ways, so a search for stories by `Tags` may produce inconsistent or incomplete results. 

Your search may turn up no stories or too many stories. You can adjust your search and hit the `Search` button again as needed. 

### Ways to super-fine-tune a PMP search

In the `Search term` box you can use these prefixes to further narrow the search:

* title:”search term”
* teaser:”search term”
* tags:”search term”
* content:”search term” (seems to return fewer results that just ”search term”)
* byline:”name”

## Optional: You can also search for content and get GUIDs from the PMP site

You can search for PMP content, and find the GUID for each item you find, on the PMP support site: 

https://support.pmp.io/

Click on Advanced Search to narrow your search to only stories with images, or simply use this url which does the same thing:

https://support.pmp.io/?advanced=1&profile=story&has=image

## Next steps

* [Create topic or program-based landing pages](/create-landing-pages.md) for PMP and other content
* [Create an hourly pull of PMP content to a Program or Category page](/hourly-pull-to-a-page.md)
