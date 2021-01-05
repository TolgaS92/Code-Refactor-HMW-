# 01 HTML CSS Git: Code Refactor

## Your Task

This week is an odd-numbered week, so your homework is an on-the-job ticket, which means you'll begin with starter code that you need to modify. This week's homework involves a very important aspect of web development: **accessibility**. 

One of the most common tasks for front-end and junior developers is to take existing code and refactor it (recall that to refactor code is to improve it without changing what it does) to meet a certain set of standards or implement a new technology. In this homework, a marketing agency has hired you to refactor an existing site to make it more accessible. 

Web accessibility is an increasingly important consideration for businesses. It ensures that people with disabilities can access a website using assistive technologies such as video captions, screen readers, and braille keyboards. Making a website accessible is also good for business for many reasons, one of them being that accessible sites are better positioned in search engines like Google. It also helps companies avoid litigation that can occur when people with disabilities cannot access their website.

Even though accessibility is a broad topic that can include complex requirements, your tech lead has given you a small list of specific criteria to satisfy the project. These criteria are documented below in the Acceptance Criteria.

**Important**: An important rule to follow when working with someone else's code is the **Scout Rule**, which recommends that you always leave the code a little cleaner than when you found it.

To impress clients, you should always go the extra mile and improve the codebase for long-term sustainability. For example, make sure that all links are functioning correctly. Also, rework the CSS to make it more efficient by consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

Are you ready to jump in? Here are this week's homework requirements:

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
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Code-Refactor-HMW-Solution

1) Descriptive Title added.

2) <div> tags replaced with <section> and <aside> tags to make it sementic html ( Screenshot: sectioninsteaddiv)
  
3) First link was missing (search-engine-optimization >> id="search-engine-optimization") and wasn't working, added it on. ( Screenshot: searchengineoptimizationidwasmissing)

4) Alt attributes added for the <images>, to improve accessibility standards. ( Screenshot: alt attributes)
  
5) To make The heading attributes fall in order, footer <h2> changed to <h4>
  
6) In HTML and CSS files, for the boxes, styles were the same exact each other, and put them in one meaningfull class, and made the style.css cleaner,shorter,better. ( Screenshot: sectioninsteaddiv)

7) The elements follow a logical structure independent of styling and positioning.

8) CSS file reorganized, with explanations.



##Screenshots
1) https://github.com/TolgaS92/Firsthomework-Code-Refactor/issues/1#issue-778478294
