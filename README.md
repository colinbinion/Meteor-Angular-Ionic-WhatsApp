# Meteor-Angular-Ionic-WhatsApp


If you would like to test the verification with a real phone number, accouts-phone provides an easy access for twilio's API, for more information see accounts-phone's repo.

For debugging purposes if you'd like to add admin phone numbers and mater verification codes which will always pass the verification stage, you may add a settings.json file at the root folder with the following fields:

{
  "ACCOUNTS_PHONE": {
    "ADMIN_NUMBERS": ["123456789", "987654321"],
    "MASTER_CODE": "1234"
  }
}
