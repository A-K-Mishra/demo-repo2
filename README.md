# Demo 2 : Creating a Repository from Local PC
<ul>
<li><em>After creating a folder that will be our repository in our PC we make it a git repository by using the command : <div><strong>git init</strong></div></em></li>
<li><em>We stage this README.md file to git by using the same <strong>git add .</strong> and follow rest process as Demo 1 .</em></li>
<li><em>When we try to push this live to our GitHub account , we get a fatal error that this repository is not connected to any repository, i.e. git does not where to push this repository. For this we create an empty repository on the  Github and copy the SSH url and paste it to the command :<div><strong>git remote add origin ssh-url-of-remote-repo</strong></div> in the <strong>ssh-url-of-remote-repo</strong> pass the SSH url of the remote repository. Remote means not on this device but hosted somewhere else </em></li>
</ul>

