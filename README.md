nkro+1k poll rate nk65

-2 layers default keys except the bottom 3 fn
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
- --------------------------------------------------------------------------

![nk65 Layer 0](https://user-images.githubusercontent.com/88870880/131321854-5c254026-f7b4-454e-b3e2-e3a65013a526.PNG)
![nk65 Layer 1](https://user-images.githubusercontent.com/88870880/131321852-38d2ecdc-a623-48af-b268-fbb4b0fa4acf.PNG)


