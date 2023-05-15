# Glass of coke rendering

## Overall ([report](https://drive.google.com/file/d/1Y48_KAl0-PUQekoeWXARbjMI1Tb5IlF1/view?usp=share_link))
The objective of this project is to render a glass containing Coca-Cola using rib primitives and apply suitable BRDF models to accurately represent the object’s appearance. Additionally, the project involves implementing texture and displacement patterns on the table beneath the main object. Furthermore, an environment map was incorporated to provide realistic lighting. Finally, motion blur and depth of field techniques were employed to enhance the overall visual quality of the rendering.

## Result
![](./results/Final%20with%20depth%2001.jpg)
![](./results/Final%20with%20depth%2002.jpg)

## Requirements
RenderManProServer 24.0 or above

## Build and Repository Structure
- Please download [material](https://drive.google.com/file/d/1fgTx3xBFNH0O2BoqCF1uSii3F8A92AlT/view?usp=share_link) as .tx file is too large that I cannot upload on github. Then extract under "material" folder.

- Please download [HDRI](https://drive.google.com/file/d/1ZskYMDCajDv4VdCkyT9qe0emX0FD29Mv/view?usp=share_link)as .tx file is too large that I cannot upload on github. Then extract under ROOT dictionary.

- Main code is  ./ribs/Glass.rib. To run this code:
``` c
// Download repository
git clone git@github.com:Yuqian-He/Glass-of-coke_RIB.git
cd Glass-of-coke_RIB

//  run the code
prman ./ribs/Glass.rib
```



