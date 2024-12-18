Reviung41 

notes:
-ZMK Studio enable, ZMK unlock in layer3 (hold MO1 and MO2 + kp B)
-firmare can be directly downloaded and install in Action tab -add zmk unlock-
-all default keymap i just added the unlock for ZMK studio.

** not completely sure how i did this haha.. but its working so xD..
DIY
1. Install Git [*https://git-scm.com/downloads***](https://git-scm.com/downloads)
1. Make Github account, nvm if you already have one --repo reviung41 shield from zmk repo from https://github.com/zmkfirmware/zmk/tree/main/app/boards/shields/reviung41
2. download and install Github Desktop https://desktop.github.com/download/
3. Open powershell for Windows (search powershell with windows key)
4. copy powershell line code from https://zmk.dev/docs/user-setup ![image](https://github.com/user-attachments/assets/9d9d673d-b9d6-42fd-b273-59a72a85e15f)
5. paste-enter ![image](https://github.com/user-attachments/assets/83b1652f-4e62-406c-8b22-2e4c0eac1f00)
6. Keyboard Shield Selection: 63) REVIUNG41 ![image](https://github.com/user-attachments/assets/cd8eabb9-735f-4267-a080-fddfcd784b80)
7. MCU Board Selection: 10) nice!nano v2
8. if an authentication is needed for Github and it opens up from different browser or browser profile you can copy the link and paste it to another new tab where your Github account is loggin for easy loggin.
9. Open Github Desktop app go to File> CLone repository then click URL tab
10. go back to your Github repo and copy your link and paste it in URL tab and clone
11. Wait until you already cloned your repo in Windows Explorer (which usually located in Document>Github>repo name folder
12. You can now edit the files in the folder, I use https://notepad-plus-plus.org/ to edit code then save.
13. If your done editing, copy, and paste files in your local clone folder go back to Github Desktop click fetch add a summary and commit all the changes you have made.
14. You can now go back to Github repo and go to Action Tab and wait for the firmware to compile (Green Status=Success compile)
15. Download firware and install .uf2 file.

Or Fork this repo or make your own by downloading evrything and copy paste in your own repo.
