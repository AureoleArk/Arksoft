# DB: Arksoft
## Table: user

### id
* MySQL auto increment id

### name
* username (Max 16)

### hash
* user password hash (crypt)

### fast ip
* user register ip

### last ip
* last login ip

### type
* user account type [0.Site account, 1.Google]
 
### social_id
* social login id (Default.'NO_SOCIAL')

### otp
* Two Factor Authentication [0.off, 1.on]

### otp_secret
* Two Factor Authentication Secret (Default.'NO_OTP')

### status
* Account status [0.disabled, 1.enabled, 2.warn, 3.banned]

### lastpage
* User last my page [0.CorkBoard, 1.ArkShort, 2.ArkLive]

### parm
* User permission [0.normal, 1.donater, 2.moderator, 3.developer]

