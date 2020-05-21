# Effective Debugging and Error Handling for JavaScript


Debugging is a process for testing, finding the errors and reducing them from happening in future. Debugging JavaScript either requires having support for JavaScript debugger keyword, breakpoint support with web browser tools, or third-party tools. 


![](https://documents.lucidchart.com/documents/8ceba6cb-e76b-46d9-aacb-7634d0a92316/pages/0_0?a=511&x=161&y=376&w=838&h=508&store=1&accept=image%2F*&auth=LCA%20317957092f23c5ecbe7956b8e6a56c8676855ac9-ts%3D1522249997)


**Debugging is the process of finding errors. It involves a
process of deduction. **


### Breakpoints
Setting breakpoints is normally the first step of the debugging process. The built-in development tools in most browsers allow you to stop the execution of your code at a particular line of code and at a particular statement on every line of code running on the page being debugged, but for the purpose of this article, we will be specifically using the Chrome Dev Tools.

**The console helps narrow down the area in which the
error is located, so you can try to find the exact error. 
**
## JavaScript Errors - Throw and Try to Catch

The` try` statement lets you test a block of code for errors.

The `catch`statement lets you handle the error.

The `throw` statement lets you create custom errors.

The `finally` statement lets you execute code, after try and catch, regardless of the result.



### Errors Will Happen!
When executing JavaScript code, different errors can occur.

Errors can be coding errors made by the programmer, errors due to wrong input, and other unforeseeable things.


```javascript

<p id="demo"></p>

<script>
try {
  adddlert("Welcome guest!");
}
catch(err) {
  document.getElementById("demo").innerHTML = err.message;
}
</script>
```


If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback. 