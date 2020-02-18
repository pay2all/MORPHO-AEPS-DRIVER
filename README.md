Driver Link

https://drive.google.com/drive/folders/1K82kXao-AFZxnwZBAoikwYFRngknJoz5?usp=sharing

# MORPHO-AEPS-DRIVER
MORPHO AEPS DRIVER INSTALL

STEPS TO INTEGRATION MORPHO AEPS

Morphos RD Service Installation
Supported devices: Morphos MSO 1300 E1, E2 & E3

1. Install - MorphoRdServiceL0SoftSetup.exe file of downloaded folder.

2. Copy and Replace the below listed files in enclosed folder at ‘C:\MorphoRdServiceL0Soft\’.
3. ConfigSettings.ini (Replace) 
 server.crt (Copy) 
 server.key (Copy)
 uidai_public.crt (Replace)


4. Restart the Window Machine Or
RestartMorphoRD service- GotoStart->Run.

5. Type services.msc and click OK.
6. Right Click on Morpho RD Service and click Restart.

7. Open https://localhost:11101 and https://127.0.0.1:11101 on the browser to be used for accessing the portal. If the request is being blocked by the browser as Insecure Connection. Accept the risk and add an exception.

8. Plug-in the Morpho Biometric Device.
