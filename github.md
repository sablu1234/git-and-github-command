terminal jodi clear kora or kono text lekha na jai tobe => ctrl+shift+~


1.gir version=> git --version <br>
2.all files => ls <br>
3.git terminal clear=> clear <br>
4.git present directory=>pwd <br>
5.user name set=> git config --global user.name "sablu1234" <br>
6.user email setup in terminal => git config --global user.email "mdsablu0000000@gmail.com" <br>
7. amra ki ki config koresi ta dekte=> git config --list <br>


------------------------------------------------------------------------------------------------------------
============next under vs code i use git command================ <br>
----------------------clone command ata remote jekono file ke local a ante use hoi-------------------<br>
***jodi git a kono kisu lekha na ja tobe(q likehe enter press)=> q   <br>

1.ami amr remote repository amar local vs code a ante=>git clone https://github.com/sablu1234/apnacollege-demo.git <br>
2.amra jodi kono folder ar vatore jete chai vs terminal teke=>cd apnacollege-demo <br>
3.directory theke ber hote => cd .. <br>


-------------------------------------------status command display the status of command----------------- <br>
1.gir hub status dekte=> git status <br>

==============vs code a kisu modify korle 2 step korte hoi data github a dite===== <br>
1.add and 2.commit <br>

******add******** <br>
amra jodi new file add korte chai <br>
1.git add korte add and file ar name(new file)=> git add index.html <br>
2. amra jodi ager remote file ar modhe change korte chai same git add and file name(Old file change)=>git add README.md <br>
3. amra jodi all change add korte chai=>git add . <br>

 ******commit************** <br>
1. amader changes gulo commit korte comit and commit name(register in local)=> git commit -m "A new paragraph add" <br>


======================================================= <br>
------------------------amra jodi local commit gulo github a dite chai----------------- <br>
1. local to hithub upload the chnges(all changes)=> git push origin main <br>



<br><br><br><br>

------------------------------------------------------------------------------------------------------------------ <br>
=============== local to remote git mange=================  <br>
================init=========================<br>
1.local repo create by command=> mkdir LocalRepo <br>
2.local repo theke git repo banate=> git init <br>
3.local repo set with new github repo link=> git remote add origin https://github.com/sablu1234/localrepo.git <br>
4. local repo karo sathe set thakle tar status dekte=> git remote -v <br>
5. git branch check korte=> git branch <br>
6. git branch name change korte chaile=> git branch -M main <br>
7. amra jodi git push korar jonno short form use korte chai tobe(next all update main a jabe) => git push -u origin main <br>
8.  git push -u babohar korle akhon push korte purota lekte hobe na=> git push <br>


---------------------------------------------------------------------------------------------------------------------- <br>
==========================git branch======================== <br>
1.new branch korte chaile checout -b and new branch name=> git checkout -b feature1 <br>
2.amra jodi ak branch theke onno branch a jete chai(checkout and jetate jabo sei baranch name)=> git checkout main <br>
3.amra jodi kono branch delete korte chai(je branch ar vetore thakbo oi branch delete kora jai na)=> git branch -d feature2 <br>
4.amra jodi spacific branch a push korte chai=> git push origin feature1
<br><br>
-------------------------------------------------------------------------------------------------------------------------- <br>
=======marging code(main and feature code ak korte)=========== <br>
************marge  korar 2 ta way ase============ <br>
++++++++++++ Frist way+++++++++++++++ <br>
1.amra jodi feature branch ke main branch ar sathe compare korte chai=> git diff main <br>
2.amra jodi je branch a asi atar sathe main branch ar code aksathe korte chai=> git merge main <br>
<br><br>
++++++++++++Second way+++++++++++++++++ <br>
*ai khane amra github site theke merge korte pari <br>
*amra pr(pull request) ar <br>
==============Pull Request==================== <br><br>

------------------------------------------------------------------------------------------------------------------<br>
=========pull command(remote changes local ante hole)=========== <br>
1.amra jodi remote github ar changes local a ante chai=> git pull origin main <br>
<br><br>
========================resolving merge conflig=============== <br>
<br>
======================================================== <br>
-------------------------------undoing changes--------------------------------------------------------- <br>
1.amra jodi kono nirdisto file vule add kore feli tobe reset korte( git reset nirdisto file name)=> git reset index.html <br>
2. amra jodi sob file akste reset korte chai=> git reset <br>
=============commit kora file jodi unchange korte chai=========== <br>
1.amra jodi last commit kora file ke bad diye old commit rakte chai(head 1 commit back a jai)=>git reset HEAD~1 <br>
 2.amra all commit dekte chaile=>git reset HEAD~1 <br>
3. amra jodi nirdisto head ba commit a jete chai(git reset sathe je commit a jabo ter head code)=> git reset 0528c21052ac8efa9c062b96c51dbc73623ffc07 <br>
4. amra jodi oi nirdisto commita jayar pasapasi or pore joto sob changes ase sob remove korte chai=>git res <br>
--------------------------------------------------------------------------------------------------------------- <br><br><br>
==================Fork==============================<br>
amra jodi karo repository copp korte chai tebe fork use kori 

