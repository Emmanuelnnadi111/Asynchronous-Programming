![asynchronous-programming](https://user-images.githubusercontent.com/123368493/216847063-450c06f9-11e5-412e-8ae1-9dd3c04bb236.png)

ASYNCRONOUS PROGRAMMING

Asyncronous Programming allows multiple tasks to happen at the same time. it is the opposite of Synchronous programming.
Synchronous programming performs single task at a time and does not allow multiple task at a time.
  it doesn't wait for one program to finish before performing another, it is responsive to other events while a task runs.
  
  Example of syncronous programming using javascript
  ![SYNC](https://user-images.githubusercontent.com/123368493/216847958-4fe22a78-db5e-4914-8efd-92ae01c83044.PNG)
  
In the above example, the first line of code, One, will be logged first, followed by the second line, Two, and the third line, Three. It’s easy to see that the code works sequentially; each line of code waits for the former to be completed before it executes.

Example of Asyncronous programming using javascript

![ASYNC](https://user-images.githubusercontent.com/123368493/216848069-64d6e70f-d684-463e-8925-199102d82e9f.PNG)

The setTimeout is what makes our code asynchronous. What the code does first in the example above is to log One. Then, instead of executing the setTimeout function, it logs Three before it runs the setTimeout function. Browsers run JavaScript, and there are web APIs that handle it for users. JavaScript passes the setTimeout function in these web APIs, and then our code keeps running normally. By running code asynchronously, other code is not blocked from running. When the work is complete, a notification is sent to the main thread about whether the task was successful or failed.


BENEFITS OF USING ASYNCRONOUS PROGRAMMING
1. Increase the performance and responsiveness of your application, particularly when you have long-running operations that do not require to block the execution. In this case, you can perform other work while waiting for the result from the long running task.

2. Organize your code in a neat and readable way significantly better than boilerplate code of the traditional thread creation and handling. you write less code and your code will be more maintainable.
All this and more are the importance of Asyncronous programming, you can use it for effieciency and save time.

--By Nnadi Emmanuel Onyedikachi
