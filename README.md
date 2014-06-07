codeschool-intellij
===================

This is a port of the Codeschool theme for Vim, found at AstonJ's website:

http://astonj.com/tech/vim-for-ruby-rails-and-a-sexy-theme/

The theme here is geared towards IntelliJ IDEA use, and is recommended for users of the Darcula skin, or those that
prefer dark themes in general.

Things to keep in mind:

 - This is **heavily** geared towards a Java/JSP developer; bugs likely exist for your language of choice.
 - This has not been tested with any of the other JetBrains IDEs.  Breakage or incompatibility *may* arise.



Sample Gallery
==============

Generics and Breakpoint

 ![Generics and Breakpoint](images/codeschool-intellij_breakpoint.png)
 
Landing on a Breakpoint

 ![Landing on a Breakpoint](images/codeschool-intellij_breakpoint_hit.png)


 Annotation Coloring

 ![Annotation Coloring](images/codeschool-intellij_annotation.png)

 Diff Window Coloring

 ![Diff Window Coloring](images/codeschool-intellij_diff.png)

Terminal Error Message Coloring
 
 ![Terminal error message coloring](images/codeschool-intellij_terminal_error.png)


How to Build
============

This project uses Gradle to assemble the JAR.  Ensure that you have gradle installed, and run the command:

    gradle jar

...and you should have the working copy in your build/libs directory.


How to Install
==============

Under File > Import Settings, navigate to the folder in which the JAR was built (likely build/libs).  Import the color theme from it.


---

Feedback, patches, and pointing out general usability problems are always welcome.

