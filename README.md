local_manifest
==============
this is for all devices maintained by rc420head (+ a few extra) for candykat

htc
 ville 2.15 & 2.16
 evita
 m7gsm
 m7spr
 m7vzw
 m8
 
samsung
 i9300
 d2lte
 
lg
 d801

oneplus
 bacon 
 
 full set of builds
 
 . build/envsetup.sh && brunch bacon && brunch d801 && brunch i9300 && brunch m8 && brunch m7vzw && brunch m7spr && brunch m7 && brunch evita && brunch d2lte && brunch ville && mv ~/candykat/out/target/product/ville ~/path/outside/source/215 && cd ~/candykat/device/htc/ville && git checkout ck44216 && cd ~/candykat && brunch ville -j# (#=twice your cpu cores)
