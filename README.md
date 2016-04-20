<html>

  <body>
    <center><h1> Swift </h1></center>
    <center><h2> by Apple, and Michael Mattson </h2><br></center>
    <hr>
    <h2> What is Swift? </h2>
    <ul>
      <li>It's like C/Objective-C, but not pedantic and restrictive.</li>
      <li>Created by Apple as the flagship language for iOS, OSX, tvOS, and watchOS development.</li>
      <li>Is designed to minimize the work you have to do in debugging.</li>
      <ul>
        <li>Variable are initialized automatically before use.</li>
        <li>Memory is managed automatically.</li>
        <li>Nil values are managed through optionals.</li>
      </ul>
      <li>It also doesn't require Semicolons!</li>
    </ul>
    <hr>
    <h2> Objective C vs Swift </h2>
    Here is how we declare a function in Swift:
    <code>func someFunction(s:String, i: Int) -> Bool
{
    ...    code
}</code>
    <hr>
    <h2> Details </h2>
    <ul>
      <li>Swift is type-safe. It will infer variable types from the value assigned</li>
      <ul>
        <li>var x = 16 is an int.</li>
        <li>var y = "Hello" is a string.</li>
      </ul>
      <li>Constants can be set with let.</li>
      <ul>
        <li>let c = 3.</li>
        <li>c = 1 will cause an error</li>
      </ul>
      <li>Optionals</li>
      <ul>
        <li>Swift doesn't like nil.</li>
        <li>So, we can use ? to make swift accept a nil value.</li>
      </ul>
    </ul>
    <hr>
    <h2> Functions </h2>
    <ul>
      <li>Example Declaration:</li>
      <ul>
        <li>func someFunction(s:String, i: Int) -> Bool
          {
            ...    // code
          }</li>
      </ul>
      <li>Functions can return other functions</li>
    </ul>
    <hr>
    <h2>Read-Eval-Print-Loop</h2>
    <ul>
      <li>Also known as the REPL</li>
      <li>Accessible from terminal.</li>
      <li>Interactive version of Swift for speedy testing and debugging.</li>
      <li>Easiest place to run your code pre deployment</li>

      <hr>
      <br>
      <br>

  </body>
</html>
