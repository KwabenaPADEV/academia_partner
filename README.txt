ACADEMIA PARTNER WEBSITE UPDATE

1. Rename academia-partner-updated.html to index.html before uploading if this is your homepage.
2. Keep your existing kobby.png image in the same folder as index.html (the page references kobby.png).
3. The EmailJS browser SDK is loaded in the page head. The enquiry form sends these template variables:
   from_name, from_email, reply_to, institution, programme, service, topic, deadline, message.
4. In EmailJS template template_48gk3uc, set To Email to academiapartner05@gmail.com and Reply-To to {{from_email}} (or {{reply_to}}).
5. Test the form on your deployed website. A successful browser response means EmailJS accepted the send request; also check Inbox and Spam.

The EmailJS public key is intended for browser use. Do not place a private key in this file.
