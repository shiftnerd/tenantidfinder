Tenant ID Finder Tool

A lightweight, web-based tool for quickly retrieving Microsoft 365 tenant IDs along with essential DNS records such as MX, Autodiscover, SPF, and DMARC. It supports both single domain lookups and bulk processing, making it an ideal utility for administrators and IT professionals.

Features
	•	Microsoft 365 Tenant ID Lookup
Retrieve tenant IDs by querying Microsoft’s OpenID configuration endpoint.
	•	DNS Records Check
	•	MX Records: Verify mail exchange configurations.
	•	Autodiscover: Determine if the domain is set up for Office 365 or on-premises Exchange.
	•	SPF Records: Check for valid SPF entries in TXT records.
	•	DMARC Records: Assess DMARC configurations for domain email security.
	•	Bulk Lookup Support
Process multiple domains in one go and display results individually.
	•	CSV Export
Easily export results into a CSV file for further analysis.

How It Works

This tool runs entirely on the client side, ensuring your domain information is neither stored nor transmitted to external servers. It uses:
	•	Microsoft’s OpenID Configuration Endpoint
Extracts the tenant ID from the issuer URL for a given Microsoft 365 domain.
	•	Cloudflare DNS over HTTPS (DoH) API
Retrieves various DNS records such as MX, SPF, and DMARC.
	•	Modern Web Technologies
Built with HTML, Tailwind CSS, and vanilla JavaScript, along with ClipboardJS for enhanced UX.

Usage
	1.	Single Domain Lookup
	•	Enter a domain name (e.g., example.com) in the input field.
	•	Click the Check button to retrieve the tenant ID and DNS records.
	2.	Bulk Lookup
	•	Enter multiple domains separated by commas in the provided textarea.
	•	Click Process Domain List to fetch results for each domain.
	•	Use the Export to CSV button to download a CSV report of the findings.

Contributing

Contributions are welcome! If you have suggestions, improvements, or bug fixes, please:
	•	Open an issue to discuss your ideas.
	•	Fork the repository and submit a pull request.

License

This project is licensed under the MIT License.

Disclaimer

This tool performs all operations directly in your browser and does not store or share any entered data. Always verify the results using your own methods.
