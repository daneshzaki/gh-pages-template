* Using a dialog theme in the Manifest XML makes an app "float" over other apps

* To hide the title of a window, use: 
`requestWindowFeature(Window.FEATURE_NO_TITLE);`

* Using the same name for two activities in a manifest XML results in a "Complete action using" dialog

* Intents are a combination of data and action, e.g.
`Intent i = new Intent(android.content.Intent.ACTION_DIAL, Uri.parse("tel:+919884200096"));`

* Fragments are "mini activities" useful in setting the layout of an app dynamically between a tablet and a smartphone 
