# Food Preservation by Irradiation
Basically adds in the ability to preserve food via ionizing radiation.

The most likely approach used by a survivor would be x-ray generation.  Such devices are unlikely to be found in the New England area but the right knowledge and parts can enable one to build such a thing in a more portable form.

So after building the device to irradiate food the survivor would
 - Vacuum pack the food item in a plastic bag.
 - Place 1 or several items into the food irradiator and activate it for several minutes.
 - Pull the bagged food which should remain 'fresh' for decades and store it away for tougher times.

Whats new to Cataclysm-DDA via this mod:
 - A new item 'survival food irradiator' tool which is used in recipies and runs on charges of battery.
 - A new recipe to create the survival food irradiator since it can't be found in the world.
 - A new recipe to create plastic bags.  Due to some unfinished ('todo') code in CDDA 1 plastic chunk = 1 bag but 3 bags = 1 plastic chunk (result_mult doesn't work for items not measured in charges) so for the moment the time to create is significantly reduced.
 - MANY new recipes to transform various food items that you might find into the irradiated counterpart.  No new irradiated foods were added, only recipes to create existing irradiated foods.

Future plans:
 - Alter/add recipes so that smaller food stuffs can have more than 1 to a bag, ie blueberries use 1 bag but fit several inside.  Based on in game volume information.
 - When I've sorted out my other code additions, take a look at getting 'result_mult' to work for non-charged items.

Suggested mods:
 - Bright Lights (available via cdda-launcher) which adds in a mod for battery operated tools that allows the use of storage batteries in the tool.
 - Rechargable Batteries (https://github.com/ProfoundDarkness/cdda-Rechargable-Batteries) which enables small and medium storage batteries to be recharged in the 'battery charger' vehicle part added by Bright Lights mod.