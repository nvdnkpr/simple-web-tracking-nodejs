Simple Web tracking app in Node.js
---

Inspired by [flexible-user-tracker-in-a-few-lines-of-node](http://run-node.com/flexible-user-tracker-in-a-few-lines-of-node/)



npm init

vim app.js

```

```

npm install --save nodeagent;
npm install --save geoip-lite;


Add the following html snipp to any page in any app that you want to track
``` <img hidden src='http://localhost:9999/pagename' />  ```

run with ```node app.js``` to console out results.
run with ```nohup node track &``` and append results to a file.





