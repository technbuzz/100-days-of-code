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