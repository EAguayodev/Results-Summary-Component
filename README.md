# Frontend Mentor - Results summary component
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

### Screenshot

![Screenshot](./assets/images/Frontend-Mentor-Results-summary-component-schreenshot.png)


### Links

- Solution URL: [Github](https://github.com/EAguayodev/Results-Summary-Component)
- Live Site URL: [Vercel](https://results-summary-component-jade-iota.vercel.app/)

## My process
My process started out using and structuring the HTML to fit the text in accordance with their cards to show the user's score results. After structuring the content of the page, I generated the CSS classes to begin my styling both for desktop and mobile with a desktop approach in mind first. To get the design in place, I used Flexbox to achieve the layout format and get it as close to the design as possible. 

### Built with
- HTML5 
- CSS 
- Flexbox
- Desktop-first workflow to mobile

### What I learned

I learned at the end when debugging my code, a great way to debug and remove the horizontal scroll on mobile is using the outline inside the universal selector bracket inside your CSS, and putting a border at 1px solid [color] to find which area is overlapping.

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.


```css
* {
  outline: 1px solid red;
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- [w3schools](https://www.w3schools.com/css/default.asp) - This resource helped me get a refresher on the basics of using CSS styles regarding applying the styles to my container and main tags. This resource also helped when needing to refresh myself on using linear-gradient colors for the details on the left side of the card.
- [github documentation](https://docs.github.com/en/authentication/troubleshooting-ssh/error-permission-denied-publickey) - Github docs helped me understand and learn to fix SSH permissions denied when pushing my first commit to my new initialized repo for the challenge.
-[3 easy steps to fix horizontal scroll on mobile](https://foxscribbler.com/prevent-horizontal-scroll-on-mobile/) - Great resource for debugging horizontal scroll effects to remove on mobile.


## Author

- Website - [Eric Aguayo](https://www.ericaguayo.com)
- Frontend Mentor - [@EricAguayo90](https://www.frontendmentor.io/profile/EricAguayo90/solutions)
- LinkedIn - [@ericaguayo](https://www.linkedin.com/in/ericaguayo)

## Acknowledgments

Acknowledgments go to an instructor of mine in another group on Discord which got me to use the challenge for practicing CSS with a focus on writing code that prevented horizontal scroll effects on the mobile design.
