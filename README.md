# Add all the G Suite DNS settings into Cloudflare quickly
Very quick way to add G Suite DNS settings to your domain on Cloudflare. MX records, Text Verification, SPF, and DKIM

Over here we use Cloudflare and also G Suite a lot, we have added enough domains to G Suite to know it can be time consuming to add the DNS settings manually. So we create this little file to import them faster.

1. Download the [attached txt file](gsuite-cloudflare.txt), modify it with your unique TXT, SPF and DKIM records.
2. Login to the Cloudflare domain you want to add records to, click on DNS settings.
3. Click the Advanced Icon and drag the text file in.

That's all ;)

![Cloudflare DNS](img.png)

Inspired by https://github.com/irazasyed/dns-zone-files who has some DNZ zone files for a stack more applications/services
