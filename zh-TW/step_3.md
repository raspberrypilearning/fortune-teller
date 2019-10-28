## Making a decision

Let's get your micro:bit to make a decision by randomly choosing a number (`0` for 'No' and `1` for 'Yes').

+ Add a new `on button A pressed` event to your code.

![截圖](images/fortune-on-a-pressed.png)

+ Let's create a new variable to store the answer. Click the 'Variables' and then click 'Make a variable'.

![截圖](images/fortune-variables.png)

+ Name the new variable called `answer`.

![截圖](images/fortune-answer.png)

+ Drag a `set` block from Variables into your `on button A pressed` block and select the `answer` variable.

![截圖](images/fortune-set.png)

As you can see, the `to` in the block means that you can set the answer to display.

+ Click 'Math' and drag a `pick random` block after the `to`:

![截圖](images/fortune-random.png)

+ Tell the random block to choose a number between 0 and 1. Here's how your code should look:

![截圖](images/fortune-random-1.png)

+ Next, you want to display the word `No` on the micro:bit only `if` the `answer` is 0.

To do this, drag an `if` block onto the bottom of your `on button A pressed` event:

![截圖](images/fortune-if.png)

+ Next drag an `=` block as the condition in the `if`:

![截圖](images/fortune-equals.png)

+ Drag your `answer` variable onto the left side of the `if` block.

![截圖](images/fortune-if-finished.png)

+ Any code inside the `if` block will only run if the `answer` is 0. As 0 is `No`, let's add a `show string` block.

![截圖](images/fortune-no.png)

+ Test your code. 
    + Sometimes the `answer` will be 0, and the micro:bit should say 'No'.
    + Sometimes the `answer` will be 1, and nothing will happen!