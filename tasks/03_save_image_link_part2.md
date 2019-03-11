---
title: Save Image Link
assignees:
  - HaominZhang
---

#### As a user I want to save a link to an image.

__Story__:

Now we have an awesome form that can save images and display images after they have been saved. However, now we would 
like to persist the saved images to our databse so that we do not lose our saved links when we reload the page. Since we are using React 
on the front end, we should use a Rails API on the backend to contact the database.

__Acceptance criteria__:
- [ ] The landing page shows the image link submission form.
- [ ] The link is entered through a form.
- [ ] After the form is saved, the link is persisted in the database.
- [ ] After the form is submitted, the image is displayed on the page.
- [ ] I cannot successfully save an image with an invalid URL on the front-end.
- [ ] I cannot successfully save an image with an invalid URL on the backend.
- [ ] An error message is associated with the appropriate input field on
  failure.
- [ ] After the form is submitted, the image is displayed on the page and the submission form input fields are cleared.

__Discussion Topic__:
- [ ] What is a valid image URL?

__Dependencies__:
- Deployment Environment

__References__:
* Screenshot of completed project for <a href="../images/completed-screenshot.png" style="border:0;" target="_blank">visual reference</a>

__Note__: Many image sharing sites will permit one to upload images, or
download images when provided a link. For this project we will only work with
the link, i.e., URL, to various images.