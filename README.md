Contiki SmartRF Settings for 625bps LRM prop-mode

Didn't work so far with contikimac. Works with nullrdc.

Contikimac parameters to look into
#define CONTIKIMAC_CONF_AFTER_ACK_DETECTED_WAIT_TIME (RTIMER_SECOND / 920)
#define CONTIKIMAC_CONF_INTER_PACKET_INTERVAL        (RTIMER_SECOND / 220)   



