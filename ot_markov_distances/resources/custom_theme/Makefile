CLEANPURPLE_DIR=$(HOME)/programmation/web/cleanpurple_revealjs_theme

SASS_INCLUDES=-I $(CLEANPURPLE_DIR)/reveal.js/css/theme/ -I $(CLEANPURPLE_DIR)

all: dist/custom.css

dist/%.css: %.scss
	@mkdir -p $(@D)
	sass $(SASS_INCLUDES) $< $@
