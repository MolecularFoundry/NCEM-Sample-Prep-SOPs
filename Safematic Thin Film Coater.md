User SOP

Startup

With unit plugged into a wall outlet, power on with the power switch in the back
A blue screen will appear first. This lists:
software and firmware version
Unit serial number
Number of total carbon coating cycles (CT) performed since last cleaning. At 100, the system will disable until cleaning is performed and the cleaning alarm is reset (Staff only)

User default password: 1234
This account should be shared with users, and grants permissions to program their own recipes


Main menu/manual coating operation

The tools on this menu can be used to manually run a coating session. However, more flexibility is allowed by going into the Recipe menu (see Recipe Menu) and setting a recipe to run. If performing manual coating, the “recipe carbon/glow-discharge” selection in the top left will be “manual” 
The default setting for defining how long a coating cycle runs is Film Thickness, in nm, set in the bottom left of this screen. In this setting the quartz crystal monitors how thick the deposited layer is and prompts the cycle to end when this value is reached. As the quartz crystal gets older, the accuracy of this measurement decreases.
You can also switch Film Thickness to Time by tapping the film thickness value. If so, you can instead set a time in seconds you want the cycle to run for. This is a good option if you don’t trust the thickness of the coating made in Film Thickness mode, but requires you to do some iteration of checking samples to figure out what thickness corresponds to what deposition time.
Cog wheel icon: set stage rotation speed. This is in units of percent (arbitrary), which correspond to rpm according to the plot below. For our unit, the blue “Table” curve is the correct one to reference. 20% (reasonable default) = ~8 rpm. 100% = ~20 rpm.

Brush icon: This runs the target pre-cleaning routine. This cleans the carbon yarn by using a low energy current to bake out adsorbed material, removing oxides. Target pre-cleaning consumes only a very small amount of yarn and might as well be performed before every coating run. It can also be programmed as part of a recipe.
Next to the brush icon, there is a button that can be toggled between “CT regular” and “CT gentle”. Gentle mode extends the cooldown time between temperature spikes/pulses. This longer delay between flashes can help preserve samples that are sensitive to thermal radiation (like formvar, thin carbon, microtome sections)

Making a recipe

Tap the hammer and tool icon in the top right corner of the main menu to open the settings menus, where there are a number of tabs available
Select the first tab: recip CARBON. This is the only type of recipe available, since we only have a carbon evaporator head.
Tap the green + sign to add a new recipe. Set a name, for example: “C 5NM” for a 5 nm carbon layer. There aren’t many characters allowed, so keep it brief and record any necessary parameters iin your notes.
Termination criteria: can be tapped to toggle between thickness and time
Termination value: the thickness in nm or the time in s at which the coating cycle will terminate
Carbon cleaning: saying YES here enables target pre-cleaning before your run. Saying NO disables it. Say YES.
Carbon coating mode: regular or gentle, select depending on the thermal sensitivity of your sample
Glow after coating: does a glow discharge cycle run after coating, yes or no. if set to YES, additional options for configuring the glow discharge will become available below.
Vent after process: If YES, the chamber will be vented when coating is complete. If NO, it will remain under vacuum until vented manually. This selection depends on if you want to minimize the amount of time your sample is outside of vacuum, and if you will be ready to retrieve it after the cycle is over or if you plan to let it sit there for a long time before returning to get it. If you’re working with an air-sensitive sample, safer to say NO and vent manually when you’re ready.
Rotary table speed: sets the rotation speed. See plot and rotation speed settings in manual setup above.
After setting up your recipe, it can be selected from the main menu and run by pressing START in the bottom right corner.
