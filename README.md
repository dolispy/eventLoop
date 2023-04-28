# eventLoop

1. <b>What is the Event Loop?</b><br>
The event loop allows node to carry out non-blocking operations, despite the fact that javascript is single threaaded.It works as part of the node engine to handle the operations of call back functions.

2.  <b>Explain the 6 phases of the event loop</b>
    <ul>
    <li> Timers phase: This phase executes callbacks that use timers.</li>
    <li> Pending: This phase executes i/o operation that were defferred to the next loop cycle.</li>
    <li> prepare, idle: This phase runs internally. Poll: This phase executes input/output callbacks. </li>
    <li>Check or setImmediate phase: This phase executes any callbacks in set immediate timers from the poll.</li> 
    <li>Close or exit phase: This phase keeps running as far as there are timers or input/output callbacks. If there are none, the process ends.<li>
    </ul>


3. <b>List some best practices in server-side code development </b> <br>
Some best practices in server side dev are;<ul> 
    <li>Using Es6 async/await</li>
    <li>Keep code small </li>
    <li>Ensure code is readable </li>
    <li>Practice modularisation of code.</li> 
    <li>Handle Errors</li>
    </ul>

4. <b>What is NPM</b>
    <p>The NPM is the node package manager and it's responsible for managing all the dependencies our program needs to run both production dependencies and development dependencies</p>
5. <b> How do you initialize a package in npm</b>
    <p>You initialize a package by typing the command <b>npm init</b> or <b>npm init -y</b> in your command line interface.</p>

6. <b>How do you run a script in the package.json ?</b>
    <p>To run a script in the package.json file, you go to your package.json file and under the scripts object, add the terminal command you want to run as it's value. In your terminal, type the command: <b>npm run</b>