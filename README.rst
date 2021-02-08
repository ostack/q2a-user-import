=============================
q2a-user-import
=============================

-----------------------------
Compatible with Q2A versions:
-----------------------------

- 1.6.1 (Tested)
- 1.6.3 (Tested)

Should be compatible with 1.6.x and more. If you have it working on a version let me know and I'll add it to the list.

-----------
Description
-----------

User Import plugin for Question2Answer CMS.

--------
Features
--------

- Bulk import users into Q2A via an uploaded CSV file
- Automatically sends email to each user

------------
Installation and use
------------
#. Install Question2Answer_
#. Get the source code for this plugin from github_, either using git_, or downloading directly:

   - To download using git, install git and then type 
     ``git clone git@github.com:thisliquidspace/q2a-user-import.git backup``
     at the command prompt (on Linux, Windows is a bit different)
   - To download directly, go to the `project page`_ and click **Download**
#. Upload the **q2a-user-import-master.zip** to your qa-plugin directory, unpack and rename '**q2a-user-import-master**' directory to '**q2a-user-import**' (IMPORTANT!)
#. Navigate to your site, go to **Admin > Plugins** on your q2a install and go to section '**User Import**'
#. Select a local CSV file (correctly formatted) via '**Browse**' and then '**Upload to server**'. The file should appear in the plugin window.
#. Select the file via the corresponding radio button and then press '**Test selected file!**'.
#. Check the list generated for any badly formatted emails or illegal usernames.
#. Select the file again (prevents accidents) via the corresponding radio button and then press '**Import selected file!**'.
#. Your users will not receive the system standard sign-up email.
#. Delete all of the CSV files from the system by clicking '**Delete all files**'.

.. _Question2Answer: http://www.question2answer.org/install.php
.. _git: http://git-scm.com/
.. _github:
.. _project page: https://github.com/thisliquidspace/q2a-user-import

------------
CSV File format
------------
The CSV file should consist of lines in the following format:

"<email address>","<plain text password>","<username>"

See test.csv for example.

----------
Disclaimer
----------
This is **beta** code.  It is probably okay for production environments, but may not work exactly as expected.  Refunds will not be given.  If it breaks, you get to keep both parts.

-------
Release
-------
GNU GENERAL PUBLIC LICENSE v2 See 'LICENSE' for more information.

---------
Credits
---------
Plugin based on https://github.com/thisliquidspace/q2a-user-import

Sponsored by BuiltIntelligence_.

Development by thisLiquidSpace_

.. _BuiltIntelligence: http://builtintelligence.com
.. _thisLiquidSpace: http://thisliquidspace.com

Fix import file issue for 1.8.5 by ZhaoGuangyue_

.. _ZhaoGuangyue: https://github.com/ostack/q2a-user-import

----------
Donate
----------
Donate by paypal_

.. _paypal: https://paypal.me/guangyuezhao

---------
About Q2A
---------
Question2Answer is a free and open source platform for Q&A sites. For more information, visit:

http://www.question2answer.org/