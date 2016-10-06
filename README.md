# Processing Student Guide

<h2>Notes</h2>

* Survey to do at the end of every day: http://tinyurl.com/h6un4sf

# Goals for the Week

<h2>Primary Goal</h2>
* To learn how to learn independently and from your peers, rather than from us. 
 * We are facilitating the program, but we want to teach as little as possible. Instead, we would like you to teach yourselves by accessing online resources, and to teach each other. 
   * Why? After Friday, you are most likely going to be learning programming by learning on your own or by learning from each other.
   * So can you ask us questions? Sure, but in order to get you all used to not depending on us to learn, we will try as much as possible to ask questions to help you find answers, rather than answering your questions directly. Throughout the week, we will also introduce you to tools and resources that will make it easier to learn online and from each other.
   * This way of learning sounds hard.  Learning a new language is a lot of work. But if you work through the times when you’re stuck, when you don’t know what to do next, and you work together, depending on each other for learning things you don’t know, you can do it. I (Stuart) have seen this method work in a variety of disciplines… math, science, construction.

<h2>Secondary Goals</h2>
* To learn some computer programming skills.
* To make a piece of art that you’re proud of based on your knowledge of coding in Processing.
 * Whether you get to this point is based on how hard you work, and how well you work together to figure things out. If you don’t get to this, the goal is for you to know enough processing to do this on your own on any computer or smartphone.

# Plans for the Week

<h2>See what is possible with Processing</h2>
* Check out the first (5-minute long) video that plays when you go to http://hello.processing.org/editor/
* That video linked above is just the first of a one hour tutorial on processing that you can do later.
 * Check out some projects students made after just one hour doing that turorial. 
 * Check out a few graphic art projects Maker Mike made using Processing. 
 * Check out this online gallery of graphic art that artist Miguel Nóbrega made using Processing.

<h2>Setup</h2>
* To help us learn how to make the program better: 
 * Fill out the pre-survey at: http://tinyurl.com/z7gxuqq
* To program in the processing language anytime, anywhere:
 * Download Processing app on iPhone or Android phone.
   * On iPhone, go to App Store, search for, and download the app “Processing iCompiler.”     
    * If you open a processing coding file in “Processing iCompiler” and you can’t see all the text, click “Format”
   * On Android phone, go to the Google Play store and search for APDE or go to this link: https://play.google.com/store/apps/details?id=com.calsignlabs.apde
* To program in processing on the computer:
 * Set up processing application on Raspberry Pi and MacBook.
  * On MacBook (using the Ubuntu operating system):
    * Click in the very upper left corner of the screen to go to the menu.
    * Click “Graphic Design”.
    * Click “Processing”.
    * When the program opens, type ellipse(10,10,20,10);  and run the program by clicking the play button. A new window should appear and a circle should appear in the upper left corner of that new window. You’ve made your first program in Processing!
  * On Raspberry Pi:
    * Click “Menu”
    * Click “Programming”
    * Click “Processing”
    * When application opens, type:  rect(10,10,30,10);  and run the program by clicking the the play button. A new window should appear and a circle should appear in the upper left corner of that new window. You’ve made your first program in Processing!

<h2>Learn the Basics</h2>
* Do <a href="http://hello.processing.org/">this one-hour tutorial</a>
 * Why is this a good thing to do?
   * The tutorial outlines the basic words and grammar you need for this new language. When you learned English or a foreign language, you had to start with the basics, right? It is best to rewind the video every time you don’t understand something, and to pause the video and try things out as you go to check your understanding.
   * Learning to program from online resources like this video is great practice for learning how to learn without an “expert” around. Real-world programmers learn this way, by watching videos, reading instruction manuals, and asking each other questions on this website.
   * By the way, the link above is a good website to know. If you have questions about almost anything, you can set up an account and ask it there, and someone who knows the answer will get back to you, for free! 
  * Learning how to learn on your own (in Stuart’s opinion) is the most important skill you can have educationally. This is how we are measuring the success of our program this week. 
   * By the way, you might find useful the app used to make that last link.

<h2>Make Your First Piece of Art by Coding</h2>
* Make a piece of art to share with the group. 
 * To save your work: If you add the code below inside the draw () {      }  section of your code, your program will save an image file every time you press “S” or “s”. This is one way to save images that you could then print out and do anything with: hang up at the Y, display at the gallery show you all have coming up, or frame and sell.

if ( keyPressed ) {

    if ((key == 's') || (key == 'S')){
    
        saveFrame("images/Image-####.png");
        
    }
    
}

* On Wednesday around 6:40PM, we will showcase one of our projects to the group, explaining to each other how you made what you made, what was difficult, Interesting, what you want to do next, etc…

<h2>Increase Your Processing Vocabulary</h2>
Functions are the vocabulary of a programming language. Right now, your vocabulary includes rect(), ellipse(), and several other functions. Use the link above to make your vocabulary much larger, so you can tell the computer to do more things.
* Check out processing.org/reference to
 * Learn more about the functions that you’ve already learned.
 * Learn new functions. 
   * Example: Here’s a simple function that allows you to writes notes to yourself and other programmers inside the code without confusing the computer.
* Start with this code 

<h2>Suggestions for What to Do Next</h2>
Going forward, it’s up to you what you want to learn and what you want to make. This week during classtime we are focusing on making visual art with processing, but you can <a href="https://www.quora.com/What-can-I-do-with-Processing-Programming-language">do all kinds of other things</a> too. Here’s some other things made with processing: <a href="https://en.wikipedia.org/wiki/Digital_art">Url</a> <a href="https://www.linkedin.com/topic/animation-outsourcing">Url</a> <a href="https://processing.org/exhibition/">Url</a>

1. Find <a href="https://color.adobe.com/create/color-wheel/"aesthetically pleasing color combinations</a>. Try different color rules using the “Color Rule” button in the upper lefthand corner of the site. Note the R G B (Red, Green, Blue) values that appear below the colors that you can plug in as inputs to functions like background( ___ , ___, ___ );   stroke(___, ___, ___);   and   fill( __ , __ , __);
 *. Here’s another website that you can play with colors on.
2. Remix an existing project
 * Maker Mike has made a few graphic art projects he made using Processing publicly available, so click on the name above one of the photos to check out the code for that project. Change the code to remix it, and see what happens.
 * Modify the processing.org/gallery programs by clicking on a project, then clicking on “View Sketch Code” or “Download Code.”
3. Check out this introduction to the application that you have been using to write processing code on your computer: https://processing.org/reference/environment/
4. Check out some Books
 * “Getting Started with Processing” is a good place to start. 
 * If you’re interested in learning more about the Raspberry Pi, check out “Getting Started with the Raspberry Pi.”
5. Check out the processing.org/examples page to see how different parts of the Processing programming language to make programs. 
6. Share a Processing program you made with anyone in the world connected to the internet. 
7. Find out how and where you can print out a piece of art you made in Processing. You may want to use photo paper and a sufficiently large size() so that your image looks smooth when you print it and not blocky and pixelated.
8. Draw out what you envision making on paper, and ask about what you might need to learn to make what you’re thinking about.

# After This Week

# (Optional) Suggested Homework for the Week
Everything that was here is now included in the text above. Anything you can do in class with us, you can do out of class on your own time. The more you do on your own, the farther you can get. The farther you get, the more we can support you during this week that we are here.
