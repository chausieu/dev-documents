# 4G LTE Modem Installation Guide

Follow the steps below to configure the AMIT LTE modem with your SIM card

1. Determine if your unit comes with an external SIM slot
    a. If yes, go to section 1.0 on how to configure the modem with an EXTERNAL SIM slot
    b. If no, go to section 2. 0 on how to configure the modem with an INTERNAL SIM slot
2. To find the modem’s IMEI number, go to section 3.
3. See attached PDF file for the complete AMIT user’s manual

## 1.0 SIM Card Installation For External SIM Slot

1. Check to determine if the unit comes with an EXTERNAL SIM slot
2. If an external SIM slot is present, you will need to configure the LTE modem for external SIM
    slot usage
       a. Power up the unit and boot into the OS
       b. From a browser, go to 172.16.0.1 and login as admin/admin
![image](https://github.com/user-attachments/assets/91eba5db-e69a-4f18-80a0-0a36b5e70985)

```
c. It will prompt you to change the default admin password. Note the new password
requirement below:
```

206 - 0204 - 000 Revision IR


206 - 0204 - 000 Revision IR

d. To configure the SIM slot to external, go to Setup / Network / Cellular; change SIM Select to
External and click on SAVE at the bottom:

```
e. Power off the unit and DISCONNECT THE POWER CORD
f. Locate the SIM slot on the unit and insert the SIM card
g. Reconnect the power cord and power on the unit
```

206 - 0204 - 000 Revision IR

## 2 .0 SIM Card Installation For Internal SIM Slot

1. If your unit does not come with an external SIM slot, you will need to install the SIM card
    internally to the modem
2. Consult the user’s manual on how to open up the unit to get access to the LTE modem
3. Locate AMIT modem and the 1x screw; note, there may be 2x screw on some unit
4. Carefully lift up the modem to detach it from the bottom mPCIe carrier board:
5. The modem requires a nano SIM as shown below:


206 - 0204 - 000 Revision IR

6. The SIM slot is located at the bottom of the modem:
7. Note the alignment of the notch on the SIM card into the SIM slot during installation
8. Re-install the modem back to the mPCIe carrier board and re-install the screw(s)
9. Close up the unit


206 - 0204 - 000 Revision IR

## 3 .0 IMEI Number

1. Some carriers may require the modem’s IMEI number to be associated with the SIM card’s
    number
2. To find the modem’s IMEI number, login via the webGUI and go to Status / Cellular / Modem:


206 - 0204 - 000 Revision IR

## 4 .0 Appendix

1. This module does NOT support fail-over with multiple SIM; only one SIM could be supported at
    a time
2. eSIM is NOT supported
3. GPS is supported, but will require an additional external GPS antenna to enable it


