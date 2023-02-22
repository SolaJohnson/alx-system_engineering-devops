<ol start="0">
<li> Print the absolute path name of the current working directory.
<li> Display the contents list of your current directory
<li> Changes the working directory to the user’s home directory
<li> Display current directory contents in a long format
<li> Display current directory contents, including hidden files (starting with .). Use the long format.
<li> Display current directory contents.
  <ul>
      <li>Long format
      <li>with user and group IDs displayed numerically
      <li>And hidden files (starting with .)
   </ul>
 <li> Create a directory named 'my_first_directory' in the '/tmp/' directory.
 <li> Move the file 'betty' from 'tmp/' to '/tmp/my_first_directory'
 <li> Delete the file 'betty'.
      <ul>
          <li> The file 'betty' is in '/tmp/my_first_directory'
      </ul>
 <li> Delete the directory 'my_first_directory' that is in the '/tmp' directory.
 <li> Change the working directory to the previous one.
 <li> Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the '/boot' directory (in this order), in long format.
 <li> Prints the type of the file named 'iamafile'. The file 'iamafile' will be in the '/tmp' directory when we will run your script.
 <li> Create a symbolic link to '/bin/ls', named '__ls__'. The symbolic link should be created in the current working directory.
 <li> Copy all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. (You can consider that all HTML files have the extension '.html')
 </ol>
 
 <ol start="100">
 <li> Create a script that moves all files beginning with an uppercase letter to the directory '/tmp/u'. (You can assume that the directory '/tmp/u' will exist when we will run your script)
 <li> Delete all files in the current working directory that end with the character '~'
 <li> Create a script that creates the directories 'welcome/', 'welcome/to/' and 'welcome/to/school' in the current directory. You are only allowed to use two spaces (and lines) in your script, not more.
 <li> Write a command that lists all the files and directories of the current directory, separated by commas (,).
    <ul>
        <li> Directory names should end with a slash (/)
        <li> Files and directories starting with a dot (.) should be listed
        <li> The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
        <li> Only digits and letters are used to sort; Digits should come first
        <li> You can assume that all the files we will test with will have at least one letter or one digit
        <li> The listing should end with a new line
    </ul>
<li> Create a magic file 'school.mgc' that can be used with the command 'file' to detect 'School' data files. 'School' data files always contain the string 'SCHOOL' at offset 0.
