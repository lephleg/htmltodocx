HTML to docx Converter
======================

Requirements - server
=====================

PHP 5.2.x or later;
PHP Extension ZipArchive;
PHP Extension libxml;

Check output of phpinfo() to see if your installation meets these requirements.


Requirements - client
=====================

This converter produces Word documents in the docx (Office Open XML) file format. The client will need a programme that can open these, for example Microsoft Word 2007 or later or an earlier version of Word with the Micorsoft Office Compatibility Pack or Libre Office or Open Office.

Installation
============

Place the files on your web server somewhere where it serves files from - for example in a httpdocs directory.

Documentation and checking if it works
======================================

Browse to htmltodocx/documentation/index.php, for example go to http://mysite.local/htmltodocx/documentation/index.php in your web server if that is where you have placed your files.

You should be seeing a page of documentation, if not, then PHP is probably not set up properly on the server. Click on the link at the top of the page "Download this page as a Word document". Open the downloaded Word document - it should look similar to the documentation web page. If you encounter a problem here, check the server requirements above.

Understanding how it works
==========================

To get the best out of this software, you should read this documentation page in conjunction with the PHPWord documentation - PHPWord_Docs_0.6.2.docx - which you can find in the phpword directory. Understanding both of these will enable you to style the resulting docx documents in a way most appropriate for you.

Production sites
================

You don't need to - and it is probably not desirable to - include all the documentation on a production site. You will just need to keep the following directories and their contents:
- htmltodocx_converter
- phpword
- simplehtmldom

In addition, you could remove the "Example" directory from the phpword directory.

Project information
===================

htmltodocx
==========
Project home page:
htmltodocx.codeplex.com

PHPword
=======
Project home page:
phpword.codeplex.com
NOTE: the version of PHPword included here has been modified so that it can work with international character sets and to address a problem with table sizing when using LibreOffice.

Simple HTML dom
================
Project home page:
http://simplehtmldom.sourceforge.net/
 
