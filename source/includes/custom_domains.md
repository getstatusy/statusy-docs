# Custom Domain

You can have a custom domain name point to your public Status page. In order to do so, you will need to create a CNAME record.

1. Log into whichever provider you use to manage DNS for your website.
2. Add a new CNAME record to point to your public status page. For example if your statusy subdomain is `acme.statusy.co` and you want your custom url to be `status.acme.com` you would add the following CNAME record.

<code>
CNAME   status.acme.com     acme.statusy.co
</code>

After DNS propagates (which may take up to 48 hours) you will be able to navigate to status.acme.com and see your public status page.
