# k250-backup
backup of the firmware binaru and config file for my utibots k250vs


If you want to use this for your Ultibots k250vs running a Soothieboard (Atzeeg x5 mini) then you will probably need to change a few things:

Gamma_max -  set this to your printers max height.
extruder.hotend.steps_per_mm  - Unless you are running a Titan Aero extruder you will have to change this to match your setup.

alpha_steps_per_mm - Change this to match the steppers you have.  For me I am using a 1.8 degree steppers and the board is set to 1/32
beta_steps_per_mm  - Change this to match the steppers you have.  For me I am using a 1.8 degree steppers and the board is set to 1/32
gamma_steps_per_mm - Change this to match the steppers you have.  For me I am using a 1.8 degree steppers and the board is set to 1/32

panel.click_button_pin -  for the life of me I couldn't get my viki 2 to work with the default pin on the board.. I think my x5 mini has a bad pin so i had to change it. 
