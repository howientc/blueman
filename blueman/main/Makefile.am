SUBDIRS = applet

bluemandir = $(pythondir)/blueman/main

blueman_PYTHON = \
	AppletService.py PPPConnection.py Config.py DhcpClient.py Device.py __init__.py Mechanism.py NetConf.py SpeedCalc.py DbusService.py PluginManager.py

if HAVE_PULSEAUDIO
blueman_PYTHON += PulseAudioUtils.py
endif


CLEANFILES =		\
	$(BUILT_SOURCES)
	
DISTCLEANFILES = \
	$(CLEANFILES) 

clean-local:
	rm -rf *.pyc *.pyo 

