 Website Performance Optimization portfolio project
 ==================================================

### Index.html optimization scheme is as follows:
* Local image compression processing
* Deleting a reference to a Google font
* Using inline styles to index.html, compression CSS style code
* Google fonts will be downloaded to the local, in the index.html reference "Sans Open" font
* JS "http://www.google-analytics.com/analytics.js" to download the external file to the local, local address
* Move all JS code and references to the end of the index.html, which is designed to load the HTML and then call JS
* Compressed CSS, JS file


## Pizza.html optimization scheme is as follows:
* Open the views folder, find the pizza.html, right to open the way for the Google browser, right click, click TimeLine to see the operation effect.
* Add a corresponding number of pizza according to the size of the browser
* ID for the "movingPizzas1" and class for "mover" label to obtain the corresponding for to remove the outer layer, to avoid duplication of access to the same content and affect the performance
* Use "requestAnimationFrame" to update the animation, to maintain the best rendering efficiency
* Modify the **main.js** file in the "changePizzaSizes" method, the acquisition of div and related calculation out of the loop body, improve performance
* Compressed CSS, JS file
