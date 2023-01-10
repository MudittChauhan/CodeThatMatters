<h3> Linux Commands </h3>
<ul>
  <li> <code>ls</code>
    <ul> 
      <li> <code>ls</code> : Listing files in the directory </li>
      <li> <code>ls -a</code> : Listing with the hidden files </li>
      <li> <code>ls -l</code> : Shows all files, but not the hidden ones, with details like file permissions, user and timestamp  </li>
    </ul>
  </li>
<br>
  <li> <code>cd</code>
    <ul> 
      <li> <code>cd &lt;dir name&gt; </code> : Will take us to that particular directory </li>
      <li> <code>cd ..</code> : Will take us back one directory away </li>
      <li> <code>cd ../..</code> : Will take us back 2 directories away  </li>
      <li> <code>cd --</code> : Will take us back to home directory  </li>
    </ul>
  </li>
<br>
  <li> <code>touch</code>
    <ul> 
      <li> <code>touch &lt;file name&gt;</code> : It will create a new blank text file. If that file is already created, then touch command will update the timstamp of that file to the latest
      </li>
    </ul>
  </li>
<br>
  <li> <code>man</code>
    <ul> 
      <li> <code>man</code> : Used to see the manual of a particular command.<br>For ex: <code>man ls</code> will show us what ls command do. In case we are not sure about the command name, we can also do a keyword search using <code>-k</code>. For ex: <code> man -k ls </code>
      </li>
    </ul>
  </li>
<br>
<li> <code>cp</code>
  <ul>
    <li> <code>cp</code> : This command is used to copy a file from one location to another.<br>For ex: <code>cp /unix/test.txt ~/</code> - this will copy the file test.txt from unix dir to home directory.
    </li>
  </ul>
</li>
<br>
<li> <code>mv</code>
  <ul>
    <li> <code>mv</code> : We can use it in 2 ways, either for moving a file from one location to another, or renaming a file.<br>For ex: <code>mv /unix/test.txt /abc/</code> - This will move the file
		<br><code>mv /unix/test.txt /unix/test01.txt</code> - This will rename the file from test.txt to test01.txt
    </li>
  </ul>
</li>
<br>
<li> <code>links</code>
  <ul>
    <li> <code>links</code> : This command is use to create shortcut and links of the file. We can create shortcut of a file which known as Symbolic links, or can create different named links that points to a same file, having the same inode, known as Hard links.
      <br>For ex: <code>ln -s abc.txt myshortcut</code> :  This will create a shortcut myShortcut of file abc.txt
		<br><code>ln abc.txt hLnk</code> : This will create a link with name hLink with the same data and inode as of abc.txt
    </li>
  </ul>
</li>
<br>
<li> <code>mkdir</code>
  <ul>
    <li> <code>mkdir</code> : This command will create a new directory.<br>For ex: <code>mkdir unixfolder</code> command will create a new directory named unixfolder.
    </li>
  </ul>
</li>  
<br>
<li> <code>rmdir</code>
  <ul>
	  <li> <code>rmdir</code> : This will delete the directory, only if it is empty.</li>
    <li> <code>rmdir -p <dirname></code> : This will delete the empty directory with all the empty nested directories.</li>
    <li> <code>rmdir -r <dirname></code> : This will recursively delete the directory along with all its files & sub-directories.</li>
    </li>
  </ul>
</li>  
<br>
 </ul>
