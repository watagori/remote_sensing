# Remote sensing

## How to start

1. Click "Home->Add-Ons"
1. Install "Mapping Toolbox"
1. Install "Optimization Toolbox"
1. If you need more, just put it in as matlab says
1. Open "SU_prep_v2.m" file
1. Change the filename(1) around line 20 of the code.
   Satellite image is on
   disk 131.112.42.12\Satellite image\5Sep2012_Shiraho\052875753010_01\052875753010_01_P001_PAN\12SEP05023730-P2AS-052875753010_01_P001.TIF.
   Ex) P:\Satellite image\5Sep2012_Shiraho\052875753010_01\052875753010_01_P001_PAN\12SEP05023730-P2AS-052875753010_01_P001.TIF.
1. Click "Editor -> Run"
1. Type like "SU_main(1,30)" on the command line.
   SU_main(I_AREA, NUM_AREA).
   I_AREA=Number to divide
   NUM_area=number to calculate
1. Finally type "SU_post".
   You would see like this image.
   (When you type SU_main(10,30))
   <img src="https://github.com/watagori/remote_sensing/blob/master/image/Result.png" width=100%>
