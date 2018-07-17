# Bootstrap Interactive

- Once time's up have a few volunteers slack out their completed assignments to demonstrate for the class.

- After giving students a chance to show off some of their creations, open TODO: Link and demonstrate the result in the browser.

- Point out how we use each required component: 

  - A [Scrollspy](https://getbootstrap.com/docs/4.1/components/scrollspy/) which updates the active link in the navbar as we scroll.

    - This works by adding `data-spy="scroll"` and a `data-target` attribute set to the navbar's `id` to the container we'll be scrolling in — in our case this is the body.

  - A [Carousel](https://getbootstrap.com/docs/4.1/components/carousel/) which we're now using to contain the images on the page and their captions. For the most part we just copy and paste the sample code from the Bootstrap documentation and update the images with our image URLs.

  - A [Collapse/Accordion](https://getbootstrap.com/docs/4.1/components/collapse/) which is being used to show and hide our FAQ content on click. Point out how can open a card by default by giving it a class of `open`, and how each button's `data-toggle` property points to the `id` of the div it will be expanding.

  - A [Modal](https://getbootstrap.com/docs/4.1/components/modal/) which is being used to open a chat window when the chat button is clicked.

  - A [Dismissible Alert](https://getbootstrap.com/docs/4.0/components/alerts/#dismissing) which is being used to display an offer the user can dismiss if they wish. This one is simple to set up — just copy and paste the code from Bootstrap's documentation and change up the text inside.

- Take another few moments to answer any remaining questions. The main takeaway from this activity should be that students now have access to a dozen Bootstrap components they can use to give their prototypes interactivity with very little work.
