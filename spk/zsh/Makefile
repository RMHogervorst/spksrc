# Allow overriding the name, used by spk/zsh-static.
SPK_NAME ?= zsh
SPK_VERS = 5.8.1
SPK_CONFLICT ?= zsh-static
# Allow overriding the revision, used by spk/zsh-static.
# If you rev here, please also rev spk/zsh-static.
SPK_REV ?= 12
SPK_ICON = ../zsh/src/zsh.png

DEPENDS = cross/zsh

MAINTAINER = SynoCommunity
DESCRIPTION = Zsh is a shell designed for interactive use, although it is also a powerful scripting language.
DESCRIPTION_FRE = Zsh est un shell conçu pour un usage intéractif, mais il est aussi un puissant langage de script.
DISPLAY_NAME = Z shell
STARTABLE = no
CHANGELOG = "Update to 5.8.1"

HOMEPAGE = https://www.zsh.org
LICENSE = Custom

SPK_COMMANDS = bin/zsh

include ../../mk/spksrc.spk.mk
