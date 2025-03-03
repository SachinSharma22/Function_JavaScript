
<p>
 A regular expression is a sequence of characters that forms a search pattern.
 The user can define what needs to be searched i a text with the help of regular expression.

 Regular expressions can be of any number of characters, be it alphabet, digits or special characters.

 These expressions are more commonly used ofr text search and text replacement operations.
 </p>

 <p> <strong>Flags:></strong> There are several flags you can specify to alter the behaviour of a regular expression.
   Flags may be appended to the end of a regex literal or they may be specified as the second 
   argument to the Regular Expression</p>

   <p><strong>Patterns:></strong> Brackets are used to find the range of characters.</p>

   <p><strong>Quantifiers:></strong> Quantifiers define the number of occurrences of a string.</p>
   <h1>JavaScript Promises</h1>
   <p>JavaScript is predominantly single threaded. This makes it slow and restrictive <br>
   With the help of promises and other Asynchronous concepts, JavaScript can perform long network requests <br> simultaneously without  blocking the main thread.</p>
   <h1>What are JavaScript Promises?</h1>
   <p>A promises is an asynchronous action that may complete at some point in the future and produce a value. <br>
   <br> It notifies the user when its value is available. <br> <br>
   Promises provide a robust way to wrap the result of <br>asynchronous work, overcoming the problem of deeply <br>nested  callbacks.</p>

   <h1>States of Promises</h1>
   <p><strong>Pending:></strong> The underlying operation has not yet completed</p>
   <p><strong>Fulfilled:></strong> The operation has finished and the promise is fulfilled with a value.</p>
   <p><strong>Rejected:></strong> An error has occured during the operation, and the promise is rejected with a resason.</p>

   <p>A promises is said to be settled when it is either fulfilled or rejected <br>
   Once a promises is settled, it becomes immutable, and its state cannot change <br>
   then (callback) - used to attach a callback when the promise is resolved/ fulfilled. <br>
   catch(callback) - Used to attach a callback when the promise is rejected.</p>