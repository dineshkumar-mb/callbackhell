Callback hell is also known as the “pyramid of doom,”. This situation of callback hell is created when there are multiple nested callback functions are there which make the code complex and hard to read. 
This occurs mainly in the asynchronous programming environment like while handling async requests or file operations where the function doesn’t execute in the fixed order.
The callbacks are chained within the callbacks, making the code structure look like a pyramid. Asynchronous operations often involve callbacks to handle responses or events.
When numerous asynchronous tasks are performed sequentially, each dependent on the completion of the previous one, the code becomes deeply nested and challenging to maintain.
This nesting of callback functions can lead to callback hell,
as developers find it difficult to read and debug errors and struggle with indentation.

in this above github code we can see how callbackhell works the code displays numbers from 10 to 1 at  like a coundown after 1 it displays a msg happy independance day .
here to demonstrate the callback hell settimeout is used
