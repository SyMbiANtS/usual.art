NULL =

sounddir = $(datadir)/sounds/mageia/stereo

sound_DATA =                            \
	alarm-clock-elapsed.ogg	        \
	audio-channel-front-center.ogg	\
	audio-channel-front-left.ogg	\
	audio-channel-front-right.ogg	\
	audio-channel-rear-center.ogg	\
	audio-channel-rear-left.ogg	\
	audio-channel-rear-right.ogg	\
	audio-channel-side-left.ogg	\
	audio-channel-side-right.ogg	\
	audio-test-signal.ogg		\
	audio-volume-change.ogg		\
	bell.ogg			\
	camera-shutter.ogg		\
	complete.ogg			\
	desktop-login.ogg		\
	desktop-logout.ogg		\
	device-added.ogg		\
	device-removed.ogg		\
	dialog-information.ogg		\
	dialog-warning.ogg		\
	dialog-error.ogg		\
	message.ogg			\
	message-new-instant.ogg		\
	network-connectivity-established.ogg	\
	network-connectivity-lost.ogg		\
	phone-incoming-call.ogg		\
	phone-outgoing-busy.ogg		\
	phone-outgoing-calling.ogg      \
	power-plug.ogg			\
	power-unplug.ogg		\
	screen-capture.ogg		\
	service-login.ogg		\
	service-logout.ogg		\
	suspend-error.ogg		\
	system-ready.ogg		\
	screen-capture1.ogg		\
	trash-empty.ogg			\
	window-attention.ogg		\
	window-question.ogg		\
	addon-1.ogg			\
	addon-2.ogg			\
	addon-3.ogg			\
	addon-4.ogg			\
	$(NULL)
install-data-hook:
	-if test -f $(datadir)/sounds/KDE-Sys-Log-In-Long.ogg; then
	-mkdir $(datadir)/sounds/kde.previous
	-cp -ifH $(datadir)/sounds/KDE*.ogg $(datadir)/sounds/kde.previous
	-rm	-f $(datadir)/sounds/KDE*.ogg
	-fi
	-ln -s $(DESTDIR)$(sounddir)/desktop-login.ogg $(datadir)/sounds/KDE-Sys-Log-In-Long.ogg			
	-ln -s $(DESTDIR)$(sounddir)/desktop-logout.ogg $(datadir)/sounds/KDE-Sys-Log-Out-Long.ogg			
	-ln -s $(DESTDIR)$(sounddir)/service-login.ogg $(datadir)/sounds/KDE-Sys-Log-In-Short.ogg			
	-ln -s $(DESTDIR)$(sounddir)/service-logout.ogg $(datadir)/sounds/KDE-Sys-Log-Out-Short.ogg			
	-ln -s $(DESTDIR)$(sounddir)/window-question.ogg $(datadir)/sounds/KDE-Sys-Question.ogg			
	-ln -s $(DESTDIR)$(sounddir)/window-attention.ogg $(datadir)/sounds/KDE-Sys-Warning.ogg			
	-ln -s $(DESTDIR)$(sounddir)/trash-empty.ogg $(datadir)/sounds/KDE-Sys-Trash-Emptied.ogg			
	-ln -s $(DESTDIR)$(sounddir)/bell.ogg $(datadir)/sounds/KDE-Sys-Special.ogg					
	-ln -s $(DESTDIR)$(sounddir)/network-connectivity-established.ogg $(datadir)/sounds/KDE-Sys-User-Auth.ogg	
	-ln -s $(DESTDIR)$(sounddir)/network-connectivity-lost.ogg $(datadir)/sounds/KDE-Im-Connection-Lost.ogg	
	-ln -s $(DESTDIR)$(sounddir)/power-plug.ogg $(datadir)/sounds/KDE-Sys-Im-Contact-In.ogg			
	-ln -s $(DESTDIR)$(sounddir)/power-unplug.ogg $(datadir)/sounds/KDE-Contact-Out.ogg				
	-ln -s $(DESTDIR)$(sounddir)/suspend-error.ogg $(datadir)/sounds/KDE-Sys-App-Error-Critical.ogg		
	-ln -s $(DESTDIR)$(sounddir)/dialog-warning.ogg $(datadir)/sounds/KDE-Sys-App-Error-Serious-Very.ogg		#twink1	
	-ln -s $(DESTDIR)$(sounddir)/dialog-error.ogg $(datadir)/sounds/KDE-Sys-App-Error.ogg			
	-ln -s $(DESTDIR)$(sounddir)/dialog-information.ogg $(datadir)/sounds/KDE-Sys-App-Error-Serious.ogg		
	-ln -s $(DESTDIR)$(sounddir)/addon-1.ogg $(datadir)/sounds/KDE-Sys-App-Message.ogg				
	-ln -s $(DESTDIR)$(sounddir)/addon-3.ogg $(datadir)/sounds/KDE-Sys-App-Negative.ogg				
	-ln -s $(DESTDIR)$(sounddir)/audio-test-signal.ogg $(datadir)/sounds/KDE-Sys-App-Positive.ogg		
	-ln -s $(DESTDIR)$(sounddir)/phone-outgoing-busy.ogg $(datadir)/sounds/KDE-Sys-File-Open-Foes.ogg				#twink2 
	-ln -s $(DESTDIR)$(sounddir)/screen-capture.ogg $(datadir)/sounds/KDE-Im-Message-In.ogg			
	-ln -s $(DESTDIR)$(sounddir)/screen-capture1.ogg $(datadir)/sounds/KDE-Im-Message-Out.ogg			
	-ln -s $(DESTDIR)$(sounddir)/screen-capture.ogg $(datadir)/sounds/KDE-Im-Irc-Event.ogg			
	-ln -s $(DESTDIR)$(sounddir)/message-new-instant.ogg $(datadir)/sounds/KDE-Im-Nudge.ogg			
	-ln -s $(DESTDIR)$(sounddir)/phone-outgoing-calling.ogg $(datadir)/sounds/KDE-Phone-Ring.ogg			
	-ln -s $(DESTDIR)$(sounddir)/message.ogg $(datadir)/sounds/KDE-Im-Sms.ogg					
	-ln -s $(DESTDIR)$(sounddir)/system-ready.ogg $(datadir)/sounds/KDE-Im-Network-Problems.ogg			
	-ln -s $(DESTDIR)$(sounddir)/dialog-warning.ogg $(datadir)/sounds/KDE-Im-Cant-Connect.ogg				#twink 1
	-ln -s $(DESTDIR)$(sounddir)/phone-outgoing-busy.ogg $(datadir)/sounds/KDE-Im-Error-On-Connection.ogg			#twink 2
	-ln -s $(DESTDIR)$(sounddir)/camera-shutter.ogg $(datadir)/sounds/KDE-Im-Low-Priority-Message.ogg		
	-ln -s $(DESTDIR)$(sounddir)/audio-volume-change.ogg $(datadir)/sounds/KDE-Im-Highlight-Msg.ogg		
	-ln -s $(DESTDIR)$(sounddir)/addon-4.ogg $(datadir)/sounds/KDE-Im-Internal-Error.ogg				
	-ln -s $(DESTDIR)$(sounddir)/device-removed.ogg $(datadir)/sounds/KDE-K3B-Finish-Error.ogg			
	-ln -s $(DESTDIR)$(sounddir)/device-added.ogg $(datadir)/sounds/KDE-K3B-Finish-Success.ogg			
	-ln -s $(DESTDIR)$(sounddir)/complete.ogg $(datadir)/sounds/KDE-K3B-Insert-Medium.ogg			
	-ln -s $(DESTDIR)$(sounddir)/addon-2.ogg $(datadir)/sounds/KDE-Window-Close.ogg				
	-ln -s $(DESTDIR)$(sounddir)/addon-2.ogg $(datadir)/sounds/KDE-Window-Close.ogg				
#	-rm -f $(DESTDIR)$(sounddir)/power-plug.ogg
#	$(LN_S) device-added.ogg $(DESTDIR)$(sounddir)/power-plug.ogg
#	-rm -f $(DESTDIR)$(sounddir)/power-unplug.ogg
#	$(LN_S) device-removed.ogg $(DESTDIR)$(sounddir)/power-unplug.ogg
#	-rm -f $(DESTDIR)$(sounddir)/network-connectivity-established.ogg
#	$(LN_S) device-added.ogg $(DESTDIR)$(sounddir)/network-connectivity-established.ogg
#	-rm -f $(DESTDIR)$(sounddir)/network-connectivity-lost.ogg
#	$(LN_S) device-removed.ogg $(DESTDIR)$(sounddir)/network-connectivity-lost.ogg
#	-rm -f $(DESTDIR)$(sounddir)/screen-capture.ogg
#	$(LN_S) camera-shutter.ogg $(DESTDIR)$(sounddir)/screen-capture.ogg
#	-rm -f $(DESTDIR)$(sounddir)/dialog-error.ogg
#	$(LN_S) dialog-warning.ogg $(DESTDIR)$(sounddir)/dialog-error.ogg
#	-rm -f $(DESTDIR)$(sounddir)/window-attention.ogg
#	$(LN_S) dialog-warning.ogg $(DESTDIR)$(sounddir)/window-attention.ogg
#	-rm -f $(DESTDIR)$(sounddir)/window-question.ogg
#	$(LN_S) dialog-warning.ogg $(DESTDIR)$(sounddir)/window-question.ogg

EXTRA_DIST =            \
	$(sound_DATA)	\
	$(NULL)

DISTCLEANFILES = \
	$(NULL)

MAINTAINERCLEANFILES =		\
	*~			\
	Makefile.in		\
	$(NULL)
