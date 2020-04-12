# Default Configuration File

```yaml
# -------------------------------------------------------------------------------------------
#
#  Welcome to OmegaVision's main configuration file.
#
#  Here you'll find of the settings and options that you can
#  customize to your server needs. Most features are customizable
#  to an extent.
#
# For help you can visit the wiki at: https://bitbucket.org/oweapon/omegavision/wiki/Home
# If you have any issues, report them here: https://bitbucket.org/oweapon/omegavision/issues
#
# -------------------------------------------------------------------------------------------

# If set to true, players with permission omegavision.login will login with nightvision
# enabled, if they logged out without it still enabled.
Night_Vision_Login: true

# If set to true, players will get particle effects when nightvision is applied
Particle_Effects: true

# If set to true, potion effect produce more, translucent, particles.
# This does require the Particle_Effect setting to be set to true
Particle_Ambient: true

# If set to true, an icon will display on the screen when nightvision is applied
NightVision_Icon: true

# If set to true, players will get an actionbar message when they toggle nightvision
ActionBar_Messages: true

# If set to true, players will be able to use milk buckets to remove the potion effects
# from when they toggle nightvision
Bucket_Usage: true

# If set to true, once players use a milk bucket to remove potion effects from nightvision
# the bucket will be emptied so they need to refill it again to use it.
Bucket_Empty: true

# If set to true, players will keep nightvision when they die.
Keep_NightVision_On_Death: true

# If true, players who use nightvision will get blinded for a period of time.
Blindness_Effect:
  # Determines whether you want to enable this feature
  Enabled: true
  # How long nightvision must be active for before blindness kicks in (In minutes).
  Timer: 10
  # How long the blindness will last (In minutes).
  Duration: 20

# If set to true, those with the permission omegavision.update will recieve messages
# when the plugin updates on spigot
Update_Notify: true
```