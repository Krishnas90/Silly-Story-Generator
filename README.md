# Silly-Story-Generator
A fun and interactive JavaScript-based project where users can generate silly and creative stories. Simply fill in the blanks with random words, and watch as a unique and amusing story unfolds. Perfect for a quick laugh or sparking creativity!

1. COMPLETE VARIABLE AND FUNCTION DEFINITIONS
const customName = document.getElementById('customname');
const randomize = document.querySelector('.randomize');
const story = document.querySelector('.story');

function randomValueFromArray(array){
  const random = Math.floor(Math.random()*array.length);
  return array[random];
}
2. RAW TEXT STRINGS
It was 94 fahrenheit outside, so :insertx: went for a walk. When they got to :inserty:, they stared in horror for a few moments, then :insertz:. Bob saw the whole thing, but was not surprised — :insertx: weighs 300 pounds, and it was a hot day.

for insertx:-
Willy the Goblin
Big Daddy
Father Christmas

for inserty:-
the soup kitchen
Disneyland
the White House

for insertz:-
spontaneously combusted
melted into a puddle on the sidewalk
turned into a slug and crawled away

3. EVENT LISTENER AND PARTIAL FUNCTION DEFINITION

randomize.addEventListener('click', result);

function result() {

  if(customName.value !== '') {
    const name = customName.value;
    ne
  }

  if(document.getElementById("uk").checked) {
    const weight = Math.round(300);
    const temperature =  Math.round(94);

  }

  story.textContent = ;
  story.style.visibility = 'visible';
}
