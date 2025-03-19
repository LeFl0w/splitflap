# Inputs
- Photo size : 114mm x 152mm
- use geant des beaux arts carton gris board support thickness : 1,4mm 50cmx70cm ref : 14330 : 3,95€
- screw M1.2 x 8mm . thread pitch 0,25mm 
-motor https://www.aliexpress.us/item/4001163089405.html?gatewayAdapt=4itemAdapt 

# assembly steps
- select 2 photos
- use Photoflap\Laser\PhotoSupport.svg with Photoflap\Laser\Photosupport_cardboard1.4mm.LCF parameter to cut the board support
- glue the photo on the board support (be careful of the orientation for the one behind)
- print two board edge
- screw from inside to outside

# Laser
- PhotoSupport.svg is cardboard for holding photo. The size is equal to the photo size.
- generate to support with py.exe .\generate_2d.py --num-flaps 200 --thickness 1.6

# 3d print
- use two board edge for each photo support
