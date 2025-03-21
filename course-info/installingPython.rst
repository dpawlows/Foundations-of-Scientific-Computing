
Installing Python
=================

**In order to complete the tutorials and exercises, you should download a python distribution on your own computer.**  While the Mac computers in the campus computer labs have python installed on them, these versions may not have some of the packages that we will use in this course. The purpose of this page is to help you to
install Python and different Python packages onto your own computer. While it is possible to install Python from the Python homepage https://www.python.org/,
**we highly recommend using** `Anaconda <https://www.anaconda.com/download>`_ which is an open source distribution of the Python and R programming
languages for large-scale data processing and scientific computing. Anaconda combines a basic python distribution with many packages that are commonly used to do science. This makes life a lot easier for us, the users, in the
long run.

Downloading Anaconda
--------------------

To download the installer, head to the
`Anaconda Downloads page <https://www.anaconda.com/download>`_.
Once there, you have to enter your email and have a download link sent to you. Note that you do not have to check the "agree to receive communication" box.

.. figure:: images/anaconda_dl.png
    :width: 600px
    :align: center
    :alt: Anaconda download landing

    Anaconda download landing page.

The link that is sent to your email will take you to the downloads page. The Installer that you select will depend on your operating system and
system architecture, which Anaconda's website should automatically identify and allow you to simply click the green Download button. Anaconda is shipping with Python version 3.12 these days.

Install Anaconda to your computer by double clicking the installer and install it into a directory you want (you will need admin privileges).
If promped, install it to **all users** and use default settings.

Testing the install: Windows
----------------------------

Test that Anaconda´s *package manager* called ``conda`` works by
opening any Windows command prompt program (Command Prompt, Powershell, Anaconda Command Prompt, 
Anaconda Powershell Prompt should all work!) and running the command ``conda --version``. 
If the command returns a version number of conda (e.g. ``conda 24.11.0``) 
everything is working correctly.


Testing the install: Mac
------------------------

On a Mac, open up the Terminal application (Applications - Utilities - Terminal) and enter ``conda --version`` to
verify a correct installation.

.. note:: The ``conda`` command  
          can be used to install
          packages that
          were not included with the base distribution, though we probably
          won't need to do that in this course.

Issues installing
-----------------

There are a variety of reasons why testing the installation may not work. So, if you run into an issue, please reach out to me!

Updating
--------

Once you start using Anaconda or the Spyder IDE, you
may get the occasional "software needs updating" dialog
box popping up. Updating is easy from the Command prompt
(windows) or Terminal (Mac). Simply execute the command
``conda update spyder`` and follow the instructions.
