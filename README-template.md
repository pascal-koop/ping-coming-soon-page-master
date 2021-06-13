# Frontend Mentor - Ping coming soon page solution

This is a solution to the [Ping coming soon page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/ping-single-column-coming-soon-page-5cadd051fec04111f7b848da). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**








### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS 
- Flexbox
- CSS Grid
- Mobile-first workflow
- thanks to (https://www.bram.us/2021/01/28/form-validation-you-want-notfocusinvalid-not-invalid/) to provide me the cool solution for the form validation



### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<button class="social-btn"><a href="#"><i class="fab fa-twitter fa-1x"></a></i></button>
use of font awesome and how I can implement them in my future projects.
 <script src="https://unpkg.com/ionicons@5.5.1/dist/ionicons.js"></script>
```
```css
form {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(auto-fit, minmax(40px, auto));
  }
  grid rows that fits automaticly to your content and privides more grids if you add more content 

  input[type="email"]:not(:focus):not(:placeholder-shown):invalid
  ~ .error-message {
  display: block;
  margin-top: 0.2rem;
}
to show the error message under the the input field, when invalid 

input[type="email"]:not(:focus):not(:placeholder-shown):invalid
    ~ .error-message {
    grid-row: 2/3;
    grid-column: 1/3;
  }
  used for the Desktop version, media queries and place the error message with grid underneath the input field. 
```


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.



### Continued development

- CSS grid is useful to make more complex layouts and i want to work more with it, to fully unleash the possibilitys.  



### Useful resources
(https://www.bram.us/2021/01/28/form-validation-you-want-notfocusinvalid-not-invalid/)
-- This helped me for the Validation part is worth to take a look to his blog. I really liked this pattern and will use it going forward.

look for Kyle Cook on Youtube and his CSS course, he helped me to understand flexbox and grid more 


## Author


- Frontend Mentor - [@Pascale-Cheddar](https://www.frontendmentor.io/profile/Pascale-Cheddar)




