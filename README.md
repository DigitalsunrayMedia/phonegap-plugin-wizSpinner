

# PLUGIN: 

phonegap-plugin-wizSpinner<br />
phonegap version : 1.7<br />
last update : 31/05/2012<br />

<br />
![MLB](https://github.com/Wizcorp/phonegap-plugin-wizSpinner/blob/develop/screen.jpg?raw=true)
<br />
# DESCRIPTION :

PhoneGap plugin for creating and manipulating native loader/spinner above Cordova.
<br />
NOTE - Android is portrait only
<br />
<br />
# EXAMPLE CODE : #
<br />
<br />
Create spinner<br />
<pre><code>
wizSpinner.create(Function success, Function fail, JSONObject options);
Example option object;
{
"showSpinner": TRUE, [TRUE/FALSE - default : TRUE]
"position": "low", ["low", "middle" - default : "low"]
"spinnerColour": "white", ["white", "grey" - default : "white"]
"opacity": "0.0", [0.0/1.0 - default : 0.0]
"labelText": "Loading...", [default : "Loading..."]
"textColour": "white" ["white", "black" - default : "white"]
};
</code></pre>
<br />
<br />
Show spinner<br />
<pre><code>
wizSpinner.show(Function success, Function fail, JSONObject options);
Example option object;
{
"showSpinner": TRUE, [TRUE/FALSE - default : TRUE]
"position": "low", ["low", "middle" - default : "low"]
"spinnerColour": "white", ["white", "grey" - default : "white"]
"opacity": "0.0", [0.0/1.0 - default : 0.0]
"labelText": "Loading...", [default : "Loading..."]
"textColour": "white" ["white", "black" - default : "white"]
};
</code></pre>
<br />
<br />
Hide spinner<br />
<pre><code>
wizSpinner.hide(Function Success, Function fail); 
</code></pre>
<br />
<br />
Rotate spinner<br />
This is handled by PhoneGap event listener, though you can force this if you wish.<br />
<pre><code>
wizSpinner.rotate(Int orientation);
</code></pre>



# DOCS & SUPPORT :

PhoneGap v1.7
Docs coming soon...