# class 13 Reading:
### THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS:
- INTRODUCING HTML5 STORAGE:
TML5 Storage” is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.

![HTML5 STORAGE](https://lh3.googleusercontent.com/proxy/ObpHkz4bFNiwucoH5gyBxyCHgS_Y7R3fuGwi4bi9UQkbFUlCJWne0ONP3duYpZ_5nExFhaB5UXVXHZn1OYxTDelc1DtGTS2O6YOb0I3RN8jARWxZ)

- The latest version of pretty much every browser supports HTML5 Storage… even Internet Explorer
 IE   FIREFOX	SAFARI	CHROME	OPERA	IPHONE	ANDROID
8.0+	3.5+	4.0+	4.0+	10.5+	2.0+	2.0+

### USING HTML5 STORAGE


- HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. 

### HTML5 STORAGE IN ACTION:
- Let’s see HTML5 Storage in action. Recall the Halma game we constructed in the canvas chapter. There’s a small problem with the game: if you close the browser window mid-game, you’ll lose your progress. But with HTML5 Storage, we can save the progress locally, within the browser itself.