# Project 1 - Magnetic Poetry App
- Goal: To build a Magnetic Poetry App.


## Requirements

- Each partner individually completes the *Magneto Exercise* and posts it to mycourses (due XX/XX)
- Get a partner and post your names to the discussion thread. (due start of class, XX/XX)

### Required App Features for Checkpoint #1 (due Tuesday XX/XX - start of class)
***This is worth 10% of the Project 1 grade***

  - For this first deliverable, make sure that both partners do (or attempt) ALL of the coding requirements
  - The app is universal and runs on both iPhone and iPad. (*-2% if not done*)
  - The app uses Xcode 10.x/Swift 5/iOS 12.x (*-2% if not done*)
  - The app will start up with a set of related words on the screen - see mycourses for word sets, or come up with your own. (*-2% if not done*)
  - The words are draggable. (*-2% if not done*)
  - At startup, the word magnets will be neatly grouped near the top of the screen. Write code that places the magnets in rows, and puts space between words and the rows. To do this you will need to access the width and height of the magnets (labels) so that you know how tall to make your rows, and when you've run out of room on a row. 
  - All word labels will have exactly the same height which is `label.frame.size.height</code>`, and differing widths which is `<code>label.frame.size.width` (*3% if not done*)
  
*Tip: This might be a little tricky for you. Both partners should first attempt to do this by themselves. Ideally if you both get it working, you can submit the "best" solution.*
			
- The *Magneto* word magnets are too small, especially the ones with a single character. Solution: Add a space to boths of the ends of each label's text, then center align the text in the label. (*-3% if not done*)
- The app has a custom App icon - designed and created by you - for all iPad and iPhone sizes. <a href="https://designmodo.com/ios-app-icon-photoshop/">Here is a tutorial on how to create an app icon</a>. If you already have an image file you think could work as your icon (at least 1024x1024 pixels ideally), services like <a href="http://appicon.build">http://appicon.build</a> will generate all of the required icon sizes for you.(<i>-3% if not done</i>)</li>
			<li>Create a start up screen (on LaunchScreen.storyboard) that has the name of your app and your team members on it. Use an image (drag out a <code>UIImageView</code>), use auto-resizing or auto-layout to position it, and make sure it looks good on both iPhone and iPad. (<i>-3% if not done</i>)</li>
			<li>BOTH partners bring the app to class installed on their iOS hardware (<i>-3% if not done</i>)</li>
		</ol>
	</li>
	
### Required App Features for Checkpoint #2 (due Monday night XX/XX)
***This is worth 10% of Project 1 grade***
		<ol>
			<li>The user can load at least 3 distinct sets of words. (see the <i>Tables I-III Walkthrough</i> for ideas on how to let the user choose something from a list). Because multiple view controllers will depend on the same data, ideally you have 
			that data stored in just one place. 
			Also, use some  emojis if you like  -  <a href="http://getemoji.com">http://getemoji.com</a> & <a href="http://emojipedia.org">http://emojipedia.org</a> - (<i>-6 if not done</i>)</li>
			<li>Before loading a new word set the app needs to get rid of all of the old <code>UILabel</code>s. See this <a href="http://stackoverflow.com/questions/24312760/swift-how-will-i-remove-all-the-subviews-of-a-view/28516228#28516228">Stack Overflow post</a> on how to do this. (<i>-3 if not done</i>)</li>
			<li>When new word sets are loaded, make sure that the words are not too close to the top or edges of the screen for the user to tap. Test for this fact on a real device. (<i>-2 if not done</i>)</li>
			<li>Hide the status bar - you can do this on the main settings page for the app (<i>-2 if not done</i>)</li>
			<li>Make sure your app name matches the name on the icon  - see <a href="https://developer.apple.com/library/content/qa/qa1823/_index.html">developer.apple.com - Updating the Display Name of Your App</a> (<i>-2 if not done</i>)</li>
			<li>Get rid of all compiler warnings - including those for unused variables, missing icons, and broken Storyboard constraints (<i>-1 per compiler warning</i>)</li>
			<li>Make sure you still meet all of the checkpoint #1 requirements (<i>-1 per requirement not met</i>)</li>
		</ol>
	</li>
	
	<li><b>Required Final App Features  (due Sunday night 3/26) - no late submissions will be accepted - bring to class on your device the next day:</b>
		<ol>
			<li>The app should by now been thoroughly tested on iOS hardware:
				<ol>
					<li>The app should display properly on either landscape or portrait orientation, and on both iPhone and iPad. I recommend choosing one orientation for the app, either portrait or landscape, and making that the sole orientation of the app.</li>
					<li>There should be no obvious usability issues.</li>
				</ol>
			</li>
			<li>State Preservation. The user's current chosen category will be stored in <code>UserDefaults</code>, and the chosen word set will be displayed in when they launch the app.</li>
			<li>Use a larger font size when creating word magnets for an iPad. You can either:
look at the width of the screen (do a google search on how to get the width of the screen) and base the font size on that value, 
or check to see the device's "user interface idiom" - see this Stack Overflow post:
 				<a href="http://stackoverflow.com/questions/24059327/detect-current-device-with-ui-user-interface-idiom-in-swift">http://stackoverflow.com/questions/24059327/detect-current-device-with-ui-user-interface-idiom-in-swift</a>
				Be sure that the words can still fit on the smallest iPhone screens (the iPhone 5/iPhone SE)
			</li>
			<li>The user can share their poetry (a screenshot of the entire poem) with others using Social Networks with the <code>UIActivityViewController</code> class.</li>
			<li>The user can choose a poetry background image from their Photo Library with the <code>UIImagePickerController</code> class.</li>
			<li>The app meets all requirements of checkpoints #1 and #2 (-5% per requirement not met)</li>
			<li>Because multiple view controllers will depend on the same data, you have a <a href="https://developer.apple.com/library/content/documentation/General/Conceptual/DevPedia-CocoaCore/Singleton.html">Singleton</a> <a href="https://developer.apple.com/library/content/documentation/General/Conceptual/DevPedia-CocoaCore/ModelObject.html"><i>model class</i></a> that manages/contains your application data.</li>
			<li>Code Conventions
				<ul>
					<li>Class names are capitalized, instance variables begin in lowercase (<i>-1 per incidence</i>)</li>
					<li>Code files in the Xcode <i>Project Navigator</i> are organized in groups for example, <i>VC</i>, <i>Model</i>, <i>Lib</i>, <i>Helpers</i>, <i>Extensions</i> etc...(<i>-5 if not done</i>)
					<li>Get rid of all compiler warnings - including those for unused variables, missing icons, and broken Storyboard constraints (<i>-1 per compiler warning</i>)</li>
					<li>Use <code>//MARK: - Some Category -</code> in your view controller classes to organize your code. Possible categories include <code>ivars</code>, <code>Private Helper Methods</code>, <code>Storyboard Action Methods</code>, <code>Initialization</code>, <code>View Lifecycle</code>, <code>GestureRecognizer Action Methods</code>, <code>UIImagePickerController Delegate Methods</code>, and so on.</li>
					<li>If the app crashes, there will be an additional penalty of -10%</li>
				</ul>
			</li>
			
		</ol>
	</li>
	
	<li><b>Extra Features:</b>
		<ul>
			<li>Doing all of the above gets an 85% - to get a higher grade you need to go "above and beyond". Be sure to document your extras in a seperate file or in the comments field of the dropbox. If you don't, you will not get credit for them. Here are some ideas:
				<ul>
					<li>Add Word to existing word set/Make new word set</li>
					<li>Delete Words, and animate it - look at <i>Hello RIT-2</i></li>
					<li>Rotate words - see <i>GestureRecognizer Demo</i> in mycourses </li>
					<li>Custom Fonts - use a <code>UIPickerView</code> - see this tutorial - <a href="http://codewithchris.com/uipickerview-example/">http://codewithchris.com/uipickerview-example</a></li>
					<li>Slider for Font Size - use a <code>UISlider</code> see this tutorial - <a href="http://sourcefreeze.com/ios-slider-uislider-example-using-swift/">http://sourcefreeze.com/ios-slider-uislider-example-using-swift</a></li>
					<li>UI Animation - go back and look at <i>Hello RIT-2</i></li>
					<li>If the app force-quits, the user's last poem should be preserved, the previous background image will be restored, and all of the word magnets should be in the same location.</li>
					<li>... you decide!!! ...</li>
				</ul>
			</li>
		</ul>
	</li>
	</ol>
</section>



<section>
<h2>Handy Links</h2>
<ul>
	<li>Some examples of previous Magnet projects and best practices are here: <a target="_blank" href="pages/p1-images/Project-1-comments.pdf">Project-1-comments.pdf</a>
	<li><a href="http://magneticpoetry.com/pages/play-online">magneticpoetry.com</a></li>
	<li><a href="http://forum.rpg.net/showthread.php?590734-Lovecraftian-Letters-HPL-Fridge-Magnet-Set-Preorder-Special">Lovecraftian Letters</a></li>
	<li><a href="http://getemoji.com">getemoji.com</a></li>
	<li><a href="http://emojipedia.org">emojipedia.org</a></li>
	<li><a href="http://nshipster.com/uiactivityviewcontroller/">nshipster.com - UIActivityViewController</a></li>
	<li><a href="https://developer.apple.com/library/ios/documentation/UIKit/Reference/UIActivityViewController_Class/index.html">developer.apple.com - UIActivityViewController</a></li>
	<li><a href="https://developer.apple.com/library/ios/documentation/UIKit/Reference/UIActivity_Class/index.html">developer.apple.com - UIActivity</a></li>
</ul>

</section>

<section>
<h2>Code Hints</h2>
<h3>Hint #1</h3>
<p>The easiest way to add spaces to your magnets is to do so right after you create the label  - and to use string interpolation like so in your label creation loop:
<code>label.text = " \(word) " </code></p>

<h3>Hint #2</h3>
<p>Animating your magnets when they first appear on the screen or when a word category is changed is a nice effect. Below is code that I have running in my <code>placeWords()</code> method - in the loop that creates the magnets.</p>
<p>All of the words are initially placed at random location on the screen, with 0.5 opacity, and then moved to their proper calculated position in the animations: block below:
(The <code>center</code> variable is each word's proper ending position.)</p>

<pre>
// adapted from "Hello RIT II" ICE
UIView.animate(withDuration: 1.0,
    delay: 0.0,
    options: UIViewAnimationOptions.curveEaseInOut,
    animations: {
       l.layer.opacity = 1.0
       l.center = center
    },
    completion: nil
 )
 </pre>
 
 
 
<h3>Hint #3</h3>
<p>Hint #2 above works well when the magnet view first loads, and works fine on an iPad, but if you change the word category on an iPhone, and then return to the main magnet screen, the category has changed but the animation never happens.</p>
<p>I found a work around that uses the Grand Central Dispatch API (which we have not covered) to fire the animation 10 milliseconds after the words are added to the screen.</p>
<pre>
let fireTime = DispatchTime.now() + .milliseconds(10)
DispatchQueue.main.asyncAfter(deadline: fireTime){
    // UIView.animate() code goes here
     print("code will fire in 10 milliseconds)
} // trailing closure syntax!
</pre>


<h3>Hint #4</h3>
<p><em>Sick of everything in your app being gray?</em></p>

<p>
<code>UIAppearance</code> is a protocol on many UIKit classes that allows you to change the styling of UI elements for either your entire app, or just for for specific elements. See <b>Using UIAppearance</b> PDF in week 8.
</p>

<h3>Hint #5</h3>
<p>See the <b>UIInterpolatingMotionEffect Notes</b> PDF in week 8 of my courses to see how to add "kinetic realism" to your app. Put the effect on each word when you add them to the scene, and make the effect subtle.</p>


<h3>Hint #6</h3>
<p>When doing the final testing your app, be sure to delete it off of the simulator and your iOS device, reinstall it, and be sure that it works in the "first run" state.
This is necessary to do so that you can be 100% sure that your <code>UserDefaults</code> code is properly written.</p>
</section>
