.. include:: cyverse_rst_defined_substitutions.txt

|CyVerse|_ 

|Home_Icon|_ `Learning Center Home <http://learning.cyverse.org/>`_


**RStudio with Version Control**
================================

RStudio can be used with Git or SVN. For today's lesson we're going to be using Git with your new GitHub accounts. 

.. #### Comment: short description

**Some things to remember about the platform**

- You can pull other GitHub repositories using ``git clone`` via the RStudio terminal.
- Your local commits are not sent to GitHub until you initiate the repository with your GitHub username and password.  

----

*Instructions*
~~~~~~~~~~~~~~

  1. Create a GitHub Repository
  
  2. On your local computer, create a directory called ``~/github`` and change into that directory
  
  3. Open RStudio and start a new Project: *File > New Project > Version Control > Git*. In the ``repository URL`` paste the URL of your new GitHub repository
 
  4. Save your new git repository to the newly created ``~/github`` directory.
  
  5. Open the directory in RStudio

..
	#### Comment: Suggested style guide:
	1. Steps begin with a verb or preposition: Click on... OR Under the "Results Menu"
	2. Locations of files listed parenthetically, separated by carets, ultimate object in bold
	(Username > analyses > *output*)
	3. Buttons and/or keywords in bold: Click on **Apps** OR select **Arabidopsis**
	4. Primary menu titles in double quotes: Under "Input" choose...
	5. Secondary menu titles or headers in single quotes: For the 'Select Input' option choose...
	####

*Self Paced*
------------

`rOpenSci <https://github.com/ropensci>`_ is a leader in the development of reproducible research. There are hundreds of repositories to explore for examples of research using R.

|CyverseLogo|_ |LearningCenter|_ 

----

**Fix or improve this documentation:**

- On Github: |Github Repo Link|
- Send feedback: `Tutorials@CyVerse.org <Tutorials@CyVerse.org>`_
- Live chat/help: Click on the |intercom| on the bottom-right of the page for questions on documentation

----


.. Comment: Place Images Below This Line
   use :width: to give a desired width for your image
   use :height: to give a desired height for your image
   replace the image name/location and URL if hyperlinked


.. |CyVerse| image:: ../img/cyverse_cmyk.png
  :width: 500
.. _CyVerse: https://cyverse.org/

.. |CyverseLogo| image:: ../img/cyverse_globe_cmyk.png
  :height: 60
  :width: 60
.. _CyverseLogo: https://cyverse.org/

.. |LearningCenter| image:: ../img/Learningcenter_DkBlue.png
  :height: 60
  :width: 60
.. _LearningCenter: http://learning.cyverse.org/

.. Comment: Place URLS Below This Line

   # Use this example to ensure that links open in new tabs, avoiding
   # forcing users to leave the document, and making it easy to update links
   # In a single place in this document

   .. |Substitution| raw:: html # Place this anywhere in the text you want a hyperlink

      <a href="REPLACE_THIS_WITH_URL" target="blank">Replace_with_text</a>


.. |Github Repo Link|  raw:: html

   <a href="https://github.com/CyVerse-learning-materials/foss-2019/tree/master" target="blank">Github Repo Link</a>
