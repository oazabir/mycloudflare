# Intro
A cloudflare like DNS manager, SSL proxy, Email Sending, Caching, and so on...

Developers have a frequent need to host dev/internal sites and temporary sites on a domain, and sometimes need to get SSL certificates for those sites. Having to go through the DNS provider’s console, setting up DNS records there and also dealing with SSL certificates for development or internal sites is a challenge. Moreover, configuring DNS for email sending so that emails aren’t rejected, is another challenge. 
We need a tool that a) quickly allows us to create custom subdomains under a root domain for hosting development/internal/temporary websites, b) have SSL proxy done automatically, c) smtp server readily available to test email sending, and d) pop server to receive emails and test tools/code that acts against incoming email.
