What I learned from this ?
 - ``` data-* ``` attributes is used to store custom data private to the page or application

 - ``` transitionend ``` is a event that fire when CSS transition is completed

 - Using ``` document.querySelector(`.key[data-key="${e.keyCode}"]`) ``` to select
```sh  
    <div data-key="75" class="key">
    <kbd>K</kbd>
    <span class="sound">tom</span>
    </div>
 ```
