1. What problems does the Observer Pattern seek to solve?
    - it enables one-to-many data binding between elements. This allows code to stay organized while being reusable.
2. What are the three mechanisms of the observer pattern?
    -subscribe: adds new observable events
    -unsubscribe: removes observable events
    -broadcast: executes all events with bound data

3. Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.
    It adds event listeners to allow it to upade information based on other information being passed/used.

Darryl's sporting goods: https://chrisjcurry.github.io/darryls-sporting-goods/