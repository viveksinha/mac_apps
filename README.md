# Mac Apps
A Super Simple Desktop Client for Mac OSX Built in Javascript and MacGap

# Why
I love the Google suite but hate being limited to having to use their apps within my browser.  If you have many tabs, it's impractical for usability.

# What
It's one line of code to wrap Google Keep in an app window made possible by [MacGap](https://github.com/MacGapProject/MacGap2)

# Build

# Usage

    gem install macgap
    
    # macgap new DIR
    # macgap build DIR
    
For example, to create a new MacGap app use the `new` command:

    macgap new MyApp
    
To build a MacGap app use the `build` command, specifying the app's directory.
    
    macgap build MyApp
    
# Advanced
    
Or a more advanced example:

    macgap build --name MyApp --output ./build ./public

The directory (`DIR`) you specify should contain a file called `index.html` which will be loaded when the application starts.

# Icon

If the your application's root directory contains a file called `application.png`, that'll be used as the application's icon. 

# Run
Click the pretty icon :)

# More
Check out the [project page](https://chriskol.github.io/Desktop-Google-Keep-OSX/) for latest release binaries and stuff.

Also check out the same thing for Google Docs at [Google Docs Desktop for OSX](https://github.com/chriskol/Google-Docs-Desktop-OSX) or its [project page](https://chriskol.github.io/Google-Docs-Desktop-OSX/) for latest binaries here
