# Day One JavaScript30 Drum Kit
#javascript #front-end
* Keycode
* Data attributes
* We need to listen to the *window* event so we need to add an *eventListener* to *window*
* *document.querySelector()* to select the *element* in a page. You can also add [atrr] following the tag.
## Audio Element
So for an audio element, if you use *play()* method to it, it will only play once. The reason behind this is after you played the audio for the first time, the pointer for the audio will point to the end of the file. So if you want to replay the audio. Just set *currentTime* attribute to 0. Then it will rewind to the start. 
- - - -
* .classList.add()
* .classList.remove()
* .classList.toggle()
## CSS Transitions
* CSS transitions allows you to change property values smoothly (from one value to another), over a given duration.
* To create a transition effect, you must specify two things:
	* the CSS property you want to add an effect to
	* the duration of the effect
* To listen to a transition ends by *.addEventListener(’transitionend’,callback)*
- - - -
## What made me stuck?
1. addEventlistener() callback function.
2. Where to write the whole component in? - In the *keydown* event’s callback function.
3. Curry function’s *this*