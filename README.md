<h1>Technical Systems & Infrastructure</h1>

> 🔒 Some information has been redacted to protect confidentiality and security.

<p>
The Govsera project requires the configuration of core technical systems to connect the domain, website, and business email into a stable and functional environment. The focus is on ensuring proper domain resolution, reliable email delivery, and secure system integration across all components.
</p>

<h2>Domain & DNS Configuration</h2>

<p>
The domain is managed through GoDaddy, with DNS records configured and maintained within the Namecheap hosting environment. Key records, including A records, CNAME records, and MX records, are set and verified to ensure accurate routing between the domain and hosting services.
</p>

<p>
This configuration enables proper website loading, supports email routing, and satisfies domain verification requirements across connected platforms.
</p>

![](DNS-Records.png)
> DNS configuration showing domain routing and email authentication records.

<br>

<h2>Email Authentication (SPF, DKIM, DMARC)</h2>

<p>
Full email authentication is implemented to improve deliverability and establish sender credibility. This includes the configuration of SPF, DKIM, and DMARC records.
</p>

<ul>
<li>SPF authorizes Microsoft 365 as a valid sending source</li>
<li>DKIM is enabled and validated through published CNAME records</li>
<li>DMARC is configured to define policy and improve trust with receiving servers</li>
</ul>

<p>
These configurations help prevent spoofing, reduce the likelihood of emails being marked as spam, and support consistent delivery.
</p>

![](email-auth.png)
> Email authentication successfully validated during delivery

<br>

<h2>Microsoft 365 / Outlook Email Setup</h2>

<p>
Microsoft 365 is configured to manage business email using the custom domain. This process includes domain verification, mailbox setup, and integration between DNS records and Microsoft services.
</p>

<p>
Sender identity settings are adjusted to ensure outgoing emails reflect a consistent and professional business name.
</p>

<br>

<h2>SMTP Configuration & Email Troubleshooting</h2>

<p>
SMTP is configured to handle outbound email from the website, with additional troubleshooting required to resolve initial delivery issues.
</p>

<p>This includes:</p>

<ul>
<li>Resolving SMTP authentication errors</li>
<li>Verifying DNS propagation and record accuracy</li>
<li>Testing email headers to confirm SPF, DKIM, and DMARC pass status</li>
<li>Ensuring emails are delivered without being flagged or rejected</li>
</ul>

<p>
These steps result in a stable and reliable email delivery system.
</p>

<br>

![](SMTP-test.png)
> Email delivery validation and SMTP troubleshooting results.

<br>

<h2>Hosting Environment & SSL Configuration</h2>

<p>
The hosting environment is managed through Namecheap cPanel. Core configurations are applied to support security, performance, and compatibility.
</p>

<p>This includes:</p>

<ul>
<li>Enabling SSL to ensure secure HTTPS connections</li>
<li>Managing PHP versions for performance and system compatibility</li>
<li>Supporting overall site stability through hosting-level configuration</li>
</ul>

<br>

![](cPanel.png)
> cPanel dashboard

<br>

<h2>Professional Takeaway</h2>

<p>
A functional website depends on more than front-end development. Proper domain configuration, DNS management, email authentication, and hosting setup (along with other factors) are critical to ensuring reliability, security, and professional operation.
</p>

<p>
The result is a fully integrated system where the website, domain, and email infrastructure operate together without conflict or delivery issues.
</p>

[Return to Home](https://github.com/JorgeFSantillan)
