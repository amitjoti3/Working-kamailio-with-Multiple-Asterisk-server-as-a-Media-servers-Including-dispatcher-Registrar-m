# kamailio
Working kamailio with Multiple Asterisk server as a Media servers Including dispatcher &amp; Registrar module

This is a example configuration script of kamailio for load balance of multiple asterisk servers.

Working example of kamailio with load balancing July 2023.

Thanks team to reach kamailio support.


#################################################################################################
In asterisk 1 entriy need to enable for reail time sync with kamailio.
 /etc/asterisk/sip.con
uncomment the below line.
rtcachefriends=yes             ; Cache realtime friends by adding them to the internal list
                                ; just like friends added from the config file only on a
                                ; as-needed basis? (yes|no)


change the below line or name on 2nd media and 3rd media server names.
realm=asterisk22.localdomain             ; Realm for digest authentication
##################################################################################################
