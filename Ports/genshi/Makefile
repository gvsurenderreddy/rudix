include ../../Library/Python.mk

Title=		Genshi (Python Module)
Name=		genshi
Version=	0.7
Revision=	0
Site=		http://genshi.edgewall.org
Source=		http://ftp.edgewall.com/pub/genshi//Genshi-$(Version).tar.gz
License=	BSD

ReadMeFile=	$(SourceDir)/README.txt
LicenseFile=	$(SourceDir)/COPYING

define test_inner_hook
$(Python) -c 'import genshi'
endef
