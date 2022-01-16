# Faust
Faust is a custom-made software solution for **GAMA Studio, Belgrade**. It is intended to speed up the workflow of the tasks that can be automated.  

It is consisted of multiple programs. In everyday work, it has been shown that this solution speeds up the job up to **10X**, just by automating some tasks that, otherwise, had to be done manually.

It is suggested to run this software through **Total Commander**. All the options will be listed in a **vertical bar**.  
The setup will automatically add these options into you **Total Commander**.

![faust 4](https://user-images.githubusercontent.com/40390033/149665176-59817cd8-3f27-4f3d-875d-285623fe54dc.png)

## INI Setup

All programs use data provided by **INI (configuration) files**. They are being managed by this **INI Setup**.

<img src="https://user-images.githubusercontent.com/40390033/149665017-e44e0dd3-636c-4110-a8c8-55f7afc609d9.png" width="30%"></img> <img src="https://user-images.githubusercontent.com/40390033/149665015-2a629391-89ad-4ec8-9bd1-6216d8ca4842.png" width="30%"></img> <img src="https://user-images.githubusercontent.com/40390033/149665016-7dfc88dd-2184-4289-8497-7bab29ab4cbc.png" width="30%"></img>   

First page of INI Setup is linked to **basic settings**, like specific paths etc.  
Second page of INI Setup is linked to **printing plates sizes and types**.  
Third page of INI Setup is linked to **information about clients**.

## Dimenzije fajlova (File dimensions)

This programs lists all the **PDF and PS (PostScript) files** located on a remote location that have the current date as **Date modified** attribute.  
It also represents their **MediaBox**, **CropBox** and **TrimBox** sizes, as well as the page count.  
The program will show a warning when there are pages with different sizes. Then it gives you an opportunity to see sizes of every page in a file.    
<img src="https://user-images.githubusercontent.com/40390033/149665308-245f95bb-20b4-4c98-8de9-1c37ee6e9655.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/40390033/149665334-29164f74-451c-44cb-bd11-e5000e7014b1.png" width="28%" height="28%"></img>  

## Dizanje na ploču (Apply to Print Plate)

This program changes all **PageBox** dimensions to specific, based on a selected Print Plate.  
If the program can detect which plate does the client use, it'll apply the file to it automatically.  
Otherwise, it will ask you either which plate to use, if the client uses more than one, or to enter the plate sizes, if there is no information about client.

<img src="https://user-images.githubusercontent.com/40390033/149665541-dc32213d-2228-4075-9bd7-b6358aa0bfb3.png" width="45%"></img> 
<img src="https://user-images.githubusercontent.com/40390033/149665543-59989cc7-a6d2-4cb3-a3a0-ff8c9ebf3a5d.png" width="45%"></img> 

## Prebacivanje u kućice ploča (Moving to Print Plate directories)

This program moves all **.TIFF** and **.TIF** files to specific directiories. It detects to which folder should it go based on the name of the file.  
This software also includes an GUI interface and a progress bar, which visually represents the percentage of work done.  

<img src="https://user-images.githubusercontent.com/40390033/149665752-0e79070a-d7ac-4a70-bf55-55ccf456ba74.png" width="45%"></img> 


## Other various programs
This software solution includes a few other programs which are copying/moving files/folders to specific locations. They have no GUI interface, so all the work is being done behind the stage.
Some of them also rename the files accordingly to naming convention.  

## FAQ
**Q**: Where is source code?  
**A**: Contact me on the email provided on my GitHub profile and we'll work something out.  
**Q**: In which programming language has this been written?  
**A**: The entire software solution has been written in **C#**.  
**Q**: Which license does cover this software solution?  
**A**: This software solution is under **3-Clause BSD License**.  
**Q**: Where's the Serbian README?  
**A**: You can find it in **README_srb.md** file.  

