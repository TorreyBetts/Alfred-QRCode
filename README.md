# Alfred-QRCode
All of the QR code generator workflows I've come across use a dependency, such as an external installation, embedded app, or web service. Given that MacOS can create QR codes natively, that's what I did with this workflow.
<img width="621" alt="image" src="https://user-images.githubusercontent.com/5093679/120118401-5e6aa280-c160-11eb-98eb-c3e5f83f9af6.png">

# Installation
This workflow doesn't require any dependencies for installation, all that is required is to double click and import the workflow into Alfred. If you wish to enable a selection hotkey, look for the yellow workflow action to configure.

<img width="946" alt="image" src="https://user-images.githubusercontent.com/5093679/120122979-5e779c00-c17a-11eb-9342-15fac3292d26.png">

# Usage
The current version of this workflow contains two keywords for Alfred, **qrc** & **qrp**. When using either **qrc** or **qrp** without a parameter this workflow will attempt to use text contained on the clipboard. This same flow is followed if you set a hotkey for the selection and nothing is selected.

- **qrc [your text]** -- Creates your QR code and copies it to the clipboard
- **qrp [your text]** -- Creates your QR code, by copying it to the clipboard and also opens it with Preview for saving

<img width="628" alt="image" src="https://user-images.githubusercontent.com/5093679/120118600-62e38b00-c161-11eb-8fae-834aa9007838.png">
<img width="620" alt="image" src="https://user-images.githubusercontent.com/5093679/120118730-fddc6500-c161-11eb-9e03-84c8990c15a8.png">

