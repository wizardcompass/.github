# Wizard Compass

## Market Intelligence for the Digital Economy

Wizard Compass is a data intelligence organization dedicated to mapping the modern web. We develop advanced crawlers and analysis tools that transform raw web data into structured business insights, helping entrepreneurs, developers, and researchers understand digital trends, technology stacks, and market positioning.

---

## Meet WizardCompassBot

**WizardCompassBot** is our web indexing and `intelligence gathering` agent. It systematically browses the web to identify technologies, analyze brand assets, and categorize digital businesses (SaaS, Agencies, Directories, etc.).

### **1. Who is WizardCompassBot?**

WizardCompassBot is an "Intelligence Gatherer." Unlike general search engines that index content for keywords, our bot analyzes the **structural and technological DNA** of a website. We look at:

- **Technology Stacks:** Frameworks (Laravel, Next.js), CMSs, and analytics tools.
- **Brand Assets:** Typography, color palettes, and semantic structure.
- **Market Category:** Identifying if a site is a SaaS, e-commerce store, agency, or digital product.
    

### **2. Technical Specifications**

If you see our bot in your logs, it will identify itself with the following signature:

**User-Agent String:**

```
Mozilla/5.0 (compatible; WizardCompassBot/1.0; +https://github.com/wizardcompass/)
```

**Behavior & Politeness:**

- **Respectful:** We strictly adhere to `robots.txt` rules (both standard and wildcards).
- **Low Impact:** Our crawler operates at a low request rate to ensure no impact on your server performance.
- **Non-Intrusive:** We do not fill out forms, attempt logins, or access private data. We only analyze public-facing HTML, CSS, and manifest files.
    

### **3. Why is it crawling my site?**

We are likely crawling your site because:

1. Your domain was identified as a relevant entity in a specific market sector (e.g., Tech SaaS, Open Source).
2. A link to your site was found on a partner directory or public repository.
3. We are updating our database of web technologies to track the adoption of new frameworks or tools.
    
**Benefit to you:**
1.  **Market Visibility:** Being indexed ensures your business is correctly categorized in our market intelligence datasets, helping researchers and partners discover your tools.
2.  **Free Technical Intelligence:** We operate on a value-exchange model. If we crawl your site, you are eligible to receive the raw technical, accessibility, and performance data we collected—completely free. See [**Data Access & Transparency**](#data-access--transparency) below for details.

### **4. How to Control WizardCompassBot**

We believe in the open web but respect your right to privacy.

**To Block Us:** Add the following lines to your `robots.txt` file. We check this file before every single session.

```
User-agent: WizardCompassBot
Disallow: /
```

**To Verify Us:** WizardCompassBot will always present the User-Agent string listed above. Any bot claiming to be us without a matching signature (or originating from suspicious IP ranges that behave abusively) is likely an imposter.

---

## Open Source & Research

While our core indexing engine is proprietary, we are committed to contributing back to the ecosystem. We maintain open-source definitions for technology fingerprinting and publish research on web standards adoption.

- **GitHub:** [github.com/wizardcompass](https://github.com/wizardcompass)
- **Website:** [wizardcompass.com](https://wizardcompass.com)

## Data Access & Transparency

We believe that the data we collect about the web should be accessible to the people who build it. If WizardCompassBot has indexed your property, you are entitled to access the raw intelligence we have gathered at no cost.

**What we share with Site Owners:**
You may request a full export of the raw JSON data we hold regarding your domain, which often includes:
* **Technology Fingerprint:** Detailed breakdown of detected frameworks, CMS, and analytics stacks.
* **Accessibility Report:** Severity-based contrast and CVD (Color Vision Deficiency) analysis.
* **Performance Metrics:** Font loading strategies and resource optimization opportunities.

**How to Request Your Data:**
Email bot@wizardcompass.com with the subject line `Data Request: [Your Domain]`.

*Note: To protect the privacy of your infrastructure data, we require domain ownership verification (typically via a simple DNS TXT record or an email sent from the domain itself) before releasing raw technical reports.*

## Engineering & Open Source DNA

Wizard Compass is built by engineers who actively contribute to the standards that power the web. We don't just consume web data; we build the tools that measure and optimize it.

**Core Maintainer:** [Leonardo Poletto](https://github.com/leopoletto)

Our scraping philosophy and architecture are grounded in our maintainer's contributions to the open-source ecosystem, including:

- **Google Robots.txt Parser and Matcher Library**: Contributing documentation and CLI improvements to Google's official C++ robots.txt parser to ensure standardized bot compliance.
- **Robots Txt Parser**: Authors of [Robots TXT Parser
](https://github.com/leopoletto/robots-txt-parser). A comprehensive PHP package for parsing and analyzing robots.txt files. This library is designed to help you understand the structure and content of robots.txt files, including support for X-Robots-Tag HTTP headers and meta tags from HTML pages.
- **Lighthouse**: Contributions to the industry-standard tool for web quality and performance auditing.
- **Privacy & Compliance**: Authors of the [Chrome Privacy Extension](https://github.com/leopoletto/chrome-privacy-extension) and privacy-focused technology parser [Wappalyzer Privacy Technology Scraper](https://github.com/leopoletto/wappalyzer-privacy-report).
- **Font Performance**: Creators of [Font Self-Hosting Preparation Script
](https://github.com/leopoletto/font-self-host), [FontLint Python Scripts
](https://github.com/leopoletto/font-lint-python-scripts) and [Font Lint](https://fontlint.com/) (coming soon), advanced tooling for optimizing web typography and reducing digital footprints.

---

### **Contact**

For urgent inquiries regarding our crawler or to report an issue, please open an issue in our [Public Tracker](https://github.com/wizardcompass/.github/issues) or email us at bot@wizardcompass.com.
