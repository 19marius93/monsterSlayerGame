# Monster Slayer Game
This is the Monster Slayer Project that I've made using: <strong>HTML</strong>, <strong>CSS</strong> and <strong>Vue.js</strong>
You can check it out following the link: https://19marius93.github.io/monsterSlayerGame/

<strong>Skills used:</strong>

<strong>HTML:</strong> connected to <em>.css file</em> through a <em>link</em> tag and to <em>.js file</em> through a <em>script</em> tag, for this I've used <strong>Semantic Elements</strong> to make it more comprehensible, I've provided the elements with <strong>'classes'</strong> and <strong>'id's'</strong> so I can manipulate and style them in CSS, and I've used <strong>Custom Events</strong> to link them to my <em>.js file</em> and give them functionality.

<strong>CSS:</strong> the <em>font style</em> is imported from Google Fonts through a <em>link</em> tag in HTML, I've used <strong>Flex-Box</strong> and other <strong>CSS Properties</strong> to get the wanted layout, and with the help of <strong>CSS Specificity (id's, classes, tags)</strong>, I got the desired styling of the page. I've also used some <strong>pseudo-classes</strong> for my <em>button</em> elements, to give them a custom state.

<strong>Vue.js:</strong> with the help of the <em>JavaScript</em> framework, <strong>Vue.js</strong>, I've managed to store my data using the <strong>data()</strong> property which returns a <em>key:value pair object</em>, I've used <strong>methods:</strong> property to define the <em>functions</em> needed to perform the necessary actions & handle the <strong>custom events</strong> in my <em>HTML</em> file.The <em>damage values</em> are calculated by using a <strong>JS function</strong> which returns a <em>random value</em> from a <em>pre-set (min, max)</em>. To calculate and display <em>values</em> everytime some <em>data</em> changes, I've used the <strong>computed:</strong> property, and I've placed some <em>watchers</em> using <strong>watch:</strong> property to get the <em>"Game Over"</em> message, and the option to <em>"Start New Game"</em>, whenever a certain <em>value</em> is reached. For the <em>Battle Log</em>, which in the beginning is just an <em>empty array</em> in my <strong>data()</strong> property, I've used a <em>function</em> in the <strong>methods:</strong> property, with three given <em>parameters</em>, where I used the JS <strong>.unshift()</strong> method to add elements to the beginning of the array, and <strong>interpolate</strong> them in the <em>HTML</em> file.


How it works: 
- everytime you attack, the monster attacks back
- every three round you get a "special attack", which has a slightly higher damage value
- you have a "heal" button, if you feel like the monster is too strong, but everytime you use it, the monster still attacks back
- you have a "surrender" button, which will end the game (with a loss), if you feel like you can't beat the monster
- at the bottom, you have a log console, where all the current moves are stored
