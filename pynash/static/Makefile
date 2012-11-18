BOOTSTRAP_LESS = less/site.less
CSS_OUTPUT_FILENAME = css/site.css
LESS_COMPRESSOR ?= `which lessc`

#
# BUILD SITE MEDIA
# lessc & uglifyjs are required
#

build:
	mkdir -p css
	lessc --yui-compress ${BOOTSTRAP_LESS} > ${CSS_OUTPUT_FILENAME}
