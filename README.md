Aight SUNBURST CONFIGURABLE CVT IS HERE BOYS

I made this because when I requested this feature someone thought it wasn't as simple as I said it was and that I couldn't simply do it so I did it anyway

Two new parts:
## Idle configurable race ECU:
* It actually functionally does nothing special over race ECU except adds an option to change your idle rpm, something that beamng devs should've done from the start.
* It actually has no real benefit for CVTs but can be highly beneficial for those using "normal" manual transmissions

## Configurable CVT:
* You can adjust the ratio (but the torque bandwidth still has the same limits of the original CVT, original torque ratio range is 0.7-2.7 and user defined tuning defines the lower torque ratio, the upper torque range is adjusted accordingly),
* you can adjust how long the transmission will allow you to retain your rpm (letting go of the throttle won't reduce your rpm immediately)
* how responsive the CVT is to the throttle (if you increase responsiveness, you are penalised with even less torque during that short period of time as the CVT catches up but it really is negligible)
* full lock rpm - Mostly affects high performing engines. Low performing engines it doesnt make a difference unless you set it rediculously low which may stall your engine

I wanted to have a custom throttle-target RPM curve but I couldn't get it to work unfortunately, so the variables are hidden from view. If you open your .pc file after saving a config with this module, you can manually edit it (`cvtThrottleCurve`2-4) but I doubt you'll see any changes because I didn't see any changes
