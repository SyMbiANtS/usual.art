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
	trash-empty.ogg			\
	window-attention.ogg		\
	window-question.ogg		\
	addon-1.ogg			\
	addon-2.ogg			\
	addon-3.ogg			\
	addon-4.ogg			\
	$(NULL)
	
#install-KDE:
    @if test -f $(datadir)/sounds/KDE-Sys-Log-In-Long.ogg 						\
    then 												\
	echo "Found some KDE sound.files - gonna copy into kde.previous directory" 		\
	mkdir $(DESTDIR)/kde.previous 								\
	cp -ifH $(DESTDIR)/KDE*.ogg $(datadir)/sounds/kde.previous 				\
	rm -f KDE*.ogg 										\
	$(LN_S) desktop-login.ogg $(datadir)/sounds/KDE-Sys-Log-In-Long.ogg			\
	$(LN_S) desktop-logout.ogg $(datadir)/sounds/KDE-Sys-Log-Out-Long.ogg			\
	$(LN_S) service-login.ogg $(datadir)/sounds/KDE-Sys-Log-In-Short.ogg			\
	$(LN_S) service-logout.ogg $(datadir)/sounds/KDE-Sys-Log-Out-Short.ogg			\
	$(LN_S) window-question.ogg $(datadir)/sounds/KDE-Sys-Question.ogg			\
	$(LN_S) window-attention.ogg $(datadir)/sounds/KDE-Sys-Warning.ogg			\
	$(LN_S) trash-empty.ogg $(datadir)/sounds/KDE-Sys-Trash-Emptied.ogg			\
	$(LN_S) bell.ogg $(datadir)/sounds/KDE-Sys-Special.ogg					\						
	$(LN_S) network-connectivity-established.ogg $(datadir)/sounds/KDE-Sys-User-Auth.ogg	\
	$(LN_S) network-connectivity-lost.ogg $(datadir)/sounds/KDE-Im-Connection-Lost.ogg	\
	$(LN_S) power-plug.ogg $(datadir)/sounds/KDE-Sys-Im-Contact-In.ogg			\
	$(LN_S) power-unplug.ogg $(datadir)/sounds/KDE-Contact-Out.ogg				\
	$(LN_S) suspend-error.ogg $(datadir)/sounds/KDE-Sys-App-Error-Critical.ogg		\
	$(LN_S) dialog-warning.ogg $(datadir)/sounds/KDE-Sys-App-Error-Serious-Very.ogg			#twink1	\
	$(LN_S) dialog-error.ogg $(datadir)/sounds/KDE-Sys-App-Error.ogg			\
	$(LN_S) dialog-information.ogg $(datadir)/sounds/KDE-Sys-App-Error-Serious.ogg		\
	$(LN_S) addon-1.ogg $(datadir)/sounds/KDE-Sys-App-Message.ogg				\
	$(LN_S) addon-3.ogg $(datadir)/sounds/KDE-Sys-App-Negative.ogg				\
	$(LN_S) audio-test-signal.ogg $(datadir)/sounds/KDE-Sys-App-Positive.ogg		\
												\
	$(LN_S) phone-outgoing-busy.ogg $(datadir)/sounds/KDE-Sys-File-Open-Foes.ogg				#twink2 \
	$(LN_S) screen-capture.ogg $(datadir)/sounds/KDE-Im-Message-In.ogg			\
	$(LN_S) screen-capture1.ogg $(datadir)/sounds/KDE-Im-Message-Out.ogg			\
	$(LN_S) screen-capture.ogg $(datadir)/sounds/KDE-Im-Irc-Event.ogg			\
	$(LN_S) message-new-instant.ogg $(datadir)/sounds/KDE-Im-Nudge.ogg			\
	$(LN_S) phone-outgoing-calling.ogg $(datadir)/sounds/KDE-Phone-Ring.ogg			\
	$(LN_S) message.ogg $(datadir)/sounds/KDE-Im-Sms.ogg					\
	$(LN_S) system-ready.ogg $(datadir)/sounds/KDE-Im-Network-Problems.ogg			\
	$(LN_S) dialog-warning.ogg $(datadir)/sounds/KDE-Im-Cant-Connect.ogg				#twink 1\
	$(LN_S) phone-outgoing-busy.ogg $(datadir)/sounds/KDE-Im-Error-On-Connection.ogg			#twink 2\
	$(LN_S) camera-shutter.ogg $(datadir)/sounds/KDE-Im-Low-Priority-Message.ogg		\
	$(LN_S) audio-volume-change.ogg $(datadir)/sounds/KDE-Im-Highlight-Msg.ogg		\
	$(LN_S) addon-4.ogg $(datadir)/sounds/KDE-Im-Internal-Error.ogg				\
	$(LN_S) device-removed.ogg $(datadir)/sounds/KDE-K3B-Finish-Error.ogg			\
	$(LN_S) device-added.ogg $(datadir)/sounds/KDE-K3B-Finish-Success.ogg			\
	$(LN_S) complete.ogg $(datadir)/sounds/KDE-K3B-Insert-Medium.ogg			\
	$(LN_S) addon-2.ogg $(datadir)/sounds/KDE-Window-Close.ogg				\
	$(LN_S) addon-2.ogg $(datadir)/sounds/KDE-Window-Close.ogg				\
    else												\
	echo "didn't find any KDE file in folder, well maybe the wrong dir"			\
    fi												
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
