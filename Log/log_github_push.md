# log, github push

```
chino@chino-ThinkPad-E590:~$ cd JetsonWorks/test-unity/
chino@chino-ThinkPad-E590:~/JetsonWorks/test-unity$ ls
LICENSE  Log  README.md  test-2022p2p4f1
chino@chino-ThinkPad-E590:~/JetsonWorks/test-unity$ cd ..
chino@chino-ThinkPad-E590:~/JetsonWorks$ mv test-unity/ test-unity-1/
chino@chino-ThinkPad-E590:~/JetsonWorks$ git clone git@github.com:takurx/test-unity.git
Cloning into 'test-unity'...
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (4/4), done.
Receiving objects: 100% (5/5), done.
remote: Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
chino@chino-ThinkPad-E590:~/JetsonWorks$ curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash
[sudo] password for chino: 
Detected operating system as Ubuntu/jammy.
Checking for curl...
Detected curl...
Checking for gpg...
Detected gpg...
Detected apt version as 2.4.8
Running apt-get update... done.
Installing apt-transport-https... done.
Installing /etc/apt/sources.list.d/github_git-lfs.list...done.
Importing packagecloud gpg key... Packagecloud gpg key imported to /etc/apt/keyrings/github_git-lfs-archive-keyring.gpg
done.
Running apt-get update... done.

The repository is setup! You can now install packages.
chino@chino-ThinkPad-E590:~/JetsonWorks$ cd test-unity
chino@chino-ThinkPad-E590:~/JetsonWorks/test-unity$ curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash
Detected operating system as Ubuntu/jammy.
Checking for curl...
Detected curl...
Checking for gpg...
Detected gpg...
Detected apt version as 2.4.8
Running apt-get update... done.
Installing apt-transport-https... done.
Installing /etc/apt/sources.list.d/github_git-lfs.list...done.
Importing packagecloud gpg key... Packagecloud gpg key imported to /etc/apt/keyrings/github_git-lfs-archive-keyring.gpg
done.
Running apt-get update... done.

The repository is setup! You can now install packages.
chino@chino-ThinkPad-E590:~/JetsonWorks/test-unity$ git lfs install
git: 'lfs' is not a git command. See 'git --help'.

The most similar command is
	log
chino@chino-ThinkPad-E590:~/JetsonWorks/test-unity$ git lfs install
Updated Git hooks.
Git LFS initialized.
chino@chino-ThinkPad-E590:~/JetsonWorks/test-unity$ git push
Enumerating objects: 23336, done.
Counting objects: 100% (23336/23336), done.
Delta compression using up to 4 threads
Compressing objects: 100% (23296/23296), done.
Writing objects: 100% (23335/23335), 528.79 MiB | 3.04 MiB/s, done.
Total 23335 (delta 14236), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (14236/14236), completed with 1 local object.
remote: warning: File test-2022p2p4f1/Library/PackageCache/com.unity.burst@1.8.2/.Runtime/burst-llvm-14.dll is 50.37 MB; this is larger than GitHub's recommended maximum file size of 50.00 MB
remote: warning: File test-2022p2p4f1/Library/PackageCache/com.unity.burst@1.8.2/.Runtime/hostmac/dsymutil is 83.51 MB; this is larger than GitHub's recommended maximum file size of 50.00 MB
remote: warning: File test-2022p2p4f1/Library/PackageCache/com.unity.burst@1.8.2/.Runtime/libburst-llvm-10.dylib is 74.61 MB; this is larger than GitHub's recommended maximum file size of 50.00 MB
remote: warning: File test-2022p2p4f1/Library/PackageCache/com.unity.burst@1.8.2/.Runtime/libburst-llvm-14.so is 63.26 MB; this is larger than GitHub's recommended maximum file size of 50.00 MB
remote: error: Trace: b7b12029011eb13b71ee4e61af4fcb61f0b86bd79778cde634888a74cf46d772
remote: error: See http://git.io/iEPt8g for more information.
remote: error: File test-2022p2p4f1/Library/PackageCache/com.unity.burst@1.8.2/.Runtime/libburst-llvm-14.dylib is 116.29 MB; this exceeds GitHub's file size limit of 100.00 MB
remote: error: GH001: Large files detected. You may want to try Git Large File Storage - https://git-lfs.github.com.
To github.com:takurx/test-unity.git
 ! [remote rejected] main -> main (pre-receive hook declined)
error: failed to push some refs to 'github.com:takurx/test-unity.git'
chino@chino-ThinkPad-E590:~/JetsonWorks/test-unity$ cd ..
chino@chino-ThinkPad-E590:~/JetsonWorks$ mv test-unity/ test-unity-2/
chino@chino-ThinkPad-E590:~/JetsonWorks$ 
```



# Log2

```
chino@chino-ThinkPad-E590:~/Downloads/git-lfs-3.3.0$ ./install.sh 
install: cannot create regular file '/usr/local/bin/git-lfs': Permission denied
chino@chino-ThinkPad-E590:~/Downloads/git-lfs-3.3.0$ sudo ./install.sh 
[sudo] password for chino: 
Git LFS initialized.
```