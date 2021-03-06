#Creating a Landing Page to Display Stories Pulled from the PMP

There are at least three ways to create a landing page for a project or subject area, where you can pull in stories for a given project or subject. You can pull in PMP stories, post your own stories, and add related stories on a landing page or website section. 

The first two methods are very similar:

Create either a Category or Tag for the subject or focus of the page. Examples could include:

* Election
* Environment
* Health Care
* Anything else you want
 
(Here are NPR DS's instructions on how to [create a Category](http://digitalservices.npr.org/post/how-create-category), and [how to create a Tag](http://digitalservices.npr.org/post/how-create-tag) in Core Publisher.)

To create a new Category or Tag, click on `Configure Core Publisher` in the top menu, then click either `Manage Categories` or `Manage tags`:

![Configuring Categories and Tags in Core Publisher]
(/img/configure-terms-core-publisher.png)

When you create a Category or Tag, Core Publisher will create a page for it with a url of `http://yoursite.org/term/category_or_tag_name` 

You can also edit the Category or Tag to add a Description which will be displayed on the page to provide further context.

##Post PMP stories on a Category or Tag page

Adding PMP content to a Category or Tag page is easy: Go to Find Content and either [Pull a PMP story by its PMP GUID](/pulling-pmp-content-into-cp-by-story.md#if-you-know-the-guid-of-a-specific-pmp-story-you-want), or [Search the PMP](/pulling-pmp-content-into-cp-by-story.md#if-you-dont-know-the-guid-of-a-specific-pmp-story-search-the-pmp) to find one or more stories you want to pull. For each story you pull, edit the story and add the Category or Tag you want. The story will instantly display on the Category or Tag page.

##Post PMP stories to a Topic page

The third method of creating a project or subject landing page is to create a Topic page. A Topic page for (e.g.) the topic of Health Care will have a url like this: `http://yoursite.org/topic/health-care`

The only difference with a Topic page is that you can associate it with up to five different Tags. So any story tagged with any of the associated tags will display on the Topic page. This might be handy when you want a landing page to display lots of existing stories that are tagged with different tags. For example, if you want a landing page for Health Care, and you know there are existing stories with tags like health, health care, hospitals, medicine, and wellness, you can simply add these as Associated Tags in the Topic page. Stories tagged with any of these will instantly display on on the Health Care topic page.

Adding PMP content to a Topic page is the same as for a Category or Tag page: Go to Find Content and either Pull a PMP Doc by its PMP GUID, or Search the PMP docs to find one or more stories you want to pull. Either way, after you pull a story you need to hit its Edit tab and add a Tag associated with the Topic Page.

##See also:
* [Pulling PMP Content into Core Publisher by Individual Story](/pulling-pmp-content-into-cp-by-story.md)
* [Create an Hourly Pull of PMP Pontent to a Program or Category Page](/hourly-pull-to-a-page.md)
