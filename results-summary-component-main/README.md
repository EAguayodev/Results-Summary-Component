# Frontend Mentor - Results summary component




## The challenge

Your challenge is to build out this results summary component and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

We provide the data for the results in a local `data.json` file. So you can use that to add the results and total score dynamically if you choose.

Your users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

## Create a custom `README.md`

We strongly recommend overwriting this `README.md` with a custom one. We've provided a template inside the [`README-template.md`](./README-template.md) file in this starter code.

The template provides a guide for what to add. A custom `README` will help you explain your project and reflect on your learnings. Please feel free to edit our template as much as you like.

Once you've added your information to the template, delete this file and rename the `README-template.md` file to `README.md`. That will make it show up as your repository's README file.

## Submitting your solution

Submit your solution on the platform for the rest of the community to see. Follow our ["Complete guide to submitting solutions"](https://medium.com/frontend-mentor/a-complete-guide-to-submitting-solutions-on-frontend-mentor-ac6384162248) for tips on how to do this.

Remember, if you're looking for feedback on your solution, be sure to ask questions when submitting it. The more specific and detailed you are with your questions, the higher the chance you'll get valuable feedback from the community.

## Sharing your solution

There are multiple places you can share your solution:

1. Share your solution page in the **#finished-projects** channel of the [Slack community](https://www.frontendmentor.io/slack). 
2. Tweet [@frontendmentor](https://twitter.com/frontendmentor) and mention **@frontendmentor**, including the repo and live URLs in the tweet. We'd love to take a look at what you've built and help share it around.
3. Share your solution on other social channels like LinkedIn.
4. Blog about your experience building your project. Writing about your workflow, technical choices, and talking through your code is a brilliant way to reinforce what you've learned. Great platforms to write on are [dev.to](https://dev.to/), [Hashnode](https://hashnode.com/), and [CodeNewbie](https://community.codenewbie.org/).

We provide templates to help you share your solution once you've submitted it on the platform. Please do edit them and include specific questions when you're looking for feedback. 

The more specific you are with your questions the more likely it is that another member of the community will give you feedback.


# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#results-summary-component)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)




### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.


### Links

- Solution URL: [Github](https://github.com/EAguayodev/Results-Summary-Component)
- Live Site URL: [Vercel](https://results-summary-component-jade-iota.vercel.app/)

## My process
My process started out using and structuring the html to fit the text in accordance with their cards to show the users score results. After structuring the content of the page, I generated the css classes to begin my styling both for destop and mobile with a desktop approach in mind first. To get design in place, I used flexbox to achieve the layout formatted and get it as close to the design as possible. 

### Built with
- Semantic HTML5 markup
- CSS 
- Flexbox
- JSON
- Desktop-first workflow to mobile

### What I learned

I learned at the end when debugging my code, a great way to debug and remove the horizontal scroll on mobile is using the outline inside the universal selector bracket inside your css, and putting a border at 1px solid [color] to find which area is overlapping.

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.


```css
* {
  outline: 1px solid red;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- [w3schools](https://www.w3schools.com/css/default.asp) - This resource helped me get a refresher on the basics of using css styles regarding to applying the styles to my container and main tags. This resource also helped when needing to refresh myself on using linear-gradient colors for the details on the left side of the card.
- [github documentation](https://docs.github.com/en/authentication/troubleshooting-ssh/error-permission-denied-publickey) - Github docs helped me understand and learn to fix SSH permissions denied when pushing my first commit to my new intialized repo for the challenge.
-[3 easy steps to fix horizontal scroll on mobile](https://foxscribbler.com/prevent-horizontal-scroll-on-mobile/) - Great resource for debugging horizontal scroll effects to remove on mobile.


## Author

- Website - [Eric Aguayo](https://www.ericaguayo.com)
- Frontend Mentor - [@](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@](https://www.twitter.com/yourusername)
- LinkedIn - [@ericaguayo](https://www.linkedin.com/in/ericaguayo)

## Acknowledgments

Acknowledgements go to an instructor of mine in another group on Discord which got me to use the challenge for practicing css with the focus on writing code which prevented horizontal scroll effects on the mobile design.dev.to