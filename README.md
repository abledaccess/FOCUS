# FOCUS

Style while surfing the web with your keyboard.

## About

What do you do when you want/ need to use a website with a keyboard and there aren't styles to indicate what you are tabbing to on a page? You implement FOCUS, that what! This is, of course, my way of saying this solution is what I rely on when performing accessibility assessments. In fact, it's nothing more.

On with it! FOCUS, quite simply, is a "user defined style sheet" that allows a user to use a set of "styles" that your web browser will obey above all other styles declared by any web sites creator. Styles that give the :focus pseudo-element a dramatic appearance to give a user definite indication of what is actually focused on a webpage.

## How to...

... to get this to work for you in 4 major web browsers. Steps ranked from easiest to hardest.

- In Safari go to Preferences &gt; Advanced then select "Other", navigate to where you've saved/ put FOCUS.css in the drop down menu beside &#8220;style sheet&#8221;.

- In Internet Explorer go to Tools &gt; Internet Options &gt; General and choose the Accessibility button (the last button in the General pane). And in the dialogue box that pops up check the box beside "Format documents using my style sheet". Then you can "browse" and choose your style sheet once that checkbox is checked. Don't forget to click "Apply" before completely exiting "Internet Options".

- In Firefox (recent versions at least) <a href="https://addons.mozilla.org/en-US/firefox/addon/stylish/?src=search">install an "Add-on" named Stylish</a>. Then go into your "Add-ons manager" (Tools &gt; Add-ons), select "User Styles" in the left hand column and choose the "Write new style" button that is sitting in the main window. Once you choose that button you can name your new style declaration(s) anything you'd like. Then in the main window off the dialogue simply, for the purposes of this demonstration, <a href="https://github.com/abledaccess/FOCUS/blob/master/FOCUS.css">paste in the contents of FOCUS.css</a> (you can paste in the entire 11 lines of code, a lot of it are comments, it won&#8217;t affect how the CSS behaves). Then hit save. You should see the results of what you pasted in throughout Firefox now&nbsp;&mdash; though the fact that <em>everything</em> in Firefox that can receive focus gets styled can be jarring at first.</li>

- In Chrome (again recent versions) you need to <a href="https://chrome.google.com/webstore/detail/stylish/fjnbnpbmkenffdnngjfgmeleoegfcffe">install an "Extension" by the same name, and developer</a> as far as I can tell, as in Firefox. And follow the steps I outlined above.