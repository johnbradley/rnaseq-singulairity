Bootstrap: yum
OSVersion: 7
MirrorURL: http://mirror.centos.org/centos-%{OSVERSION}/%{OSVERSION}/os/$basearch/ 
Include: yum

%runscript
    echo "This is what happens when you run the container..."


%post
    echo "Hello from inside the container"
    yum -y install vim-minimal
