- With the following command you can obtain a list of installed packages, classified by priority:

  dpkg-query -Wf '${Package;-40}${Priority}\n' | sort -b -k2,2 -k1,1
