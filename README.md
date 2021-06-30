

### frontend-mentor provided the design








### Built with

- Semantic HTML5 markup
- CSS 
- Flexbox
- CSS Grid
- Mobile-first workflow
- thanks to (https://www.bram.us/2021/01/28/form-validation-you-want-notfocusinvalid-not-invalid/) to provide me the cool solution for the form validation



### What I learned


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










### Useful resources
(https://www.bram.us/2021/01/28/form-validation-you-want-notfocusinvalid-not-invalid/)
-- This helped me for the Validation part is worth to take a look to his blog. I really liked this pattern and will use it going forward.

look for Kyle Cook on Youtube and his CSS course, he helped me to understand flexbox and grid more 


## Author


- Frontend Mentor - [@Pascale-Cheddar](https://www.frontendmentor.io/profile/Pascale-Cheddar)




