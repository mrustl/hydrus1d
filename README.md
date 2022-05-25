# hydrus1d

Windows executable only for last official release of [HYDRUS-1D]([https://www.pc-progress.com/en/Default.aspx?h1d-downloads]). 


## Workflow

1. Go to PC-Progress website: [https://www.pc-progress.com/en/Default.aspx?h1d-downloads]()

2. Downloaded and installed last official release of [HYDRUS-1D v4.17.0140]( https://www.pc-progress.com//Downloads/Pgm_Hydrus1D/Hydrus1D_4.17.0140.exe)

3. Go to `C:\Program Files (x86)\PC-Progress\Hydrus-1D 4.xx` and copy `H1D_calc.exe` and
`Ver_H1D.txt` (version info) 


## Licence

As pointed out by the `customer support` of PC-Progress, distribution 
of all files in `C:\Program Files (x86)\PC-Progress\Hydrus-1D 4.xx` is not allowed, 
but confirmed that sharing the calculation module (i.e. `H1D_CALC.exe`) only is 
possible. Thus (and due to the fact that provision of executable files within the 
wrapper `R package` [kwb.hydrus1d](https://kwb-r.github.io/kwb.hydrus1d/) is not 
good practice) it is placed here in its own repo.


> *Von: PC-Progress Customer Support* 
>
> *Gesendet: Mittwoch, 25. Mai 2022 08:37*
>
> *An: Michael Rustler*
>
> *Betreff: RE: HYDRUS1D License Information*
>
>
>
>Dear Michael,
>
>"What you suggest would certainly not work. During the installation of HYDRUS-1D, 
>multiple items are created in the Windows registration database, several OCX 
>objects are registered there, and multiple MFC libraries are copied during the 
>installation. Thus, you should advise your users to download the HYDRUS-1D 
>installation file from the HYDRUS website and install it properly.
>
>Anyway, while we share the software publicly, we do not allow other people to 
distribute it. The users >need to get the software from the HYDRUS website.
>
>We do not know what kind of wrapper you are writing, but it is quite likely that 
>you may need only the computational module, i.e., h1d_calc.exe. Feel free to 
>distribute this file with your software.
>
>Feel free to contact us if you have any questions."
>
>Best regards,
>Jiri 
>
>----[Personal communication](https://github.com/KWB-R/kwb.hydrus1d/issues/2#issue-1248094386)




