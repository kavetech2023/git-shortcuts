<h1>Git Commands Made Easy. !</h1>
<table>
  <tr>
    <th>Code</th>
    <th>Description</th>
  </tr>
  <tr></tr>
    <td>git init</td>
    <td>Initializes a new Git repository in the current directory.</td>
  </tr>
   <tr>
    <td>git add <<filename>></td>
    <td>Adds a file to the staging area for the next commit</td>
  </tr>
       </tr>
   <tr>
    <td>git commit -m "<message>"</td>
    <td>Commits changes currently in the staging area with a message</td>
  </tr>
       <tr>
    <td>git status</td>
    <td>Shows the status of your working directory and staging area.</td>
  </tr>
           <tr>
    <td>git log</td>
    <td>Shows the commit history of your repository</td>
  </tr>
            <tr>
    <td>git clone <url></td>
    <td>Clones a repository from a remote URL.</td>
  </tr>
  </table>

  <h1>Branching and Merging:</h1>
  
<table>
  <tr>
    <th>Code</th>
    <th>Description:</th>
  </tr>
  <tr>
    <td>git branch</td>
    <td>Creates a new branch.</td>
  </tr>
   <tr>
    <td>git checkout <branch_name></td>
    <td>Switches to a different branch.</td>
  </tr>
       </tr>
   <tr>
    <td>git merge</td>
    <td>Merges changes from another branch into the current branch.</td>
  </tr>
       <tr>
    <td>git pull</td>
    <td>Fetches and merges changes from the remote repository into the current branch.</td>
  </tr>
           <tr>
    <td>git push</td>
    <td>Pushes your local commits to the remote repository.</td>
  </tr>
  </table>
    <h1>Undoing and Redoing:</h1>
  
<table>
  <tr>
    <th>Code</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>git reset HEAD <filename></td>
    <td>Creates a new branch.</td>
  </tr>
   <tr>
    <td>git checkout <branch_name></td>
    <td>Unstages a file from the staging area. (Unmodified working directory)</td>
  </tr>
       </tr>
   <tr>
    <td>git checkout <filename></td>
    <td>Discards changes made to a file in the working directory. (Unmodified staging area)</td>
  </tr>
       <tr>
    <td>git revert <commit_hash></td>
    <td>Creates a new commit that reverts the changes introduced by a specific commit.</td>
  </tr>
  </table>

  <h1>Stashing:</h1>
  
<table>
  <tr>
    <th>Code</th>
    <th>Description:</th>
  </tr>
  <tr>
    <td>git stash</td>
    <td>Creates a new branch.</td>
  </tr>
   <tr>
    <td>git stash pop</td>
    <td>Applies the most recent stash and discards it.</td>
  </tr>
       </tr>
   <tr>
    <td>git stash list</td>
    <td>Lists all available stashes</td>
  </tr>
  </table>

