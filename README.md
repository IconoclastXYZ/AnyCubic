# AnyCubic
Info on my adventures with AnyCubic resin printers

# Printer model details
- Anycubic MonoX 6k
- Wash and cure station +

# In no particular order...
- the slicer which comes with the printer is 'average'
- tried several options and landed on Lychee Slicer, free version

# Raft settings
- Default angled up edge raft from Lychee causes suction issues and comes off
- Settled on circular
- 10 layers at 0.05mm

# Support settings
- Mostly the automatic orientation and 'medium' supports work well from Lychee
- Add a few extra 'heavy' supports at the bottom so that the print doesn't fall off before it has really started

# Layer exposure settings
- 'Bottom layers' = 10 - that way when the Anycubic ramps down the exposure time it blends with the start of the supports above the raft - otherwise it all just falls off before it has even started
- 'Bottom exposure' - 25 sec at 80% power using Anycubic EVA resin in white
- 'Normal layers' = 2.5 sec, rest as above
- Interlayer light off delay - 0.5 sec

# Lift settings
- Done in two stages for bottom layers and normal layers
- Bottom layers - 0.5mm/s for 3mm then 1mm/s for 4mm raising, 3mm/s for 4mm then 1mm/s for 3mm when lowering back down
- Normal layers - 0.7mm/s for 3mm - rest the same
- Tweaking these settings, in particular using slower to start, seemed to solve most of my early print failures

# Printer physical setup
- WhamBam magnetic plate - makes for *much easier* print removal and with a second plate, can start again straight away
- Smaller squirter bottle for dispensing IPA
- Paper towels to rest things on - but NOT for cleaning - they are more abrasive than you imagine and leave bits behind
- Chux Superwipes (or cheap copies) for actual cleaning of plates and FEP film - no scratches, so bits left behind
- Tried tissues (awful), tried laboratory wipes (Kimwipes delicate task wipes, lint free) - awful, abrasive and not lint free
- Eye protection
- Nitrile disposable gloves - better than latex, last quite a few uses

# Print cleanup
- remove WhamBam plate, scrape excess resin into bath and put straight into Wash and Cure station bucket, wash for 10 min
- drain IPA and flex plate to remove - 'pops off'
- wash in warm water to help with support removal
- use forceps or small pliers to break away bases of supports and allow removal without breaking the print

# Resin
- Currently using the Eco Resins from Anycubic

# Resin coating
- https://www.rowetrading.com.au/product/xtc-3dcoating-mini-69624/ - more for FDM than MSLA...
