# Samosir

Samosir is the library used to develop plugin modules for the Toba personal information retrieval application. It lets developers easily write modules that add functionality from within Toba and integrate with the internal database and search engine.

SCR# 963

https://sourceforge.net/projects/samosir/

CVS is an old system for managing code. In order to access a CVS repository, you must install a CVS client.
The CVS data can be accessed as follows. You can run a per-module CVS checkout via pserver protocol:

cvs -z3 -d:pserver:anonymous@a.cvs.sourceforge.net:/cvsroot/samosir co -P Samosir

You can view a list of files or copy all the CVS repository data via rsync (the 1st command lists the files, the 2nd copies):

rsync -a a.cvs.sourceforge.net::cvsroot/samosir/
rsync -ai a.cvs.sourceforge.net::cvsroot/samosir/ /my/local/dest/dir/
