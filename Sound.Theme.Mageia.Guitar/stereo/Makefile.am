NULL =
ussdir = /usr/share/sounds
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
	
	-if test -f $(ussdir)/KDE-Sys-Log-In-Long.ogg; then
	-mkdir $(datadir)/sounds/kde.previous
	
	-cp -ifH $(ussdir)/KDE*.ogg $(datadir)/sounds/kde.previous
	-rm	-f $(ussdir)/KDE*.ogg
	-fi
	-ln -s $(DESTDIR)$(sounddir)/desktop-login.ogg $(ussdir)/KDE-Sys-Log-In-Long.ogg			
	-ln -s $(DESTDIR)$(sounddir)/desktop-logout.ogg $(ussdir)/KDE-Sys-Log-Out-Long.ogg			
	-ln -s $(DESTDIR)$(sounddir)/service-login.ogg $(ussdir)/KDE-Sys-Log-In-Short.ogg			
	-ln -s $(DESTDIR)$(sounddir)/service-logout.ogg $(ussdir)/KDE-Sys-Log-Out-Short.ogg			
	-ln -s $(DESTDIR)$(sounddir)/window-question.ogg $(ussdir)/KDE-Sys-Question.ogg			
	-ln -s $(DESTDIR)$(sounddir)/window-attention.ogg $(ussdir)/KDE-Sys-Warning.ogg			
	-ln -s $(DESTDIR)$(sounddir)/trash-empty.ogg $(ussdir)/KDE-Sys-Trash-Emptied.ogg			
	-ln -s $(DESTDIR)$(sounddir)/bell.ogg $(ussdir)/KDE-Sys-Special.ogg					
	-ln -s $(DESTDIR)$(sounddir)/network-connectivity-established.ogg $(ussdir)/KDE-Sys-User-Auth.ogg	
	-ln -s $(DESTDIR)$(sounddir)/network-connectivity-lost.ogg $(ussdir)/KDE-Im-Connection-Lost.ogg	
	-ln -s $(DESTDIR)$(sounddir)/power-plug.ogg $(ussdir)/KDE-Sys-Im-Contact-In.ogg			
	-ln -s $(DESTDIR)$(sounddir)/power-unplug.ogg $(ussdir)/KDE-Contact-Out.ogg				
	-ln -s $(DESTDIR)$(sounddir)/suspend-error.ogg $(ussdir)/KDE-Sys-App-Error-Critical.ogg		
	-ln -s $(DESTDIR)$(sounddir)/dialog-warning.ogg $(ussdir)/KDE-Sys-App-Error-Serious-Very.ogg		#twink1	
	-ln -s $(DESTDIR)$(sounddir)/dialog-error.ogg $(ussdir)/KDE-Sys-App-Error.ogg			
	-ln -s $(DESTDIR)$(sounddir)/dialog-information.ogg $(ussdir)/KDE-Sys-App-Error-Serious.ogg		
	-ln -s $(DESTDIR)$(sounddir)/addon-1.ogg $(ussdir)/KDE-Sys-App-Message.ogg				
	-ln -s $(DESTDIR)$(sounddir)/addon-3.ogg $(ussdir)/KDE-Sys-App-Negative.ogg				
	-ln -s $(DESTDIR)$(sounddir)/audio-test-signal.ogg $(ussdir)/KDE-Sys-App-Positive.ogg		
	-ln -s $(DESTDIR)$(sounddir)/phone-outgoing-busy.ogg $(ussdir)/KDE-Sys-File-Open-Foes.ogg				#twink2 
	-ln -s $(DESTDIR)$(sounddir)/screen-capture.ogg $(ussdir)/KDE-Im-Message-In.ogg			
	-ln -s $(DESTDIR)$(sounddir)/screen-capture1.ogg $(ussdir)/KDE-Im-Message-Out.ogg
	-ln -s $(DESTDIR)$(sounddir)/message.ogg $(ussdir)/KDE-Im-New-Mail.ogg
	-ln -s $(DESTDIR)$(sounddir)/screen-capture.ogg $(ussdir)/KDE-Im-Irc-Event.ogg			
	-ln -s $(DESTDIR)$(sounddir)/message-new-instant.ogg $(ussdir)/KDE-Im-Nudge.ogg			
	-ln -s $(DESTDIR)$(sounddir)/phone-outgoing-calling.ogg $(ussdir)/KDE-Im-Phone-Ring.ogg			
	-ln -s $(DESTDIR)$(sounddir)/message.ogg $(ussdir)/KDE-Im-Sms.ogg					
	-ln -s $(DESTDIR)$(sounddir)/system-ready.ogg $(ussdir)/KDE-Im-Network-Problems.ogg			
	-ln -s $(DESTDIR)$(sounddir)/dialog-warning.ogg $(ussdir)/KDE-Im-Cant-Connect.ogg				#twink 1
	-ln -s $(DESTDIR)$(sounddir)/phone-outgoing-busy.ogg $(ussdir)/KDE-Im-Error-On-Connection.ogg			#twink 2
	-ln -s $(DESTDIR)$(sounddir)/camera-shutter.ogg $(ussdir)/KDE-Im-Low-Priority-Message.ogg		
	-ln -s $(DESTDIR)$(sounddir)/audio-volume-change.ogg $(ussdir)/KDE-Im-Highlight-Msg.ogg		
	-ln -s $(DESTDIR)$(sounddir)/addon-4.ogg $(ussdir)/KDE-Im-Internal-Error.ogg				
	-ln -s $(DESTDIR)$(sounddir)/device-removed.ogg $(ussdir)/KDE-K3B-Finish-Error.ogg			
	-ln -s $(DESTDIR)$(sounddir)/device-added.ogg $(ussdir)/KDE-K3B-Finish-Success.ogg			
	-ln -s $(DESTDIR)$(sounddir)/complete.ogg $(ussdir)/KDE-K3B-Insert-Medium.ogg			
	-ln -s $(DESTDIR)$(sounddir)/addon-2.ogg $(ussdir)/KDE-Window-Close.ogg				
	-ln -s $(DESTDIR)$(sounddir)/addon-2.ogg $(ussdir)/KDE-Window-Close.ogg				
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
