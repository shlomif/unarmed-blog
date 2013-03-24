all:

upload:
	rsync -a -v --progress *.xhtml "$${__HOMEPAGE_REMOTE_PATH}"/temp-xml-grammar-screenplay/

firefox:
	firefox *.xhtml
