
This branch is forked from https://github.com/milewise/node-soap. 

The last integration is based on the latest commit b46eefcad8 at 2012-12-11.

Install:  npm install soap-js

This branch fixes the defects below.

0.2.8
Fix the issue that namespace should propagate to child nodes and clean up of unused code. 
Accept the pull request https://github.com/milewise/node-soap/pull/74

0.2.9
Fix the mistake when merge the previous request.

0.2.10
Fix the issue in file lib/wsdl.js. the original code cannot handle the array correctly

0.2.11
Currently, the attribute whose value is zero or false will not be added to the xml content. This change allows zero and false as elements value.


## License
MIT license.



