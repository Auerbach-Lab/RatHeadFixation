# Rat Head Fixation System

 - **Author:** Brian James, \<james29@illinois.edu>
 - **Date:** 2022-08-20
 - **Version:** 0.3.5
 - **Primary Investigator:** Ben Auerbach, Auerbach Lab, University of Illinois \<bda5@illinois.edu>


## Description
This is a head fixation system for adult laboratory rats, suitable for audiology research. It is derived from the Hight mouse head fixation system. Headplates were re-created using the Hight plates as guidance, but in larger dimensions and contoured to match a CT scan of a rat skull. The mounting hole spacing was widened to minimize torque, and the mating portion of the angled headbar was thickened for additional strength. Because of the different mounting hole spacing, the two systems do not share interchangable parts.


## Parts
**rat_headplateACx** -- The primary headplate design, compatible with straight or angled headbar. This design is symmetrical; it can be used with the mounting plate on the left or the right side interchangably. Headplates can be 3d printed in stainless steel (such as 316) from a variety of manufacturers; [Craftcloud](craftcloud3d.com) allows easy comparison shopping. 

**rat_headplateIC** -- Alternative headplate suitable for probing the inferior colliculus or other regions requiring a dorsal approach. This design is compatible with straight headbar only. While it will mate with the angled headbar, the bar would need to pass downward through the bench top when securing a prone rat. This design is necessarily asymmetrical but can be mirrored for use with a right side headbar. This design is still version 0.1.

**rat_headbarStraight** -- Simple rod to which the plate is secured while in use, machined from 0.5" diameter rod stock, e.g. [Grainger #3ANN6](https://www.grainger.com/product/GRAINGER-APPROVED-Rod-Stock-316-3ANN6). Stainless steel alloy 316 is recommended for its improved resistance to corrosion, particularly if using cleaning solutions that decompose to produce chloride ions, such as bleach or benzalkonium chloride (Lysol, Microban, 3M Quat, most disinfecting wipes, etc).

**rat_headbarAngled** -- An alternative headbar design which may be useful if positioning the rat on a floating ball or similar movable surfaces.

**#5-40 Socket Head Cap Screw, 3/8 Length, 3/32 Hex"** -- Two screws are required per head**bar** for fastening a headplate, e.g. [Grainger #6XA50](https://www.grainger.com/product/GRAINGER-APPROVED-Socket-Head-Cap-Screw-5-40-6XA50).

**3/32 Hex Key / Allen Wrench** -- Socket head screws are driven using a hex key, e.g. [Grainger #38TG47](https://www.grainger.com/product/EKLIND-Hex-Key-3-32-in-Tip-Size-38TG47), rather than a screwdriver. A ball-end key is more convenient since it can be used at multiple angles. Verify the drive size of the fasteners you're using; #5 screws may require either 5/64" or 3/32" drive.

**C&B Metabond Dental Cement System** -- Only the following components are specifically
required:

 - Etchant Gel (S395)
 - Quick Base (S398)
 - C Universal TBB Catalyst (S371)
 - Radiopaque Tooth Shade Powder (S396)
 - Measuring Scoop (S378)
 - Ceramic Mixing Dish With Temperature Indicator (S387)

The remaining components from the all-in-one kit (S380) -- dentin activator, clear powder, applicator tools and brushes -- are not needed. If purchasing the kit, the clear powder may also be used interchangably with the opaque powder.

**Speedball India Ink** -- Used for dyeing the cement mixture. This brand is specifically
recommended by Hight for its consistency and imparted blackness.

**Toothpicks** and **Cotton/Foam Swabs** -- Used to apply cement and etchant, respectively.


## Files
The master assembly file is `rat_head_fixation_assembly.iam`, which shows how parts fit together and sit on the skull. That assembly and the individual `.ipt` part files are in Autodesk Inventor formats.

Dimensional drawings of the headbars are provided as `.dwg` Autodesk drawings and as PDFs, to be given to a machine shop. Only imperial unit versions are provided since both the base rod stock and the fasteners are in imperial units. Metric users should redefine the headbar to be machined from metric rod stock, probably 12 mm, and change the tapped holes to M3. No dimensional drawings are provided for headplate files, as these are intended to be 3d printed directly from the `.ipt` or `.stl` files. Part `.stl` files are dimensioned in millimeters.

Other provided files include the rat skull model in its original format (`RatSkull_Mesh1.stl`), a cropped version with a reduced vertex count created in Autodesk Meshmixer (`ratskull.mix`), and intermediate `.obj` files and corresponding `.ipt` files for the skull and cutaway profile views. There is also a sample 16x Nikon LWD microscope objective model to test clearance.

All files created for the Rat Head Fixation System have filenames prefixed with `rat` to differentiate them from similar Hight files. Manufacturer-provided files such as fasteners were not renamed.


## Usage
The AX headplate is intended to be positioned just forward of bregma, nearer to bregma
than to lambda, as pictured below. The angled headbar can be used when there needs to be
clearance behind the rat, such as when using a floating ball setup.

<img src="https://i.imgur.com/D4JZl8x.png" alt="usage_ax_v03.png" height="305">  <img src="https://i.imgur.com/lrhLZyE.png" alt="usage_headbars.png" height="305">

### Directions
1. Remove the ceramic mixing dish from freezer and place over ice to keep it cold.
2. Thoroughly clean cranium of any remaining tissue/periosteum and moisture.
3. Saturate swab with etchant, then apply swab over cleaned cranium surface. Let stand 30 seconds, then immediately and thoroughly wipe off with a clean swab. Be careful to not let etchant contact any soft tissue.
4. Position and fixate the headplate over the cranium using the headbar.
5. Prepare the cement. With the mixing dish still on ice, add (in this order) to one well: **4-5 drops Quick Base** (immediately re-cap container), **1 drop India Ink**, **1 drop Catalyst**  (immediately re-cap syringe). Mix gently, for no more than 5 seconds. Finally, add **2 scoops Radiopaque Powder** and stir gently for 5-10 seconds to a creamy consistency.
6. Using clean toothpicks, apply cement mixture to bond the cranium and headplate. Once applied to the headplate, the cement quickly solidifies in seconds to minutes.
7. Clean ceramic mixing dish before cement fully cures.
8. Allow the cement to set for 6 minutes (and allow at least 30 minutes before applying force to the headplate). Afterward, leave no part of the cranium exposed to air.

### Notes
 - Store the ceramic mixing dish in the freezer to ensure it is thoroughly chilled before use.
 - For best results, store mixing dish upside down, with water added to fill the base so that the entire dish is in contact with ice for the procedure.
 - Cured cement on instruments or the mixing dish can be softened by soaking in acetone or chloroform.
 - Coating surfaces in KY, petroleum jelly, glycerine, or mineral oil will prevent cement from bonding to them.
- Cement viscosity increases over time after being mixed.
- Working time for the cement mixture is 2 minutes at 15°C, or up to 5 minutes if kept colder. If the mixture is allowed to come to room temperature (24°C) the working time is cut to 20 seconds or less.
- Headplate implantations using this technique have been tested to be functional for at least 3 months.


## Sources
**Hight Mouse Head Fixation System**
Sandra Romero, Ariel E Hight, Kameron K Clayton, Jennifer Resnik, Ross S Williamson, Kenneth E Hancock, Daniel B Polley, Cellular and Widefield Imaging of Sound Frequency Organization in Primary and Higher Order Fields of the Mouse Auditory Cortex, _Cerebral Cortex_, Volume 30, Issue 3, March 2020, Pages 1603–1622, https://doi.org/10.1093/cercor/bhz190

**3D .stl File of Rat Skull**
M. Pohl, Bernd; Fernando Gasca; Olaf Christ; Hofmann, Ulrich G. (2013): 3D .stl file of rat skull. figshare. Dataset. https://doi.org/10.6084/m9.figshare.777745.v1

**3D .stl File of Mouse Skull**
Rowe T, Demarest M. (2001): "Mus musculus". Dataset: Digital Morphology. http://digimorph.org/specimens/Mus_musculus/

**Mouse Skull from Mouse skull (from micro-CT)**
https://www.thingiverse.com/thing:20200 by [MarkU](https://www.thingiverse.com/MarkU)
![Creative Commons Attribution License](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)

**16X Nikon CFI LWD Plan Fluorite Objective - CAD files**
https://www.thorlabs.com/thorproduct.cfm?partnumber=N16XLWD-PF

**Socket Head Cap Screw - CAD files**
https://www.grainger.com/product/GRAINGER-APPROVED-Socket-Head-Cap-Screw-5-40-6XA50