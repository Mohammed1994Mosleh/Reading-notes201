# class09 Reading:
## Forms:
The best known form on the web is probably the search box that sits right in the middle of
Google's homepage.
In addition to enabling users to search, forms also allow users= to perform other functions
online. You will see forms when registering as a member of a website, when shopping online, and when signing up for newsletters or mailing lists.
![Form](https://i.stack.imgur.com/5MatP.png)
### Form Controls:
- ADDING TEXT(Text input):
- Password input
- Text area (multi-line)
### Making Choices:
- Radio buttons
- Checkboxes
- Drop-down boxes

#### Submitting Forms: Uploadi ng Files::
- Submit buttons
- Image buttons
- Uploading Files:


### Form Structure:
<form action="http://www.example.com/subscribe.php"
method="get">

- text input:
<input type="text" name="username" size="15"
maxlength="30" />
- Password Input:
<input type="text" name="username" size="15"
maxlength="30" />
- Text Area:
<textarea name="comments" cols="20" rows="4">Enter
your comments...</textarea>
- Radio Button:
<input type="radio" name="genre" value="rock"
checked="checked" /> Rock
- Checkbox:
<input type="checkbox" name="service"
value="itunes" checked="checked" />
- Drop Down List Box:
<select name="devices">
<option value="ipod">iPod</option>
<option value="radio">Radio</option>
<option value="computer">Computer</option>
</select>
- File Input Box:
<input type="file" name="user-song" /><br />
<input type="submit" value="Upload" />
- Submit Button:
<input type="submit" name="subscribe"
- Image Button
<input type="image" src="images/subscribe.jpg"
width="100" height="20" />


## Events:
### DIFFERENT EVENT TYPES:
- UIEVENTS(load,unload,error)
- KEYBOARD EVENTS(keydown,keyup,kepress)
- MOUSE EVENTS(click,mousedown,mouseup)

##### EVENTS TRIGGER SCRIPTS:
Events are said to t rigger a function or script. When the click event
fires on the element in this diagram, it could trigger a script that enlarges
the selected item.

#### envent handling:
When the user interacts with the HTML on a web page, there are three
steps involved in getting it to trigger some JavaScript code.
Together these steps are known as event handling.

1. Select t he element node(s) you want the script to respond to.
2. Indicate which event on the selected node(s) will trigger the response.
3. State the code you wantto run when the event occurs.
![event](https://i.stack.imgur.com/L7xjo.png)
### Eevent flow:


When an event occurs, the event object tellsyou information about the event, and the element it happened upon.