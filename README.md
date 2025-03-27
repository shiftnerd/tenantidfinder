Tenant ID Finder Tool 🚀

A lightweight, web-based tool for quickly retrieving Microsoft 365 tenant IDs along with essential DNS records such as MX, Autodiscover, SPF, and DMARC. It supports both single domain lookups and bulk processing, making it an ideal utility for administrators and IT pros. ✨

⸻

Features 🌟
	•	Microsoft 365 Tenant ID Lookup
Retrieve tenant IDs by querying Microsoft’s OpenID configuration endpoint.
	•	DNS Records Check
	•	MX Records: Verify mail exchange configurations 📧
	•	Autodiscover: Determine if the domain is set up for Office 365 or on-premises Exchange 🔍
	•	SPF Records: Validate SPF entries in TXT records 🔐
	•	DMARC Records: Assess DMARC configurations for enhanced email security 🛡️
	•	Bulk Lookup Support
Process multiple domains at once and view individual results 🔢
	•	CSV Export
Export your findings into a CSV file for easy analysis 📊

⸻

How It Works 💡

This tool runs entirely on the client side, ensuring your domain information is neither stored nor transmitted to external servers. It leverages:
	•	Microsoft’s OpenID Configuration Endpoint
Extracts the tenant ID from the issuer URL for a given Microsoft 365 domain.
	•	Cloudflare DNS over HTTPS (DoH) API
Retrieves various DNS records such as MX, SPF, and DMARC.
	•	Modern Web Technologies
Crafted with HTML, Tailwind CSS, and vanilla JavaScript, enhanced with ClipboardJS for a seamless experience.

⸻

Usage ⚙️
	1.	Single Domain Lookup
	•	Enter a domain name (e.g., example.com) in the input field.
	•	Click the Check button to fetch the tenant ID and DNS records.
	2.	Bulk Lookup
	•	Input multiple domains separated by commas in the provided textarea.
	•	Click Process Domain List to retrieve results for each domain.
	•	Use the Export to CSV button to download a CSV report of your findings.

⸻

Contributing 🤝

Contributions are welcome! If you have ideas, improvements, or bug fixes:
	•	Open an issue to discuss your thoughts.
	•	Fork the repository and submit a pull request.

⸻

License 📝

This project is licensed under the MIT License.

⸻

Disclaimer ⚠️

This tool performs all operations directly in your browser and does not store or share any data you enter. Always verify the results using your own methods.
