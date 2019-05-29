.. include:: cyverse_rst_defined_substitutions.txt

|CyVerse|_


**Websites & Documentation**
============================

This website is rendered using a `ReadTheDocs.org <https://readthedocs.org/>`_ template. Think of RTD as "Continuous Documentation".

ReadTheDocs has become a popular tool for developing web-based documentation. `CyVerse Learning Materials Github <https://github.com/CyVerse-learning-materials>`_ hosts a few templates which you can view and pull for your own use.

`Bookdown <https://bookdown.org/>`_  is an open-source R package that facilitates writing books and long-form articles/reports with R Markdown.

`GitHub Pages <https://pages.github.com/>`_ using `Jekyll <https://jekyllrb.com/>`_, are another popular way of hosting websites on GitHub.

.. #### Comment: short description

*Some things to remember about ReadTheDocs*
-------------------------------------------

- publishing websites via `ReadTheDocs.com <https://readthedocs.com/dashboard/>`_ costs money.
- You can work in an offline state, where you develop the materials and publish them to your localhost using `Sphinx <https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html>`_
- You can work on a website template in a GitHub repository, and pushes are updated in near real time using ReadTheDocs.com. 

*Some things to remember about Bookdown*
----------------------------------------

- Bookdown websites can be hosted by `RStudio Connect <https://www.rstudio.com/products/connect/>`_
- You can publish a Bookdown website using `Github Pages <https://github.blog/2016-08-17-simpler-github-pages-publishing/>`_

*Some things to remember about GitHub Pages*
--------------------------------------------

- You can pull templates from other GitHub users for your website, e.g. `academicpages.github.io <https://github.com/academicpages/academicpages.github.io>`_, `jekyll themes <http://themes.jekyllrc.org/>`_
- GitHub pages are free, fast, and easy to build, but limited in use of subdomain or URLs.

----

**Build your own Website**
--------------------------

*ReadTheDocs*
~~~~~~~~~~~~~

  1. `Install <https://docs.readthedocs.io/en/stable/install.html>`_

  2. `Use Github <https://github.com/rtfd/readthedocs.org>`_
  
  3. `Create a ReadTheDocs account <https://readthedocs.org/accounts/signup/>`_
    

*Bookdown*
~~~~~~~~~~

   1. `Install R and RStudio <https://www.rstudio.com/products/rstudio/download/>`_
 
   2. Install Bookdown package
   
   .. codeblock:: R
   
      install.packages("bookdown", dependencies=TRUE)

   3. Open the Bookdown demo and get started

*GitHub Pages*
~~~~~~~~~~~~~~

   1. Create a GitHub account
   
   2. Clone the repo ``https://github.com/username/username.github.io``
   
   3. Create an ``index.html``
   
   4. Push it back to GitHub


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
