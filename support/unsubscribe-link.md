---
description: >-
  Adding an unsubscribe link lets your recipients opt out of your emails, thus
  reducing the risk of being flagged as spam, and to have a cleaner mailing
  list.
---

# Unsubscribe link

### How to include an unsubscribe link?

Please note that the 2 methods will make your email compliant with the "One Click Unsubscribe" that is recommended by [the latest guideline for bulk senders](https://blog.google/products/gmail/gmail-security-authentication-spam-protection/).

There are 2 ways to include an unsubscribe link in your template with different advantages :&#x20;

1. [Insert the standardized unsubscribe complete footer](unsubscribe-link.md#insert-the-standardized-unsubscribe-footer) - takes a second, and looks very standard
2. [Insert an unsubscribe link](unsubscribe-link.md#insert-an-unsubscribe-link) - more customizable

### How would it look for my recipients?

Whenever one of your recipients clicks to unsubscribe, they will be redirected to a page like the following:

<figure><img src="../.gitbook/assets/unsubscribe ui.png" alt=""><figcaption></figcaption></figure>

Also, depending on the email provider, recipients will see the "unsubscribe link" at the top of their emails. Below is an example in Apple Mail, but all the email clients have a different look.

<figure><img src="../.gitbook/assets/unsubscribe one click.png" alt="one click unsubscribe overview in Apple mail"><figcaption><p>This is how one-click unsubscribe will look to your recipients</p></figcaption></figure>

{% hint style="info" %}
The "One click Unsubscribe" button is not always visible, Email clients have some intelligence and they don't always display the link.&#x20;

It is very likely that if you send a test email to one of your other inboxes, it won't appear because the email client "knows" that you are regularly exchanging emails with this sender.
{% endhint %}

### How would it look to me?

When one of your recipients unsubscribes, you will know it through the tracking status of your campaign :&#x20;

<figure><img src="../.gitbook/assets/tracking unsubscribe.png" alt=""><figcaption></figcaption></figure>

### Insert the standardized unsubscribe footer :

1. From the template editor, click on the  "Unsubscribe footer" icon 🔕.&#x20;
2. Click on the "Insert Unsubscribe footer" button and you are done.

<div>

<figure><img src="../.gitbook/assets/insert footer.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src="../.gitbook/assets/unsubscribe footer.png" alt=""><figcaption></figcaption></figure>

</div>

### Insert an unsubscribe link

To add an unsubscribe link, you will need to insert the unsubscribe variable as shown below. It will be replaced by a special link that Mail Merge for Gmail uses to handle unsubscribes.&#x20;

Here's how to do it:&#x20;

1. In Mail Merge for Gmail, open your template or create a new one.
2. In the editor, add the following text "_Click here to unsubscribe_" (or any other message of your choice)
3. Select the text then click on **Insert/Edit link** 🔗
4. In the "Insert/Edit link" popup, select "Unsubscribe" in the dropdown "Link List"
5. Click "Save"

<div>

<figure><img src="../.gitbook/assets/insert link.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src="../.gitbook/assets/unsubscribe link.png" alt=""><figcaption></figcaption></figure>

</div>



When sending your emails, Mail Merge for Gmail will automatically convert the special variable with a unique unsubscribe link letting each of your contact opting-out easily, **so be careful to not change the URL by yourself.**

Please not than in the template editor, the unsubscribe link is not active.
