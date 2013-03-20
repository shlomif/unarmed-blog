all:

upload:
	rsync -a -v --progress *.xhtml "$${__HOMEPAGE_REMOTE_PATH}"/temp-sherlock-holmes-awk/

firefox:
	firefox *.xhtml
