# Debugging
<p>&nbsp;</p>

![booom](https://miro.medium.com/max/626/1*B4jEYLg7oX3lcEH9C0YxaA.jpeg)
<p>&nbsp;</p>


JavaScript can be hard to learn and everyone makes mistakes when writing it. This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.

It would be wonderful if we could, by some miracle, manage to create JavaScript applications that never fail, never have errors, never go wrong. Then we would have perfection and wouldn’t need things like debuggers and error handling. But what would be the fun in that?

There are two types of errors in JavaScript. The first is a programming error, where we, the JavaScript developers, do something wrong. These types of errors are typically found using our favorite browser and our favorite debugger.

At a minimum, what we need from a debugger is the ability to stop program execution and then examine variables and objects at that point. It also helps if we can continue the program by steps, drill into functions, and examine network activity and the state of the DOM at any time. However, we can usually manage debugging if we have the ability to stop a program and examine object values.

The second type of error occurs when the web page reader answers a question incorrectly, pushes the wrong button, or tries to type in a Social Security number when we’re expecting a name. Or the error can happen when we’re mixing libraries and something goes wrong between them. We’ll look at these kinds of errors first, and then we’ll get into the various browsers and their debugging capabilities.

## Third-Party Services
There is a large number of emerging third-party services, that support JavaScript debugging and error handling, such as Bugsnag’s error monitoring platform. These tools provide insights of what's going on with the code running in various user's browsers so that it is possible to notify the development team with details of the issues with errors being logged. The main advantage of these types of services is that they provide the debugging and error handling remotely as a service so that it is possible to capture this valuable information to easily investigate an issue.

## Online and Desktop IDEs
Using Integrated Development Environments (IDEs) is the most popular ways to debug JavaScript Applications today. With the tight integration with browser tools, it is now possible to debug the code either from Online or Desktop IDEs, where it is possible to use the features like error logging, using keywords to break the code and using breakpoints. The advantage of this approach over the rest of the tools is that it is possible to investigate the issue from all the angles including the backend code.

## Effective Error Handling and Logs
### Handling Log Levels
When developing JavaScript applications it is important to have different levels of logging enabled. For example, when the application runs in testing or staging environments, it is possible to enable detailed logging including application flow, important variables & etc. while in production environments only to log errors. To achieve these, either a third-party JavaScript library or a custom implementation is required to manage log-levels.

### Log Transport
Since JavaScripts runs on client's browser, an error occurred remotely needs to be transferred to a new environment so that the development or ops team can investigate by accessing the logs.

### Log Formats
It is also important to have a format which is possible to be extended in future to support any new log data formats as well as to keep uniformity across different logging messages.

### Exception Handling
This is one of the key areas, where it is required to effectively handle the errors and show users with sufficient information about the situation and pass that information to the developer. This can also be handled based on Log Levels.


to know more about Error Handling & Debugging you van visit this [wesite](https://dzone.com/articles/effective-debugging-and-error-handling-for-javascr)
or you can red this [book](https://dzone.com/articles/effective-debugging-and-error-handling-for-javascr)
JavaScript book, Ch. 10, “Error Handling & Debugging”