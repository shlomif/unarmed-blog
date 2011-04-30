all:

upload:
	rsync -a -v --progress *.xhtml "$${HOMEPAGE_SSH_PATH}"/We-are-Qs/

firefox:
	firefox *.xhtml
