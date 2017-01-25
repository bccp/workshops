Website of BCCP Workshops
=========================

This is the hosting repository for BCCP workshops. The idea is borrowed from Scipy-Conferences. 

Here, each workshop is set up as a branch. To start a new workshop, branch off from an existing workshop:

1. Select the base workshop from the branches menu of the github interface

2. Type a new branch name, in a format like `2017-non-linear-universe`. Github will ask you if you are to create a new branch. Select yes.

3. Now we are on the `2017-non-linear-universe` (or any branch name you decided). Edit the website to make sure information is accurate. (Sponser, Venue, Links to Schedule, Organizers, etc).

4. Edit this file [subsites]_ to add an entry for the website. The format of a line is

.. code ::

 Branch-name  |  URL on the bccp website | html | .
   

For example,

.. code ::

 2017-non-linear-universe | 2017-non-linear-universe | html | .



The last two words must be `html` and `.` -- those will be useful for future updates.
After the file is edited and committed, you shall soon be able to find the website online.
For our example, the url is `http://bccp.berkeley.edu/2017-non-linear-universe`.

5. Remember to add a link to the website to the workshops page of the bccp website.
 

.. [subsites] https://github.com/bccp/website/blob/master/subsites.txt




