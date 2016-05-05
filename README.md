# edX RAW HTML boiler plate

Use this tool to develop small interactive html, css, js apps for RAW HTML xblocks in edX

## How to use

* ensure that you have **node.js** installed (to use npm which comes packaged with node.js)
* ensure that you have grunt-cli installed globally (to make use of grunt-contrib-watch)



1. Git Clone ... to your sites folder that is used by mamp (or whereever you run a localhost webserver)

2. Use your favorite web browser (use chrome) and go to localhost/path/to/directory (make sure the webserver is running)

3. Open terminal to the project's directory and run the following command

> npm run start

this will install npm packages and start grunt watch.

4. Start developing (write all your code within the commented section) ... :) (every time you save index.html, grunt automatically refreshes localhost/path/to/directory, if it doesn't, just refresh)

5. Once you are ready to use in the edX platform, just copy the code you have written into the RAW HTML component. 

6. If you notice any difference, it's most probably needs a css update. At which point experiment withing the browser's inspect element. 

7. If everything is working well and you tested on all browsers and mobile then ... 10 points to gryffindor. yay!

## Warning:

* There could be slight differences in css when you take your code into the xblock, these could be minor such as margins and paddings. 

* **DO NOT** import any js plugins or css frameworks without testing to see if it works on the edX platfrom, otherwise you're going to have a bad time.