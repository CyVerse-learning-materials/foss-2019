.. include:: ../cyverse_rst_defined_substitutions.txt


**VICE**
========

CyVerse data science workbench, the `Discovery Environment <https://de.cyverse.org/de/>`_, includes a feature called `VICE (Visual Interactive Computing Environment) <https://learning.cyverse.org/projects/vice/en/latest/>`_

VICE uses Docker containers to launch interactive programs, like RStudio, R Shiny Apps, Project Jupyter, Data Mining, and WebGL Applications that can be run in a browser. 

.. #### Comment: How to launch apps on VICE

**Visual Interactive Computing Environment**

- You can launch existing VICE images from the DE, or integrate your own using the Manage Tools. 
- VICE apps are containers, and your data are in the container until you move them off of it. Your results will be saved when the app terminates in your ``/username/analyses`` directory, unless you specify that the app results be saved elsewhere.

----

*Starting a VICE app*
~~~~~~~~~~~~~~~~~~~~

  1. Log into CyVerse `Discovery Environment <https://de.cyverse.org/de/>`_ or `CyVerse Run <https://cyverse.run>`_

  2. Select an application and start it
  
  3. After a few seconds to a couple of minutes (<2) your app should be running, you'll see a notification icon (bell) in the upper right corner of the DE, or click on `Analyses` to view the apps that you are running.

..
	#### Comment: Suggested style guide:
	1. Steps begin with a verb or preposition: Click on... OR Under the "Results Menu"
	2. Locations of files listed parenthetically, separated by carets, ultimate object in bold
	(Username > analyses > *output*)
	3. Buttons and/or keywords in bold: Click on **Apps** OR select **Arabidopsis**
	4. Primary menu titles in double quotes: Under "Input" choose...
	5. Secondary menu titles or headers in single quotes: For the 'Select Input' option choose...
	####


----

**Fix or improve this documentation:**

- On Github: |Github Repo Link|
- Send feedback: `Tutorials@CyVerse.org <Tutorials@CyVerse.org>`_

----


.. Comment: Place Images Below This Line
   use :width: to give a desired width for your image
   use :height: to give a desired height for your image
   replace the image name/location and URL if hyperlinked


 .. |Clickable hyperlinked image| image:: ./img/IMAGENAME.png
    :width: 500
    :height: 100
 .. _CyVerse logo: http://learning.cyverse.org/

 .. |Static image| image:: ./img/IMAGENAME.png
    :width: 25
    :height: 25



.. Comment: Place URLS Below This Line

   # Use this example to ensure that links open in new tabs, avoiding
   # forcing users to leave the document, and making it easy to update links
   # In a single place in this document

   .. |Substitution| raw:: html # Place this anywhere in the text you want a hyperlink

      <a href="REPLACE_THIS_WITH_URL" target="blank">Replace_with_text</a>


.. |Github Repo Link|  raw:: html

   <a href="https://github.com/CyVerse-learning-materials/foss-2019/tree/master/CyVerse/vice.rst" target="blank">Github Repo Link</a>
