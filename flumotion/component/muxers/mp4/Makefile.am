include $(top_srcdir)/common/python.mk

component_PYTHON = __init__.py mp4.py wizard_gtk.py
componentdir = $(libdir)/flumotion/python/flumotion/component/muxers/mp4
component_DATA = \
	mp4muxer.xml

clean-local:
	rm -rf *.pyc *.pyo

EXTRA_DIST = $(component_DATA)
