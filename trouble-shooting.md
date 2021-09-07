 Networking Error

    W: Failed to fetch http://in.archive.ubuntu.com/ubuntu/dists/focal/InRelease  Temporary failure resolving 'in.archive.ubuntu.com'
    W: Failed to fetch http://in.archive.ubuntu.com/ubuntu/dists/focal-updates/InRelease  Temporary failure resolving 'in.archive.ubuntu.com'
    W: Failed to fetch http://in.archive.ubuntu.com/ubuntu/dists/focal-backports/InRelease  Temporary failure resolving 'in.archive.ubuntu.com'
    W: Failed to fetch http://security.ubuntu.com/ubuntu/dists/focal-security/InRelease  Temporary failure resolving 'security.ubuntu.com'
    W: Some index files failed to download. They have been ignored, or old ones used instead.

Resolution:

    Network connection or internet coneection issue. Please make sure everything fine 
    
    
    sudo privileages error
    
    zerolinuxes@xps-13-9305:~$ apt update
Reading package lists... Done
E: Could not open lock file /var/lib/apt/lists/lock - open (13: Permission denied)
E: Unable to lock directory /var/lib/apt/lists/
W: Problem unlinking the file /var/cache/apt/pkgcache.bin - RemoveCaches (13: Permission denied)
W: Problem unlinking the file /var/cache/apt/srcpkgcache.bin - RemoveCaches (13: Permission denied)

resolution:
      check whether u gave sudo privileage or not
    
