nkro+1k poll rate nk65

-2 layers
- fn+ home = nkro on 
- fn+ pgup = nrko off
- fn+ pgdn = toggle nrko
- -----------------------------------
Converting mycustomqmkconfig.json file to  key.c file 

qmk json2c "PATH NAME HERE\mycustomqmkconfig.json"    

- example: qmk json2c "C:\Users\User\Desktop\QmkConfigs\mycustomqmkconfig.json"
---------------------------------------------------------------------------

edit rules.mk 
NRKO ENABLE = yes

Flash nk65_mykeymap.bin file


### Flash ###

- Unplug
- Hold Escape
- Plug In
- Flash using QMK Toolbox
