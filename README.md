# 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements <!--Acceptance Criteria 1-->
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning <!--Acceptance Criteria 2-->
WHEN I view the image elements
THEN I find accessible alt attributes <!--Acceptance Criteria 3-->
WHEN I view the heading attributes
THEN they fall in sequential order <!--Acceptance Criteria 4-->
WHEN I view the title element
THEN I find a concise, descriptive title <!--Acceptance Criteria 5-->
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

## Sam's Notes for Understanding

Acceptance Criteria 1:

WHEN I view the source code
THEN I find semantic HTML elements

Why is this important?:

First, it is much easier to read. This is probably the first thing you will notice when looking at the first block of code using semantic elements. This is a small example, but as a programmer you can be reading through hundreds or thousands of lines of code. The easier it is to read and understand that code, the easier it makes your job.
It has greater accessibility. You are not the only one that finds semantic elements easier to understand. Search engines and assistive technologies (like screen readers for users with a sight impairment) are also able to better understand the context and content of your website, meaning a better experience for your users.
Overall, semantic elements also lead to more consistent code. When creating a header using non-semantic elements, different programmers might write this as <div class="header">, <div id="header">, <div class="head">, or simply <div>. There are so many ways that you can create a header element, and they all depend on the personal preference of the programmer. By creating a standard semantic element, it makes it easier for everyone.
Source: https://guide.freecodecamp.org/html/html5-semantic-elements/

Acceptance Criteria 2:

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning

Why is this important?:

https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure

Acceptance Criteria 3:

WHEN I view the image elements
THEN I find accessible alt attributes


Why is this important?:

Images and graphics make content more pleasant and easier to understand for many people, in particular, those with cognitive and/or learning disabilities. They serve as cues for people with visual impairments, including people with low vision, to orient themselves in the content.

Adding an image or a graphic to your content without using proper or empty alternative attributes (alt tags), can be extremely frustrating for people with visual impairments navigating your site through assistive technologies. Images alternatives add valuable information for low vision or blind screen reader users.

This article is intended to outline best practice examples of image alt tags to help you implement these tags properly on your website.

https://support.siteimprove.com/hc/en-gb/articles/115000013031-Accessibility-Image-Alt-text-best-practices

Acceptance Criteria 4:

WHEN I view the heading attributes
THEN they fall in sequential order


Why is this important?:

The underlying purpose of headers is to convey the structure of the page. For sighted users, the same purpose is achieved using different sizes of text. Text size, however, is not helpful for users of screen readers, because a screen reader identifies a header only if it is properly marked-up. When heading elements are applied correctly, the page becomes much easier to navigate for screen reader users and sighted users alike.

In the same way that sighted users can glance at a page and get a sense of its contents, users of screen readers can do the same by navigating through headings. Well written and properly ordered headings can save users, especially those who use screen readers, a lot of time and frustration.

The purpose of headings is to describe the structure of the webpage, not just highlight important text. They should be brief, clear, unique, and marked with h1 through h6 elements applied in hierarchical order. All of these qualities make headings valuable tools for screen reader users. Similar to the way sighted users can glance at a page and get a sense of its contents, screen reader users can navigate through headings. Well written and properly ordered headings can save screen reader time and frustration.

In addition to making the page more accessible, headings have other benefits since search engines use headings when filtering, ordering, and displaying results. Improving the accessibility of your site can also have the effect of making your page more findable.

https://dequeuniversity.com/rules/axe/3.0/heading-order

Acceptance Criteria 5:

WHEN I view the title element
THEN I find a concise, descriptive title

Why is this important?:

The HTML Title element (<title>) defines the document's title that is shown in a browser's title bar or a page's tab. It only contains text; tags within the element are ignored.

The contents of a page title can have significant implications for search engine optimization (SEO). In general, a longer, descriptive title performs better than short or generic titles. The content of the title is one of the components used by search engine algorithms to decide the order in which to list pages in search results. Also, the title is the initial "hook" by which you grab the attention of readers glancing at the search results page.

A few guidelines and tips for composing good titles:

Avoid one- or two-word titles. Use a descriptive phrase, or a term-definition pairing for glossary or reference-style pages.
Search engines typically display about the first 55–60 characters of a page title. Text beyond that may be lost, so try not to have titles longer than that. If you must use a longer title, make sure the important parts come earlier and that nothing critical is in the part of the title that is likely to be dropped.
Don't use "keyword blobs." If your title is just a list of words, algorithms often reduce your page's position in the search results.
Try to make sure your titles are as unique as possible within your own site. Duplicate—or near-duplicate—titles can contribute to inaccurate search results.

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title


Did you ever feel like reading a book without a title? Ranking on Google now is much more than optimizing or concentrating on a single element. Title tag still remains one of the most important element that could contribute towards optimizing your website for better rankings on the SERPs. Title tags are also known as Meta title.

https://www.rankwatch.com/learning/content/how-and-why-does-title-tag-play-major-role-attracting-traffic-your-website

