2022.05.27 CraftFlow

Pr3dator  v1.1.26208
CraftGui  v1.2.8530
FlowAdmin V0.9.32

Firmware:
Added: Wiper usage after first G28
Added: Temperature sensor measurement instability checking and warning. 
Fix:   Minor bugfixes
                                                                                                                     
                                                                                                                     
                                                                                                                     
                                                                                                                     
                                                                                                                     
                                                                                                                     
                                                                                                                     
                                                                                                                     
                                                                                                                     
                                                                                                                     
                                                                                                                     
                                                                                                                     
                                                                                                                     
                                                                                                                     
                                                                                                                     
                                                                                                                     
                                                                                                                     
                                                                                                                     
                                                                                                                     

################################################################################ 
2022.02.16 CraftFlow

Pr3dator  v1.1.25996
CraftGui  v1.2.8527
FlowAdmin V0.9.25

Firmware: 
Added:   Dome detect
Added:   Maintenance instructions
Fix:     Elimination of printed object height error when z-hop is applied
Fix:     Minor bugfixes

Flowadmin:
Added:   Better error handling
Added:   Fixed multiple unhandled error that may cause system crash from time-to-time (File manager, Storage size check, Pendrive size check)
Added:   Option to delete and remove saved Cloud storage access
Added:   Network connection checker and feedback display
Added:   More mobile friendly file list
Added:   Minor performance improvement
Fix:     Jogging click error
Fix:     Profile save/export error
Fix:     Pendrive check on cloud file manager pages
Fix:     Potential custom sound upload errors
Fix:     Custom sound preview playback in settings menu dropdown

################################################################################ 
2021.11.08 CraftFlow

Pr3dator  v1.1.25838
CraftGui  v1.2.8522
FlowAdmin V0.9.13

Firmware: - !!!! Recalibration required !!!!
Added:   Online support
Added:   WiFi password with space
Added:   Romanian language
Added:   Bed heat balance waiting
Fix:     Extruded length calculation
Fix:     Mesh Bed 1st layer
Fix:     Online update 
Fix:     Flash drive mount
Fix:     RGB logo usage
Fix:     Minor bugs

Flowadmin:
Added:   Remote web access
Added:   Cloud file storage access
Added:   code viewer
Added:   Upload print history to craftbot.com account
Added:   Custom sounds for events
Added:   Export and import printer settings
Added:   Firmware update check
Fix:     Redesign
Fix:     Minor bugfixes


################################################################################ 
2021.08.13 CraftFlow

Pr3dator  v1.1.25799
CraftGui  v1.2.8512
FlowAdmin V0.8.19

Firmware: - !!!! Recalibration required !!!!
Fix:   Motor driver false error indication fixed
Fix:   Static ip settings fixed
Fix:   Minor bugs


################################################################################
2021.03.17 CraftFlow

Pr3dator  v1.1.25642
CraftGui  v1.2.8474
FlowAdmin V0.8.19

Firmware: - !!!! Recalibration required !!!!
Added: HMI and predator code refactoring
Added: Added tutorial videos to the calibration steps
Added: The machine recalculates the speed estimate when you set the speed while printing
Added: The dome fan speed is taken over from the gcode when printing continues
Added: S-curve motion control
Added: Modified acceleration and deceleration ramp
Added: Extruder unload speed decreased
Added: X motor current tuning during boot
Added: The Z axes movement speed has been increased in Jog menu
Added: Z offset calibration has further fine tuned
Added: Reverse tray calibration due to successful calibration 
Added: Bed compenzation with filament flow in mirror or paralell print mode
Added: New personalised menu item: Moving the build plate down if the printing is interrupted
Added: Checking the USB port before firmware update to avoid update problem
Added: Mesh compensation is now distributed in 20 mm
Added: The dome fan lockable during the print menu
Added: Pr3Dator board update is added to the update menu. It is visible only when the Pr3D board version differs than the expected version
Added: The email alerts list has been expanded
Added: M117 support added
Added: E-mail style updated
Fix:   False bed temperature sensing has been fixed
Fix:   Motor driver false error indication fixed
Fix:   Minor bugs

FlowAdmin:
Added: Browser will remember login even if printer is restarted
Added: Added another file browser to the top of file manager list
Added: Redirect to dashboard after successful print start
Added: Kick to login screen if session timed out
Fix:   Small fixes and improvements


################################################################################
2020.09.17 CraftFlow

Pr3dator v1.1.24338
CraftGui v1.1.6622
FlowAdmin V0.8.9


Firmware:
Fix:   Hot bug fix


################################################################################
2020.07.24 CraftFlow

Pr3dator  v1.1.24329
CraftGui  v1.1.6619
FlowAdmin V0.8.9

Firmware:
Added: Webadmin HMI communication functions extended.
Added: GUI recovery scripts added.
Added: Layer count and Z position info added to the print screen.
Added: Default door temperature treshold set to 60C.
Added: Print time estimation routine reworked.
Added: Status/log files expanded width mesh bed values.
Added: Extended storage of printed data in a local database that can be saved to a flash drive.
Fix:   Minor bugs

FlowAdmin:
Added: Printer overlay message / dialog display, handle and response from FlowAdmin
Added: Print history display with every event
Fix:   Option for cookie timeout, fix the forced 15 minute cookie timeout bug
Fix:   Fixed age old bug where left buttons / menu disappers for some reason
Added: Faster stored data read
Fix:   Fixed socket message timeout / wait bug
Added: Simplified boot up sequence
Added: Printer calculated ETA used when present
Added: Huge settings / control / print settings update
Fix:   Fixed file manager security / session issue
Added: Removed unncecessary ajax/file calls on dashboard
Added: New e-mail template
Added: Toggle temp chart visibility
Added: Multiple other minor changes


################################################################################
2020.06.12 CraftFlow

Pr3dator  v1.1.24276
CraftGui  v1.1.5863
FlowAdmin V0.7.21

Firmware:
Added: At the end of printing, the video continues to be recorded for a few seconds to prevent the video from ending abruptly.
Added: The system time and date can also be set offline in the timezone menu.
Added: The machine supports for EXFAT file systems on mounted media.
Added: The info menu has been expanded with the Report tab. Mesh level and status values can be saved to media.
Added: Startup wizard has been expanded with SMTP settings.
Added: Calibration menu has been expanded to sub-items.
Added: The machine performs an assisted bed measurement before printing. This can be enable or disable in the personalized menu.
Added: During printing when remove flash drive the machine goes pause state and a warning message appears in display.
Added: Extruder fan control frequency has modified (from 26 Khz to 150 kHz ). 
Fix:   Minor bugs

FlowAdmin:
Fix:   Minor bugs


################################################################################
2020.04.30. CraftFlow

Pr3dator  v1.1.23925
CraftGui  v1.1.5353
FlowAdmin V0.7.16

Added: New languages: Spanish, Italian
Added: Now the calibration status is indicated in the Calibrate menu.
Fix:   The PID algorithm has been modified to avoid overshootings when changing temperatures.
Fix:   False thermal fault indications have been fixed.
Fix:   It is not possible to extrude in the print menu only when there is a pause state.
Added: FMS sensitivity is now adjustable
Fix:   The "Case fan does not rotate" false error signal fixed.
Added: Dome fan does not rotate error detection implemented.
Added: Now the door can be opened during calibration and printing
Fix:   Time-lapse video recording has been reworked. The machine on the fly generates video without images.
Added: Cold extrusion warning message implemented.
Added: Personalized options have been expanded. You can choose the printer go to the pause position or not if the door opens during printing.
Fix:   During update the "Main board flash operation failed" have been fixed.
Fix:   Heads YX calibration procedure modified: now it is easier finds the calibration hole.
Fix:   Static ip settings screen freeze fixed.
Fix:   parameters are not deleted after update
Fix:   False battery fault indication have been fixed.
Added: The cover fan can be adjusted during printing.
Added: You can also open the door during calibration or printing if the conditions are right.
Fix:   Update menu has been modified. There is no rescan button.
Fix:   The "No buildplate installed" false error signal fixed.

FlowAdmin: 0.7.16
Fix:   Remote web connection fixes
Added: Added "Stop heating" to in progress printing sliders
Fix:   Removed video playback popup button on mp4-s in file manager
Fix:   Status check error handling
Fix:   Typo fixes

Other UI fixes have been made.
After updating, recalibration is required due to changes!!!
