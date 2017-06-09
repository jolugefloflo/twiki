<!-- TITLE: TCE Company TWIKI Home -->
<!-- SUBTITLE: A comprenhensive Knowledge Base for Twilio Functions -->
# Introduction
![White Background 300 X 139 1](/uploads/white-background-300-x-139-1.png "White Background 300 X 139 1")

**This is the Official Repository** of TCE Company's Twilio Resource Kit or **TRK** where all Procedures, Code Samples and **Testing Functions** are being allocated for all Collaborators to use and research.

> **GIT Repository**
> All the resources contained here, are being updated and backed on [Github](www.github.com) page

# Best Practices
**Edits** In order to modify any content on this Twiki, you must be a member of admin users (

**Code Conventions**
All the code references will be displayed with the following format:

```bash
# exports.handler = function(context, event, callback) {
	let twiml = new Twilio.twiml.MessagingResponse();
	twiml.message("Tank you for reaching us, your request is being processed");
	callback(null, twiml);
};
