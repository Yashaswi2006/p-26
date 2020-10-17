# #                             Git & Github

##                       configuring username & email

Ashish Patel@DESKTOP-1DTNCLT MINGW64 ~
$ git config --global user.name "Yashaswi singh"

Ashish Patel@DESKTOP-1DTNCLT MINGW64 ~
$ git config --global user.email "iamyash2006@gmail.com"

## pwd

  pwd fullform - print working directory

$ pwd
/c/Users/Ashish Patel

## ls

listing all the directories

$ ls
'3D Objects'/         IntelGraphicsProfiles/   ntuser.dat.LOG2                                                                               'Saved Games'/
 AppData/             Links/                   NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf                                        ScStore/
'Application Data'@  'Local Settings'@         NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms   Searches/
 Contacts/            MicrosoftEdgeBackups/    NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms   SendTo@
 Cookies@             Music/                   ntuser.ini                                                                                    'Start Menu'@
 Desktop/            'My Documents'@           OneDrive/                                                                                      Templates@
 Documents/           NetHood@                 Pictures/                                                                                      Videos/
 Downloads/           NTUSER.DAT               PrintHood@
 Favorites/           ntuser.dat.LOG1          Recent@

## cd

cd stands for change directory

$ cd Desktop/

## mkdir

making a new directory

$ mkdir yash

## git status

$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   sketch.js

no changes added to commit (use "git add" and/or "git commit -a")

## adding a folder to git

$ git add sketch.js

## commit a message

$ git commit -m "adding a platform"
[master 5f2be91] adding a platform
 1 file changed, 5 insertions(+), 1 deletion(-)

