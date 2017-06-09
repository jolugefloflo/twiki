<!-- TITLE: TCE Company TWIKI Home -->
<!-- SUBTITLE: A comprenhensive Knowledge Base for Twilio Functions -->
![Wiki.js](/uploads/white-background-300-x-139-1.png "White Background 300 X 139 1"){.pagelogo}
# Introduction

**This is the Official Repository** of TCE Company's Twilio Resource Kit or **TRK** where all Procedures, Code Samples and **Testing Functions** are being allocated for all Collaborators to use and research.

> **GIT Repository**
> All the resources contained here, are being updated and backed on a [Github](www.github.com) container.
> 

# Best Practices
**Edits** In order to modify any content on this Twiki, you must be a member of admin users (

**Code References**
All the code references will be displayed with the following format:

```bash
# exports.handler = function(context, event, callback)
{
	let twiml = new Twilio.twiml.MessagingResponse();
	twiml.message("Tank you for reaching us, your request is being processed");
	callback(null, twiml);
};
```


-----

# Files
**Sandard** files can be uploaded

>[Diagnose Result During Failure 3 10 2017](/uploads/assets/diagnose-result-during-failure-3-10-2017.txt "Diagnose Result During Failure 3 10 2017")
>
>[Managed Services Data Sheet](/uploads/assets/managed-services-data-sheet.pdf "Managed Services Data Sheet")
>
>[Amigo Help Desk Report](/uploads/assets/amigo-help-desk-report.xlsx "Amigo Help Desk Report")

-----

# Tables
**Tables** can also be inserted on a page>

| Property            | Required | Description                                                                                                                          |   Default Value  |
|---------------------|:--------:|--------------------------------------------------------------------------------------------------------------------------------------|:----------------:|
| **title**           | yes | The title of the website. Displayed in the navigation bar. | Wiki |
| **host**            | yes | The full hostname of the site, as accessed by the user. Do not add a trailing slash. | http://localhost |
| **port**            | no  | The port on which the server should listen to. You can also use the environment variable process.env.PORT by omitting this property. | 80 |
| **paths.repo**      | yes | The path (absolute or relative to server.js) to the folder where markdown content will be synchronized with the Git repository. Make sure this folder has the necessary write permissions. Note that this folder will contain all uploads (images, documents, etc.), so make sure to allow enough disk space depending on your usage. | ./repo |
| **paths.data**      | yes | The path (absolute or relative to server.js) to the folder where temporary data will be stored (cache, thumbnails, search indexes, etc.). Make sure this folder has the necessary write permissions. | ./data |
| **lang**            | no  | The default language to use for the site UI. Possible values: `en`, `de`, `es`, `fr`, `ko`, `pt` or `ru` | en |
