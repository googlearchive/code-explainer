code-explainer
=========

Making pretty and informative code snippets.

![small_demo](https://cloud.githubusercontent.com/assets/6819944/11015499/2c595048-852f-11e5-9ba2-66c603df9a0b.png)

![collapse_image](https://cloud.githubusercontent.com/assets/6819944/11015523/fad28a66-852f-11e5-9a04-fc3845d4de76.png)

Running the demo locally:
```
bower install
npm install http-server

# link code-explainer into the bower_components, where it expects to be
mkdir bower_components/code-explainer
ln code-explainer.html bower_components/code-explainer/code-explainer.html


node_modules/.bin/http-server -p 8080 -a 127.0.0.1
# Navigate to localhost:8080/demo.html

```

A note about indentation
------------------------

The indentation is auto-adjusted to be relative to the first line of code:
```
<script type="text/template">>
	<!-- The indentation on this line (one tab) is the "baseline" for all other indentation-->
			<!-- Despite the source code having three tabs, this will only display as
			having two, due to the baseline -->
</script>
```
