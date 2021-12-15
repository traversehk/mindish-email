# Project
Develop email templates for mindish team.
Templates use MJML as responsive email framework.

## Required MJML Compilation Tool
1. [MJML Playground](https://mjml.io/try-it-live/)
2. Or, [MJML App](https://mjmlio.github.io/mjml-app/)
3. Mindbody > Manager Tools > Auto Emails

## Steps
1. Open MJML Compilation tool
2. Open Mindbody > Manager Tools > Auto Emails
3. Copy all the MJML codes from the [email templates](https://github.com/traverseworks/mindish-email) to the MJML Compilation Tool. The email layout should appear in the preview panel
4. Find and Replace all `{{variable}}`. Do not edit anything else.
5. To create a new paragraph. insert `<br>` to create newline.
6. To inject Mindbody Replace Phrase, you can first find the list of the Replace Phrase from the Mindbody > Manager Tools > Auto Emails, and insert the phrase into the content
7. !!IMPORTANT - for every replace phrase, you must replace the `<` to `&lt;` and `>` to `&gt;`
for example, to inject `<CLIENTADDRESS>`, you should put `&lt;CLIENTADDRESS&gt;`
7. Click `View HTML` Copy HTML on the top-right column
8. In Mindbody > Manager Tools > Auto Emails, click `HTML` in the email editor. Replace everything by pasting the HTML copied in step7. Click "Update"
9. Now it should be good to go.

## Template Screenshot
#### Template 1
![Template 1](https://github.com/traverseworks/mindish-email/blob/main/screenshot/template-1-desktop.jpg)
#### Template 2
![Template 1](https://github.com/traverseworks/mindish-email/blob/main/screenshot/template-2-desktop.jpg)
#### Template 3
![Template 1](https://github.com/traverseworks/mindish-email/blob/main/screenshot/template-3-desktop.jpg)
#### Template 4
![Template 1](https://github.com/traverseworks/mindish-email/blob/main/screenshot/template-4-desktop.jpg)
#### Template 5
![Template 1](https://github.com/traverseworks/mindish-email/blob/main/screenshot/template-5-desktop.jpg)
#### Template 6
![Template 1](https://github.com/traverseworks/mindish-email/blob/main/screenshot/template-6-desktop.jpg)
#### Template 7
![Template 1](https://github.com/traverseworks/mindish-email/blob/main/screenshot/template-7-desktop.jpg)
#### Template 8
![Template 1](https://github.com/traverseworks/mindish-email/blob/main/screenshot/template-8-desktop.jpg)
