<p align="center">
  <h1 align="center">Group-User-Directory</h1>
</p>

<h3 align="center">A tiny script to conveniently create groups, users, and shared directories in Linux.</h3>

<h2>Purpose</h2>
This script can be used for administration purposes to automate creation of groups, users, and directories while also being able to link with each other.

<h2>Current features (1.0)</h2>
The Script has 3 "modes", with each having their own set of commands.
<h3>GROUP mode</h3>
- Create group using group name
<h3>USER mode</h3>
- Create user account using username<br>
- Assign user account to an existing group
<h3>DIRECTORY mode</h3>
- Create shared directory without a specific group (ROOT)<br>
Using this will create groups under /home/directory<br>
- Create shared directory and assign primary group with RWX permissions<br>
Using this will create groups under /home/group/directory<br>
- Assign extra group (using setfacl) with R-X permissions to a shared directory<br>
- Assign second group (using setfacl) with RWX permissions to a shared directory

<h2>Disclaimer</h2>
This script is a proof of concept but still functional, hence me labeling the first release as 1.0.<br>
In the future I can implement more features like deletion, removing users from groups, and being able to create directories in any specified path.
