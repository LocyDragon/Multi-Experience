# Multi-Experience
Let your experience multiable.
Command:
/multiexp Show Plugin Info
/multiexp enable [multiple] [minute] Enable Multi Experience
Permissions:
multiexp.admin Use /multiexp command
Default op
Configuration:
`
configuration:
#Enable auto broadcast (Not avaliable,have bug)
 auto-broadcast-enabled: true
#Auto broadcast intervat time (minute)
 broadcast-interval-time: 1
language:
#Language
 msg-signal-1: "\u00a7aSet "
 msg-signal-2: " times experience for "
 msg-signal-3: " minute(s) successfully!"
 msg-getexp-1: "\u00a7a"
 msg-getexp-2: " times experience activities is holding, You have got "
 msg-getexp-3: " experience(s)!"
 msg-expired: "\u00a74Multi experience activity has expired!"
 msg-holding-1: "\u00a7a"
 msg-holding-2: " times experience activities is holding, Duration time "
 msg-holding-3: " minute(s)!"
 msg-broadcast-1: "\u00a7aNow "
 msg-broadcast-2: " times experience activities has opened, Duration of "
 msg-broadcast-3: " minute(s)!"
 usage: "\u00a7eUsage: /multiexp enable [multiple] [minute]"
multiexp:
#MultiExp config
 enabled: false
#Enable multi experience
 multiple: 2
#Experience multiple
 tick-time: 0
#End time (tick)
`
