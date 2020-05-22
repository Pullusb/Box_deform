# Grease pencil Box deform 
Blender addon - Modal that create temporary deforming rectangle around selected GP points 

## [Download latest](https://github.com/Pullusb/Box_deform/archive/master.zip)

Want to support me? [Check this page](http://www.samuelbernou.fr/donate)

---  

## Description

I first created this as a prototype following my request post : [Cage deform active tool for grease pencil](https://blender.community/c/rightclickselect/P9fbbc/)
Turns out this works really well as it is, so I added some shortcuts to make easier use and voilà, (touché!)

Developped for Grease pencil (only grease pencil edit mode supported for now), but mesh might be supported later if proved usefull.


<!-- ![lock frame](https://github.com/Pullusb/images_repo/raw/master/PAPERMOD_Lock_frame.png) -->

**How to use** (same tutorial in addon preferences)
In _GP edit mode_, select points then use shortcut `Ctrl + T`  
The lattice box is generated facing your view (be sure to face canvas if you want to stay on it)  
Then use following shortcuts (also displayed in topbar)  

`Spacebar` / `Enter` : Confirm
`Delete` / `Backspace` / `Tab`(twice) / `ctrl+T` : Cancel
`M` : Toggle between Linear and Spline mode at any moment
`1-9 top row number` : Shortcut to subdivide the box
`Ctrl + arrows-keys` : Subdivide the box in X/Y axis individually for custom deformation

Note: A cancel warning will be displayed the first time you hit Tab (to avoid mis-canceling)

---

## Changelog:

 2020-05-23 v0.1.1
  - first repo push version