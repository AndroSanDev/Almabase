# Deployment Instructions


## Prerequisites for Deployment 

- Verify the MATLAB Compiler Runtime (MCR) is installed and ensure you    
  have installed version 7.17 (R2012a)  

- If the MCR is not installed, do the following:
  1. Enter
  
      ```
      >> mcrinstaller
      ```
      
      at MATLAB prompt. This MCR Installer command displays the 
      location of the MCR Installer.

  1. Run the MCR Installer

Or Download Windows 64bit version of MCR from the MathWorks website:

   http://www.mathworks.com/products/compiler/
   
   
For more information about the MCR and the MCR Installer, see 
“Working With the MCR” in the MATLAB Compiler User’s Guide.    


NOTE: You will need administrator rights to run MCRInstaller 


## Files to Deploy and Package

### Files to package for Standalone 

- AlmaBase.exe
- MCRInstaller.exe 
   -include when building component by clicking "Add MCR" link 
    in deploytool
- This readme file 

## Definitions

For information on deployment terminology, go to 
http://www.mathworks.com/help. Select your product and see 
the Glossary in the User’s Guide.





