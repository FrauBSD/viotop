############################################################ IDENT(1)
#
# $Title: Makefile for installing viotop $
# $Copyright: 2020 Devin Teske. All rights reserved. $
# $FrauBSD: viotop/GNUmakefile 2020-04-17 15:35:11 -0700 freebsdfrau $
#
############################################################ CONFIGURATION

DESTDIR=	
BINDIR=		$(DESTDIR)/usr/bin

############################################################ PATHS

CP_F=		cp -f
MKDIR_P=	mkdir -p
RM_F=		rm -f

############################################################ OBJECTS

PROG=		viotop

############################################################ TARGETS

all:
	@printf "Options:\n"
	@printf "\tmake install\tInstall $(PROG)\n"
	@printf "\tmake uninstall\tUninstall $(PROG)\n"

install:
	$(MKDIR_P) $(BINDIR)
	$(CP_F) $(PROG) $(BINDIR)/

uninstall:
	$(RM_F) $(BINDIR)/$(PROG)

################################################################################
# END
################################################################################
