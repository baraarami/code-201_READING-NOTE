# Debugging and Error Handling

It would be wonderful if we could, by some miracle, manage to create JavaScript applications that never fail, never have errors, never go wrong. Then we would have perfection and wouldn’t need things like debuggers and error handling. But what would be the fun in that?

There are two types of errors in JavaScript. The first is a programming error, where we, the JavaScript developers, do something wrong. These types of errors are typically found using our favorite browser and our favorite debugger.


If your JavaScript doesn't work as you expected it to, that might mean you have a bug in your code. tiny image of a bug

Typos are a common source of bugs in JavaScript. If your script isn't working, check the following:

Missing punctuation. Be sure every opening bracket has an accompanying closing bracket.
Unclosed character string. Whenever you're working with text in JavaScript (for example, when you displayed text in an alert box in the previous lesson), that text must be enclosed in quotation marks. You can use either single quotation marks ('...') or double quotation marks ("...") but be sure every opening quotation mark is closed at the end of the string of characters.
Misspelled variable. JavaScript is case-sensitive. In the example in the previous lesson, you created a variable called myText. That isn't the same as MyText; one has a lower-case M, the other does not. If you define a variable called myText, then try to execute the command alert(MyText) the script would fail because MyText doesn't exist.
Debugging is the art of finding bugs in your code, and fixing them.




Debugging using Alert
The alert() function can be very useful for debugging code. In the previous lesson, you created a showAlert() function, and added a link to your web page that triggers that function. If you click the link and nothing happens, what went wrong? It could be that there's a bug in the function, or it could be that the function was never triggered because there's something wrong with the link. To test whether there's something wrong with the function, you could add one or more alert() commands in strategic places

Debugging Using Browser Tools
Some browsers show an icon indicating when a JavaScript error has occurred on the page. For example, some versions of Internet Explorer, if debugging is enabled, 


Now, get to know how your browser reports errors (if at all). Try messing up the JavaScript code in your javascript.html page, using the errors from the above examples. With each example, what effect does the error have? Does your browser display an error icon or otherwise give you any indication that an error has occurred? If not, this feature is probably disabled in your browser and would need to be turned on in your browser's settings or preferences.

Also, most browsers today have debugging tools available, either built into the browser, or available for free as downloadable plug-ins. These tools typically include a Console tab that displays script errors if they occur; and a Script tab that allows you to step through your script line by line in order to identify problems. Using these tools is an advanced topic and is beyond the scope of this curriculum, but they're worth a look, and if you're comfortable with them they can be very helpful as you create more and more sophisticated web pages. Here are the developer/debugger tools that are available in several of the most popular browsers, and the steps for accessing them:

Firefox: Press Ctrl+Shift+I (Cmd+Option+I on Mac) to toggle Developer Tools (or select Tools > "Web Developer") from the menu.
Chrome: Press Ctrl+Shift+J (Cmd+Option+J on Mac) to bring up Developer Tools.
Internet Explorer 8 and higher: Hit F12 to access Developer Tools (or select "F12 Developer Tools" from the Tools menu)
Opera: Tools->Advanced->Error Console.
Safari: In Preferences > Advanced, check the "Show Develop menu in menu bar". Then, the menu bar will include a "Develop" option which has many features including Error Console, Web Inspector, JavaScript Profiler, etc).




