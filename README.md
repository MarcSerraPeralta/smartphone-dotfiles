# smartphone-dotfiles

Here is a list of the steps that I follow to set up my smartphone

## 1. Remove unwanted apps that come preinstalled

Delete or disable all the apps that are not in the following list:
- Gallery
- Phone
- Messages
- Contacts
- Camera
- Settings
- Play Store
- Calculator
- FM Radio
- Recorder
- Google Drive
- Gmail
- Google Maps

To fully remove the apps, go to Settings > Apps > "Disable" or "Uninstall" (sometimes this is not the case when deleting them from the app icons in the home screen). 

## 2. Install replacements for removed apps

- Material Files <- File Explorer
- Google Lens <- Scanner
- Finamp <- Music (*I do not download music directly to my phone*)
- Firefox <- Google Chrome
- Firefox youtube.com (+ ad blocker) <- Youtube
- Google Keep <- Notes
- Clock (https://github.com/BlackyHawky/Clock) <- default Clock

For Clock, load the saved configuration from my Drive: Settings > Backup & Restore > Restore

## 3. Setting up Firefox

Install the following extensions:
- uBlock Origin
- Dark reader
- Control Panel for YouTube
- Sponsorblock

Set the following configuration:
- Set as default browser (enable)
- Homepage > disable everything on the homepage
- Customize > Address bar location: bottom
- AI controls > disable page summaries and voice search
- In a new tab, click on the three dots > Change Wallpaper > select the black one

## 4. Setting up Aegis (2FA)

1. Install Aegis
2. Import backup: Settings > Import & Export > Import from file > Aegis
3. Set backup location: Settings > Backups > Backup location: a directory in Google Drive
4. Enable backup: Settings > Backups > enable Automatically back up the vault
5. Install icons: Settings > Icon packs > select the file downloaded from https://github.com/aegis-icons/aegis-icons
6. Enable fingerprint: Settings > Security > enable Biometric unlock

## 5. Install apps for my server

- Tailscale: requires Google account
- Immich: requires Tailscale, username+password
- Finamp: requires Tailscale, username+password
- ConnectBot: does not require anything
- Moonlight: ...
- Tapo: ...
- LocalSend: does not require anything
- Element Classic: ...
- CSV file viewer: does not require anything

## 6. Install Cl@ve and DigID (identity apps for Spain and Netherlands)

- Cl@ve: requires DNI, DNI expiry date, and SMS confirmation
- DigID: requires previous device or username+password (which I do not remember?)

Set the fingerprint for DigID when prompted.

## 7. Install social media apps

- WhatsApp: requires SIM for phone number
- Instagram: requires password
- Bereal: requires SMS confirmation
- LinkedIn: requires Google account
- Discord: requires username+password and mail confirmation

For Instagram, set a maximum app time of 15 minutes in Settings > Digital Wellbeing and parental controls

For LinkedIn, disable a lot of the notifications in Settings > Notifications and disable all the ad information in Settings > Advertising data.

## 8. Install banking apps

- Imagin: requires username+password, and previous device
- ABN AMRO: requires e-identifier, username+password
- Tikkie: requires SMS confirmation, Dutch IBAN number, full name
- Wallet: requires Google account (and adding the card information)

## 9. Install healthcare apps

- La Meva Salut: requires idCAT Mobil

## 10. Install public transport apps

- T-mobilitat: does not require anything
- NS: requires username+password

For NS, go to Mijn NS > click on OV-chipkaart > Notifications > enable check-in and check-out

## 11. Install international travel apps

- Vueling: requires username+password
- Transavia: requires username+password
- been: requires Google account

## 12. Install shopping apps

- Jumbo: requires username+password
- Albert Heijn: requires username+password and SMS confirmation
- Praxis: requires username+password
- Marktplaats: requires Google account

## 13. Install fitness apps

- Wikiloc: requires username+password
- Strava: requires a Google account

## 14. Install weather apps

- Buienalarm: does not require anything
- Buienradar: does not require anything

## 15. Install mobile operator apps

- simyo: requires username+password
- MyLebara: requires username+password

## 16. Install work apps

- Outlook: requires username+password and 2FA verification
- eduVPN: requires username+password and 2FA verification
- GitHub: requires username+password and 2FA verification

## 17. Install house apps

- DUWO App: requires username+password
- tricount: requires name+email and mail confirmation

For DUWO App, enable biometric verification. 

For tricount, set the correct notification settings in Profile > Preferences > Notifications

## 18. Set up phone configuration

In Settings:

1. Notifications & Control centre > Control centre style > select old style
2. Notifications & Control centre > Notifications > disable notifications from unwanted apps
3. Notifications & Control centre > Lock screen > Format > Show notifications but hide content
4. Sound & vibration > Additional settings > disable play sound when locking device
5. Privacy > disable Show passwords (display characters briefly as you type)

Set up the wallpaper using the images from Papra. 
