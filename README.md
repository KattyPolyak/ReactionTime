# ReactionTime
ReactionTime provides a testing suite to ensure that the features of Concurrent Mode in React will run optimally in order to provide the best developer experience possible that will in turn lead to a more satisfactory user experience. 

# Quick Start
In order to use ReactionTime, add the following syntax in a Jest testing environment:

`const reactiontime = require('reactiontime')`

'reactiontime' tests can be accessed as methods on the 'reactiontime' object.

Example syntax as follows:

`
reactiontime.createRootTest('src/index.js');
reactiontime.packageTest('package.json');
`

... 'src/index.js' is equal to the relative path of the highest component of your react tree.
<br>
... 'package.json' is equal to the relative path of your package.json.