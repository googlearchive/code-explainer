code-explainer
=========

Making pretty and informative code snippets.

![small_demo](https://cloud.githubusercontent.com/assets/6819944/11015499/2c595048-852f-11e5-9ba2-66c603df9a0b.png)

![collapse_image](https://cloud.githubusercontent.com/assets/6819944/11015523/fad28a66-852f-11e5-9a04-fc3845d4de76.png)

Running the demo:
```
bower install
npm install http-server

# link code-explainer into the bower_components, where it expects to be
mkdir bower_components/code-explainer
ln code-explainer.html bower_components/code-explainer/code-explainer.html

node_modules/.bin/http-server -p 8080 -a 127.0.0.1
# Navigate to localhost:8080/code-explainer-demo.html

```
