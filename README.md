# MVC-LH; Cross-Environment

reusing the same core application in different runtime environments by re-writing only the necessary pieces. 
* _dev-console_: a basic mvclh application that adds two numbers.  it loads into the browser by "script" tag and can be called from the console.
* _dom_: reuses controller, model & logic from "dev-console".  Has a new view & handler that connects to the DOM.
* _node_: reuses controller, logic & view from "dev-console".  Has a new handler that reads from _process.argv_, and a model that reads and writes from a text file.

___
___
### <a href="http://janke-learning.org" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Janke Learning</a>
