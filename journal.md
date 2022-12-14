# coding-journal
<h2><strong>#100daysofcode Challenge</strong></h2>
<br>
<strong>Journal Entry Template</strong>
<br>
Reviewed:
<br>
Learned:
<br>
Confused:
<br>
<h3>12.14.22 - Day Twenty Four</h3>
<strong>Reviewed:</strong> How to use an anchor element to link text. The key is to leave opening tag open, set attribute, use ">", insert visible text here, THEN close the element with a closing tag. Syntax is important!
<br>
<br>
<strong>Learned:</strong> How to add a footer, header, doctype, language, and meta attributes. HTML5 uses the UTF-8 encoding so browsers can translate the text correctly. Thankfully I've been watching CS50 to know a little of what this means.
<br>
<br>
<strong>Update!</strong> 
<br> 
I understand the distinctions between form elements. See below.
<br>
<br>
<strong>Important Notes</strong>
<ul>
    <li>The <em>label</em> element associates text with an input element
    <li>The <em>ID</em> attribute marks an element as distinct inside the HTML file. The ID is NOT visible text. Visible text is written outside the <em>input</em> element. 
    <li>The <em>name</em> names the input field. (i.e firstname: Zachary, lastname: Peterson. In this example <em>firstname</em> and <em>lastname</em> would be the <em>name</em> for the input field)
    <li>The <em>value</em> attribute is the data stored by your input field. (i.e. value would be Zachary or Peterson)
</ul>
<br>
<strong>Confused:</strong> Nothing today but I'm going to review the last few lessons once more before starting on CSS tomorrow! So excited to finally finish something!!! (How do I add party emojis??)
<br>
<h3>12.13.22 - Day Twenty Three</h3>
<strong>Reviewed:</strong> How to use for attribute correctly with label element. Key detail, the opening tag includes the attribute BEFORE closing it.
<br>
<br>
<strong>Learned:</strong> How to add multiple checkbox elements. Pretty much copy paste with different text. Also figured out how to use Homebrew to download Github CLI. Still need to learn how to use it though.
<br>
<br>
<strong>Confused:</strong> Still confused on the difference between name, ID, and value. They all sound similar and host similar input.
<br>
<h3>12.12.22 - Day Twenty Two</h3>
<strong>Reviewed:</strong> How to use fieldset and legend. Fieldset groups the items of a form together. Legend acts as a caption for form inputs.
<br>
<br>
<strong>Learned:</strong> The <em>for</em> and <em>ID</em> attributes both can be used to link element text with the text itself. I got stuck here and was very annoyed. Code should work but it doesn't. I re-read the instructions. Googled how to use "for" element and reviewed FCC's help forum for the question. Other people made obvious mistakes (typos, missing tags, etc.) Mine should work but it doesn't.
<br>
<br>
<strong>Update!</strong>
<br>
I used ChatGPT to find the error in my code. It explained it much simpler than any of the forums I found online. The opening label elemnent has to be open for the "for" attribute to work. Syntax error.
<br>
<br>
<strong>Fixed code</strong>
&lt;input id="loving" type="checkbox"&gt; &lt;label for="loving"&lt;Loving&gt;
<br>
<br>
<strong>Broken code</strong>
<br>
&lt;input id="loving" type="checkbox"&gt; &lt;label&gt;Loving for="loving"&lt;/label&gt;
<br>
<h3>12.11.22 - Day Twenty One</h3>
Created new journal format and learning process. Will review previous lessons each day before starting new lessons. This will improve understanding and memory.
<br>
<strong>Reviewed:</strong> How to use radio button, label, ID, name, value, fieldset, and legend.
<br>
<br>
<strong>Learned:</strong> Elements are whole strings of code. An element includes the tag and attributes (aka tag modifiers). Tags are the opening and closing pieces of code. Nesting is when one element is placed in the middle of another element. 
<br>
<br>
<strong>Important Notes</strong>
<ul>
    <li>The <em>label</em> element makes text clickable in a radio button.
    <li>The <em>ID</em> attribute marks an element as distinct inside the HTML file. The ID is NOT visible text. Visible text is written outside the <em>input</em> element. 
    <li>The <em>name</em> attribute ensures clicking one radio button deselects the other option. The name must be the same for all buttons. 
    <li>The <em>value</em> attribute is the data stored by your form. Value should match the name and ID for consistency.
</ul>
<h3><i>12.10.22 (Day Twenty)</i></h3>
Today I learned how to use the fieldset and legend element. Legend is used with forms to give written context. Fieldset acts as a section around the form. Not sure what the difference is from a regualar section element.
<h3><i>12.9.22 (Day Nineteen)</i></h3>
Today I learned how to use the name and value attributes in a form. I'm still trying to understand why each of these are important. <em>Input</em> is the primary element. <em>ID</em> vs <em>Value</em> vs <em>name</em> confuses me because they all have the same text "indoor". Something to figure out tomorrow.
<h3><i>12.8.22 (Day Eighteen)</i></h3>
Today I learned how to add radio buttons to my form. Here's an example <input type="radio">. I also learned how to nest it within a label element to make the radio text clickable. I can improve the internalization of each concept by reviewing previous concepts first. And only doing 3-5 lessons per day.
<h3><i>12.7.22 (Day Seventeen)</i></h3>
Today I reviewed how to create a form. I'm a bit confused on the <em>action</em> attribute. I imagine I need to setup a database for the form to submit to? I learned how to use <em>required</em>, <em>button</em> and <em>submit</em> to ensure the form works correctly. Lessons are getting more intense!
<h3><i>12.6.22 (Day Sixteen)</i></h3>
Today I learned to use the <em>input</em> element in a <em>form</em> with attributes (modifiers) <em>text</em>, <em>name</em>, and <em>placeholder</em>. Attributes allow you to change how the primary element functions. My library of elements and attributes is growing!
<h3><i>12.5.22 (Day Fifteen)</i></h3>
Today I learned to use the <em>form</em> element and <em>action</em> attribute. I realized that attributes act as modifiers to elements. Also realized it helps if I review my previous code before learning the new stuff. This makes previous concepts easier to remember and use. I was also able to setup Git. Turns out I wasn't following the instructions correctly. Tomorrow I'll try to understand how to use Git.
<h3><i>12.4.22 (Day Fourteen)</i></h3>
Today I tried to install Git using Homebrew. But I got stuck on creating a zprofile since I'm using Apple silicon mac. Learned how to create ordered lists. I was a bit faster today because I remembered general syntax rules.
<h3><i>12.3.22 (Day Thirteen)</i></h3>
Today I finally caught up to where I was previously in FCC. I reviewed how to use the <em>figure</em> and <em>figcaption</em> elements. I finally understand that most elements have an open and closing tag. They can also be nested within other elements. Elements are a critical part of learning HTML. <strong>I can improve by expanding my element library and remembering which elements produce the desired results.</strong>
<h3><i>12.2.22 (Day Twelve)</i></h3>
Today I reviewed how to use img src to link online photos. Coding syntax is important. I can improve by understanding how each element of code connects to the next and why.
<h3><i>12.1.22 (Day Eleven)</i></h3>
Today I re-learned how to use target="_blank" in an href element to open a new tab on click. Also re-learned how to add sections to my code. I can improve by finding a way to get more reps on each skill. It's difficult to remember what I've learned when I only use it once.
<h3><i>11.29.22 (Day Ten)</i></h3>
Today I learned my coding journal file extension was MD which means markdown. I changed it to HTML. I also learned VSC linting extensions help find syntax errors. What I can do to improve is implement more repetition. New skills don't stick without practice.
<br>
<h3><i>11.28.22 (Day Nine)</i></h3>
Setup VSC on new laptop. Created test doc in Github desktop. Reconnected VSC to Github profile to autosave changes like this. Will start daily coding practice on Thursday Dec 1st.
<br>
<h3><i>7.16.22 (Day Eight)</i></h3>
Worked on Cat Photo app from FCC. Learned how to open links in new tab with blank target, add sections within main, add undordered lists, and use the element figcaption. (today was the techlahoma code camp at Clevyr)
<br>
<h3><i>7.13.22 (Day Seven)</i></h3>
Added a skills table to my <a href="https://github.com/Zacharyjpeter/coding-journal/blob/main/Sololearn%20CV%20Project.html"> Fake CV Project</a>. Fixed the table border and spacing on <a href ="https://zacharyjpeter.github.io"> my portfolio website </a> under the project section. 
<br>
<h3><i>7.13.22 (Day Seven)</i></h3>
Added a table to <a href ="https://zacharyjpeter.github.io"> my portfolio website </a> under the project section. The goal is to have projects posted like a showcase. Need to add links and space text out. Could potentially host example financial blog posts there too.
<Br>
<h3><i>7.12.22 (Day Six)</i></h3>
Added <a href="https://github.com/Zacharyjpeter/coding-journal/blob/main/Sololearn%20CV%20Project.html"> Fake CV Project</a> from Sololearn to project journal. Learned how to create lists. Added fake job titles and descriptions.
<br>
<h3><i>7.11.22 (Day Five)</i></h3>
Updated <a href ="https://zacharyjpeter.github.io"> my portfolio website </a>. Added three sections and spiderman gif just for fun. Started working on Cat App from FCC. Not sure how to link to FCC projects yet.
<h3><i>7.10.22 (Day Four)</i></h3>
CSS in Sololearn. Learned difference between inline, internal, and external CSS. Markdown doesn't support CSS. 
<br>Tried adding stylesheet to my website project. No luck. Started process of applying Jekyll theme instead.
<br>
<h3><i>7.9.2 (Day Three)</i></h3>
Started my <a href ="https://zacharyjpeter.github.io"> Github website </a> using VSC, Homebrew, and MacOS terminal!
<br>HTML in Sololearn. Learned how to add an image with alt text.
<img src ="https://cdn0.iconfinder.com/data/icons/logos-21/40/GitHub-1024.png" height="100px" alt="github icon"/>
<h3><i>7.8.22 (Day Two)</i></h3>
HTML in Sololearn. Learned difference between element and attribute.
<br><p align ="center">This is how you can make text shift on the page</p>
<h3><i>7.7.22 (Ground Zero)</i></h3>
HTML in Sololearn. Current project is a resume. So far I've learned how to use headers, line breaks, and text emphasis. Today I added a summary section using the "p" element and h1. This display is proof of my progress!

