# MailChimp
* pass your sales leads and contacts to MailChimp
* Lead creation allows MailChimp to create Salesforce leads from your MailChimp subscribers who aren't already Salesforce leads or contacts.
* ALLOW MAILCHIMP TO CREATE LEADS IN SALESFORCE - Enabling this feature will allow MailChimp to create new leads in Salesforce for email addresses that don't match existing leads or contacts.
* TURN ON/OFF DATA SYNC - Enabling the data sync feature will schedule a series of batch tasks. The data sync updates your MailChimp subscriber fields with the corresponding contact/lead field data each hour, and it updates the Salesforce contacts/leads with the MailChimp subscriber campaign activity each night.
* REFRESH ALL LISTS - The "Refresh All Lists" button updates all of the list field data. This button updates Salesforce with the MailChimp lists, list fields, and groups.
* MAP FIELDS - The "Map Fields" link takes you to the field mapping page for each list. You can edit the field mapping for existing list fields or create new MailChimp list fields. The field mapping settings are used to match MailChimp list fields with their corresponding contact/lead fields.

The permissions for the leads, contacts, and accounts should be set to "Public Read/Write" in order for the MailChimp for Salesforce app to work properly. In order to edit these permissions, go to Setup > Administer > Security Controls > Sharing Settings.
