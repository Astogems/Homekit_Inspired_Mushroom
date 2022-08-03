# Homekit_Inspired_Mushroom

Entity IDs have been redacted.

Paste this into your raw config. Do note that you will have to use input_select and input_boolean helpers in order for this to work properly.

Animated Background:- Create a input_select.background_selection helper and list the options as 1 to 28. Inserted the new entity ID into line 8 and 133.

Kiosk Mode:- Create a input_boolean.kiosk_mode helper and insert that entity ID into line 3 and 135.

For the menu selection, Look at line 155, there is an entity ID there, create that exact entity ID and list the options as whatever you like.

See line 164 for the tap_action, notice how on each press, it updates the input_select to a different predefined state.

Now hopefully you understood the logic, look at line 232 and replace the states with whatever you have created. Remember to add the entity_id on line 233 as well.

From the Living Room Accordian, take a look at Line 443, there is an entity ID, you have to input a input_boolean.expand_livingroom.

This will toggle the entity when you take on the title.

Lastly, input the same entity ID to line 458, and the accordian will be complete.

Now replicate the steps over and over until you have all the devices you need.

If you have any questions and would like to DIY, please PM me on discord, thats where I reply the quickest and I will definitely see that you get it done.Alternatively, you could hire my services to help you build this dashboard.
