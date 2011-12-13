<h1>How to use:</h1>
<p>To use, go to /Library/Application Suppport/Titanium/mobilesdk/osx/<version>/iphone/Classes/ and paste the files of this GitHub directory. <u>Don't forget to make a backup of your files</u></p>

<h1>Coding:</h1>
<p>To program this, you have to make an Annotation, and put this property in the annotation object:</p>
<pre>var annotationPoint = Ti.Map.createAnnotation({
	latitude:<YOUR LATITUDE>,
	longitude:<YOUR LONGITUDE>,
	title:"Testing a draggable annotation",
	pincolor:Titanium.Map.ANNOTATION_RED,
	draggable:true
});</pre>

<h1>Credits:</h1>
<p>I use this directory <b>https://github.com/appcelerator/titanium_mobile</b> to make this modification.</p>
