# Interactive mocks

Interactive UX concepts for Red Hat Hybrid Cloud Console workflows.

## Live patch status concepts

The current prototype shows live patch (kpatch) status in two Insights
Vulnerability views:

1. CVE details: which affected systems have a compatible live patch
2. System details: which CVEs on one system have a compatible live patch

Open `index.html` directly in a browser. The mock is self-contained and uses
synthetic system and vulnerability data.

Use the page switcher at the top, or click the first system name and the first
CVE ID to move between the two views. The URL fragments `#cve` and `#system`
also open each view directly.
