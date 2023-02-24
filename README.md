# Assignment 03 - DRAFT

**Course Title**: Web Development

**Course Code**: IMD1005

**Semester**: Winter 2023

**Due Date**: 11:59 PM (midnight) 2023-03-XX

**Assessment**: This assignment is worth 25% of your final grade and marked out of 100.

## TLDR

1. Build a feature rich Todo list.
2. Add the code for your web page to a GitHub assignment 03 repository and host the page online using the GitHub pages service.

## Description

Todo lists are like a "right of passage" in webdev tutorials. A simple Todo list can be written in a couple dozen lines of code. There is, however, a huge opportunity for innovation, enhancements and features. Your Assignment 03 involves building an awesome and innovative Todo list app. 

## Instructions

1. Your `todos` are going to be javascript objects that your users will be able to dynamically create.
2. The UI/UX is completely up to you, though it must be responsive and at a minimum enable users to view, add, remove, and delete `todos`. 
3. Using user centered design principles, consider what additional properties and features your users may need for an awesome Todo list. 
4. Your `todos` are going to have, at a minimum, a `title`, and `done` status. 
5. Users will also appreciate being able to add categorise or group `todos` together, so you will also need to track `categories` or `headings` or some sort of `grouping` information.
6. Consider also adding a `priority` and `descriptions` to your `todos`, though only if you feel they add value to your app. 
7. It would be super annoying to lose all of your `todos` everytime the page refreshed, so you are going to use `localStorage` ([mdn docs](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API/Using_the_Web_Storage_API)) to save the users' data.
8. You should also have an awesome empty state when a user first opens your app ([examples](https://www.toptal.com/designers/ux/empty-state-ux-design)).  
9. Though not required, consider "branding" your app with a cool product name, and logo. 

## Assignment acceptance criteria 

* Publish your code to GitHub using the GitHub classrooms generated repository
* Use the GitHub Pages service to host your pages
* Ensure you have a license file in your repository (recommend MIT license)
* Ensure you have the assignment readme.md file in your repository

## Grading rubric

The creation and posting of this web page is worth 25% of your final grade and marked out of 100.

|Criteria|Total&nbsp;Marks|How we define excellence|
|----|----|----|
|Visual design|**15%**|The design presented demonstrates an excellent use of colour (or lack thereof), typography, high quality graphics, and iconography. The design also comes across as cohesive, inviting, and illustrates a focus on user experience. An excellent design also includes a way of delighting users and adding moments of charm to their experience.|
|Content and layout|**15%**|The content implemented on the web page demonstrates a clear hierarchy and an effective layout is employed for the content that is being displayed in each section. The solution is responsive to the users' viewport and displays well in mobile, tablet, and desktop browsers.|
|HTML|**20%**|The HTML code submitted is well formed, structured, and complaint. Appropriate semantic elements are used throughout the document. For example, use `<header>` for the page header and `<section>` for each document section within `<main>`. Correct use of headings `<h1-h6>` and heading structure. The web page has the appropriate meta tags in the `<head>` to set the charset, viewport and IE11 legacy mode values.|
|CSS|**20%**|The CSS code submitted is well formed, structured, and compliant. A CSS reset file is used to 'reset' all of the default browser styles. The web page renders correctly in multiple browsers, including but not limited to Firefox and / or Chrome. All CSS should be referenced from an external file. The web page should not use a `<style>` tag or a embedded `style` attributes to apply CSS to the page.|
|JavaScript|**20%**|The JS code submitted is well formed, structured, and compliant. No run time errors should occur. If an error occurs it should be caught and dealt with appropriately. Your code should be written to the latest ECMAScript 2022 standard. |
|GitHub&nbsp;submission|**10%**|All of the project files (HTML, CSS, JS, assets) are added to your assignment repository on GitHub. The repository has both a populated READMe.md file and a MIT license file.|

## Late submissions

* If you intend to use one of your assignment extensions please email [mispeln@algonquincollege.com](mailto:mispeln@algonquincollege.com) before the specified due date
* If you are ill or any other issues arise that are beyond your control, please email [mispeln@algonquincollege.com](mailto:mispeln@algonquincollege.com) before the specified due date to discuss alternate arrangements
* If you fail to request your late pass, or fail to inform me of any extenuating circumstances that cause a delay in your submission by the due date, you will receive a mark of **Zero (0)** for the assignment 
* If you use your late pass, and fail to submit your assignment by one week after the specified due date, you will receive a mark of **Zero (0)** for the assignment

## Screenshots for inspiration 

The following are some samples of excellent Todo List applications out there. You do not, and should not build these specfic designs. This is only being shared to illustrate what the industry is putting out there right now, and to provide some inspiration to for your own designs and features.

### Simple Todo List App

<img width="1417" alt="Screenshot 2023-02-24 at 12 17 12 PM" src="https://user-images.githubusercontent.com/9325038/221244829-d547cf0d-ce5a-43d4-a2fe-e9d442bbddae.png">

[Source](https://www.uplabs.com/posts/simple-todo-list-app)

### Any.do App

<img width="1417" alt="Screenshot 2023-02-24 at 12 25 39 PM" src="https://user-images.githubusercontent.com/9325038/221246731-8ae0addc-54e0-4185-a344-222cd44a6072.png">

[Source](https://www.any.do/to-do-list/)

### Microsoft To do

<img width="981" alt="Screenshot 2023-02-24 at 12 33 55 PM" src="https://user-images.githubusercontent.com/9325038/221248466-5558bd3e-8111-499b-a57a-5647eeb4abd0.png">

[Source](https://todo.microsoft.com)

### Things by Cultured Code

<img width="971" alt="Screenshot 2023-02-24 at 12 36 54 PM" src="https://user-images.githubusercontent.com/9325038/221249209-08d757a7-0b11-4840-adbe-7b6e49c379e9.png">

[Source](https://culturedcode.com/things/)


## Frequently Asked Questions (FAQ)

<dl>
  
  <dt>Do I have to put comments in my code?</dt>
  <dd>No! You do not need to comment your code. That being said, it is an industry best practice to add comments to your code, so I would recommend that you add comments to your code where it makes sense, but this is not required.</dd>
  
  <dt>Does the web page / web app have to work in both mobile and desktop?</dt>
  <dd>Yes! You must build your app to be completely responsive.</dd>
 
  <dt>Can I use lorem ipsum text in my web page / web app?</dt>
  <dd>You may use lorem ipsum if you need to but ideally by now you should be using relevant content in your projects. Though, if you don't have relevant content you are absolutely permitted to use <a href="https://www.lipsum.com">lorem ipsum</a>, <a href="https://baconipsum.com">bacon ipsum</a>, or <a href="https://veganipsum.me">vegan ipsum</a> in your designs. Keep in mind that this should not be used in cases where the meaning of the text is important, for example the call to action buttons in the hero.</dd>

  <dt>Do I need to include sketches, concepts, or initial low fidelity mockups in my submission?</dt>
  <dd>No. If you would like to share your design or creative process I'm happy to look at them, but it is not required.</dd>
 
  <dt>Can I use trademarked or copywritten material on my page?</dt>
  <dd>Yes! As this is for educational purposes, all of the source is open, and no one is trying to sell their design or code you can absolutely use trademarked or copywritten material.</dd>
 
</dl>

## Helpful links

### HTML Resources

* [Intro to HTML - Prof3ssorSt3v3](https://www.youtube.com/watch?v=KUmuiqV1xME&list=PLyuRouwmQCjncCz8JChyPNRBvm2ONGYa2)
* [HTML Tutorial - MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML)

### CSS Resources 

* [Intro to CSS - Prof3ssorSt3v3](https://www.youtube.com/watch?v=KFKScNHa-8M&list=PLyuRouwmQCjl4wTSNbb8RTKZuyMhoIxBe&index=2)
* [CSS Tutorials - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Tutorials)

### JavaScript Resources

TODO

### Images and Icons 

* [Pexels](https://www.pexels.com)
* [Unsplash](https://unsplash.com)
* [The noun project](https://thenounproject.com)

### Inspiration 

* [Article on Guerrilla User Testing](https://xd.adobe.com/ideas/process/user-testing/hallway-usability-test-guerrilla-testing/)
* [Land Book](https://land-book.com)
* [Best Website Gallery](https://bestwebsite.gallery/sites)
* [One page love](https://onepagelove.com)
* [Awwwards](https://www.awwwards.com/websites/)
* [ui8.net](https://www.ui8.net)



<!-- 

!!!! ASSIGNMENT BONUS - STILL NEEDS TO BE WRITTEN !!!!

Congratulations - you found the secret assignment bonus. 

Well done! To get an extra 10 marks (ten) on your mark for Assignment 03 please follow the instructions below.

STEP 1: 

TODO

STEP 2: 

TODO

STEP 3:

TODO

NOTE: 

TODO

!!!! ASSIGNMENT BONUS - STILL NEEDS TO BE WRITTEN  !!!!

--> 
