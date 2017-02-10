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
