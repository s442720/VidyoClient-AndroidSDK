# VidyoClient-AndroidSDK

### caller
Code(new): https://github.com/s442720/VidyoClient-AndroidSDK-caller-v3

~~APK(old): https://drive.google.com/file/d/10ZMNxFWBk6rrK-fzu3vjUpHIBvgo-61y/view?usp=sharing~~

### receiver
Code(new): https://github.com/s442720/VidyoClient-AndroidSDK-receiver-v3

~~APK(old): https://drive.google.com/file/d/1NXsYT9dDYNMookk_TDj-fQ5NwL67jEN7/view?usp=sharing~~

2020/01/03  v3
1. Import more functions for video-chat (vidyo.io)
2. Connect to the database(Firebase), and use "connected" argument(int) to control current status. (0: init, 1: connected successfully, 2: connection ended)
3. Use modal in caller and AlertDialog in receiver
4. Disable the back button for android
-----------------------------------------------------------------------
2020/01/15  v4
1. Rewrite and simplify the parts of reading from and updating to firebase
2. Delete login
3. Dismiss the old database and connect to new one
4. Change one of the attribute's name in "Call" column (connected -> status)

### The project structure
~~v1: https://drive.google.com/open?id=1D18uljAF7XkxEM07RGzWRi6p-k5EvtPF <br/>~~
v2: https://drive.google.com/open?id=15VLLEkFVJ5Sv7U4q3z4RIreH8d5ToitF

### The database(Firebase) structure
https://drive.google.com/open?id=1nFh5k84dQRbj-keIq6r5Owb1NuiLIMN0

### C3 model
Level1-Context: https://drive.google.com/open?id=1opFrW2VzLgrP2Wwq_U60mz8-0NJG38eu <br/>
Level2-Container:  https://drive.google.com/open?id=1yy_SUGoozplRmILrQbpsbLRcJx4EX-mA <br/>
Level3-Component: https://drive.google.com/open?id=1Lev03iW1ZhSttqvD0X7UnNBlyJH3JhgU
