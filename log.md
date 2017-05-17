# 100 Days Of Code - Log

<!--### Day 1: June 27, Monday

**Today's Progress**: I've gone through many exercises on FreeCodeCamp.

**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after a lot of attempts and hours spent.

**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence)-->

### Day 1: February 10, 2017 - Friday

**Today's Progress**: Working on Coding Javascript for 30 days

**Thoughts** : I learned while playing with checkboxes and there checked states. Also learnt that the *change* event doesn't look 
the keys like *ctrl, shift or alt*, when they are pressed. In order to solve we need to use **keyCode**. Whereas the *click* event 
can also gives us information which key is pressed. 

In order to achive something as basic as highlight the adjacent label of checkbox, for instance strikethrought it when a todo list 
checked we can go the simple way as `input:checked + label {text-decoration: line-throught}` in **CSS** or we go the long way using
**Javascript** as

```
inputs.forEach(function(input){
  input.addEventListener('change', function(e){
    var label = e.target.nextSibling;
    debugger;
    if(e.target.checked){
      label.classList.toggle('hl');
    } else {
      label.classList.toggle('hl');
    } 
  })
}, true)
```

**Link(s) to work** [Hold shift to select all checkbox](http://https://github.com/technbuzz/codejs30/commit/528e6e79a2ffdedc8e9969233f7fa93580f9b04d)

### Day 2: February 11, 2017 - Saturday

**Today's Progress**: Refactored old code for sass 

**Thoughts** Went throught this [article](http://https://medium.com/front-end-developers/the-solution-to-media-queries-in-sass-5493ebe16844#.y0o6afmfh) and learned how to
cope with the duplicate media queries when writing inline sass
**Link(s) to work** Worked locally

### Day 3: February 12, 2017 - Sunday

**Today's Progress**: Customizing Html Video Player 

**Thoughts** Playing through the html video api. Learnt that you can't check if video is playing but you go the reverse by checking
if it is paused. It also accepts an events when it's **paused** or when it's **running**

**Link(s) to work** [Customize Html5 Video](http://https://github.com/technbuzz/codejs30/commit/897dfbb2747f06311b3c35c29c79c3bff798b418)

### Day 4: February 13, 2017 - Monday

**Today's Progress**: Portfolio 

**Thoughts** Working on the portfolio. Not directly related to code because most of the time spend in wireframing. One thing I did learned we should not spend much time and energy for low fidelity wireframes. I went through moqups, mocking bird and many other tools but finally sticked with wireframe.cc

**Link(s) to work** Worked Locally

### Day 5: February 14, 2017 - Tuesday

**Today's Progress**: Portfolio 

**Thoughts** Contiinued Working on the portfolio. Started working on setting up the workflow. Switched from gulp-sass to gulp-ruby-sass which does requires the ruby,gem. Because it is faster.

**Link(s) to work** Worked Locally

### Day 6: February 15, 2017 - Wednesday

**Today's Progress**: Blogging 

**Thoughts** Wrote weekly coding report discussing Debouncing/throttling Javascript for performance, highlighting adjacent label on checking checkbox, Vscode extension and many more

**Link(s) to work** [Coding Activity for Week 07 2017](http://www.technbuzz.com/2017/02/15/coding-activities-for-week-07-2017/)

### Day 7: February 17, 2017 - Friday

**Today's Progress**: A11y 

**Thoughts** Worked on Accessibility, added focus state to the button and links also working  making the off screen nav unfocussable when collapsed

**Link(s) to work** Worked Locally

### Day 8: February 18, 2017 - Saturday

**Today's Progress**: A11y 

**Thoughts** Continued Working on Accessibility off screen nav unfocussable when collapsed

**Link(s) to work** Worked Locally

### Day 9: March 9, 2017 - Thursday

**Today's Progress**: Portfolio 

**Thoughts** Continued Working on my portfolio. The Wireframes and high fidelity mockup is converted to HTML and CSS. There is still a lot of work remains in the Responsive Design. I did used susy sass.

**Note** I am resuming my *#100daysofCode* challenge after the gap of 19 days. So I've to make up for that by completing *#119daysofCode*

**Link(s) to work** [Portfolio](http://technbuzz.com/portfolio)

---

### Day 10: March 10, 2017 - Friday

**Today's Progress**: Employee List Mean App 

**Thoughts** Just wanted to brush up my skills with Mean stack up. I practiced on basic crud app. Mongodb is very new to me now. get and post on the node side are doing most of the job. Node can't parse the request for this we need the body-parser module.

**Link(s) to work** Worked Locally, here is hosted image [Employee MEAN app](https://www.screencast.com/t/9qWmj7H0sI)

---

### Day 11: March 12, 2017 - Sunday

**Today's Progress**: Employee List Mean App 

**Thoughts** Continued working on the mean app. Added the country crud module.

**Link(s) to work** Worked Locally

---

### Day 13: March 16, 2017 - Thursday

**Today's Progress**: Learning Nodejs

**Thoughts** Digging into Nodejs. I discovered NodesJS is the sum of libuv + V8 + C++. In other words Nodes is the C++ program embedded with V8 that is added with wealth of features to make it suitable to be used as a server technologies

**Link(s) to work** Worked Locally

---

### Day 14: March 17, 2017 - Friday

**Today's Progress**: Learning NodeJs 

**Thoughts** Progressed with NodeJs and learned what are modules, commonjs moduels, Frist class functions. Modules is reusable code whose existance doesn't accidently impact other code. Commonjs modules is agreed upon standards that how modules should be used. First class functions are treated as such any other types. They can be passed around in the function, can be assigned to the variable. Put them in arrays. 

**Link(s) to work** Worked Locally

---

### Day 15: March 18, 2017 - Saturday

**Today's Progress**: Working on Html Tables 

**Thoughts** Today I learnt why the tr don't accept the padding. That how they are designed. It has some problem in the layout as they are made for the tabular data. I also found a somewhat controlled way of dealing how table deals the content inside its cell by using table fixed layout. 

**Link(s) to work** Worked Locally

---

### Day 16: March 19, 2017 - Sunday

**Today's Progress**: Working on JavaScript Objects, Variables 

**Thoughts** Inhritence is one object got access to the properties and methods of other object (set of pair values). However the way Javascript implement it is different which is called prototypical inheritense. Construction function is a normal function that is used to create an object. Primitive value is a type of data that represent a single value, a number or string or in other words everything that is not an object. Whenever we pass a primitive value to a function, a copy of a variable is created. Both of these variables point to different location in the memory. When we pass the object to a function they are passed by a reference both inside and outside the function, object refer to the same location in the memory. Scope is where in code you have access to particular function or variable.

**Link(s) to work** Worked Locally

---

### Day 17: March 20, 2017 - Monday

**Today's Progress**: Working on Browser Bookmarklet 

**Thoughts** I worked on using browser bookmarklet which is helpful in SEO when you quickly need to find what meta tags and meta content is used

**Link(s) to work** Worked Locally

---

### Day 18: March 21, 2017 - Tuesday

**Today's Progress**: Working on Bootstrap Collapse

**Thoughts** Today I needed to add and modify the existing collapse module that comes with bootstrap. I found out that it was quite hard. Because although it provide some events like when the element is fully shown or hidden but the evt we get doesn't has reference to the active element header so that I can easily add the plus and minus button. It does give access for the content is shown when an element is expanded. I had to manually traverse from the content to the so called .panel-heading in bootstrap and than to desired element.

This is the code that I wrote 
```
$('#addon-accordion').on('shown.bs.collapse', function(evt){
  var currTarget = evt.target;
  var prevHeading = $(currTarget).prev('.panel-heading');
  $(prevHeading).find('.collapse-icon').attr('src','images/sl-icon.png');
})

$('#addon-accordion').on('hidden.bs.collapse', function(evt){
  var currTarget = evt.target;
  var prevHeading = $(currTarget).prev('.panel-heading');
  $(prevHeading).find('.collapse-icon').attr('src','images/plus-black.png');
})
```

**Link(s) to work** Worked Locally

---

### Day 19: March 23, 2017 - Thursday

**Today's Progress :** Working on Media Queries with Sass

**Thoughts :** Sass is great. It adds great functionality to the CSS. But to write the media all at once doesn't come by default with Sass. One way is to write seperate mixin at the end of each include and then call then in one file. That file will contain media queries from entire project

**Link(s) to work :** [Snapshot of the Process](https://www.screencast.com/t/NREP2hEw5)


---

### Day 20: March 27, 2017 - Monday

**Today's Progress :** Working on Customizing Checkboxes

**Thoughts :** Using the bootstrap markup of checkboxes, I made the input transparent. Didn't hide it completely as the input wont receive focus and wont change the state if space is pressed. Add the a div element adjacent to the input and styled it according to the input tag.

**Link(s) to work :** Worked Locally

---

### Day 21: April 1, 2017 - Tuesday

**Today's Progress :** Getting Started with Ionic

**Thoughts :** Went throught the getting started stages. How to use it's cli and different templates

**Link(s) to work :** Worked Locally

---

### Day 22: May 3, 2017 - Wednesday

**Today's Progress :** Getting Started with Angular

**Thoughts :** Went throught the getting started stages. How to use it's cli and different templates

**Link(s) to work :** Worked Locally
---

### Day 23: May 4, 2017 - Thursday

**Today's Progress :** Angular Components 

**Thoughts :** Learn't how to create the component and what are decorators and how they make the communication possible between template and component. Also how to send the data to the child components using @Input property decorators

**Link(s) to work :** Worked Locally

### Day 24-25: May 6, 2017 - Saturday

**Today's Progress :** JavaScript 6 Array Methods 

**Thoughts :** Fiddled with array methods like forEach filter, map and learnt what's the difference b/w them. Actually forEach loops over every element of the array and return the element. But map and filter iterates over every element and after the callback modification, the modified element is mapped back and returns us the array. In case of filter, if test is passed in the call back function that that value will make its place in to the array that will be returned

**Link(s) to work :** Worked Locally

### Day 26-27: May 8, 2017 - Monday

**Today's Progress :** CSS Custom Properties - Angular Router

**Thoughts :** As the support of Css Variables landed in Edge 15, It's time to switch to variables for colors, font-sizes and easily add support of themes in your projects, as they can be changed in run time not limited to build time like that of CSS processors like SASS or LESS.
Getting my head around the Angular Routing. Didn't had much success need to practice

**Link(s) to work :** Worked Locally

### Day 28-29: May 15, 2017 - Monday

**Today's Progress :** Node 

**Thoughts :** Spinning basic server, serving static assets, handling basic get and post requests. Usage of bodyparser

**Link(s) to work :** Worked Locally

### Day 28-29: May 17, 2017 - Wednesday

**Today's Progress :** Node 

**Thoughts :** express render, #pug template inheritance with block and extends along 

**Link(s) to work :** Worked Locally