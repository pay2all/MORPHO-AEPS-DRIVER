# MORPHO-AEPS-DRIVER
MORPHO AEPS DRIVER INSTALL

STEPS TO INTEGRATION MORPHO AEPS

Morphos RD Service Installation
Supported devices: Morphos MSO 1300 E1, E2 & E3

 Install - MorphoRdServiceL0SoftSetup.exe file of downloaded folder.

 Copy and Replace the below listed files in enclosed folder at ‘C:\MorphoRdServiceL0Soft\’.
o ConfigSettings.ini (Replace) 
- server.crt (Copy) 
o server.key (Copy)
o uidai_public.crt (Replace)


 Restart the Window Machine Or
RestartMorphoRD service- GotoStart->Run.

o Type services.msc and click OK.
o Right Click on Morpho RD Service and click Restart.

 Open https://localhost:11101 and https://127.0.0.1:11101 on the browser to be used for accessing the portal. If the request is being blocked by the browser as Insecure Connection. Accept the risk and add an exception.

 Plug-in the Morpho Biometric Device.
