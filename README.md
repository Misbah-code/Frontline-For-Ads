Front Line Advertisement --- Corporate Website & CMS
```{=html}
<p align="center">
```
`<strong>`{=html}A bilingual digital presence and lead-generation
platform for a UAE advertising company`</strong>`{=html}
```{=html}
</p>
```
```{=html}
<p align="center">
```
`<a href="https://frontline-adv.co/">`{=html}`<strong>`{=html}Visit the
live website →`</strong>`{=html}`</a>`{=html}
```{=html}
</p>
```
```{=html}
<p align="center">
```
`<img src="https://img.shields.io/badge/PHP-8.x-777BB4?logo=php&logoColor=white" alt="PHP 8" />`{=html}
`<img src="https://img.shields.io/badge/MySQL-Database-4479A1?logo=mysql&logoColor=white" alt="MySQL" />`{=html}
`<img src="https://img.shields.io/badge/HTML5-Markup-E34F26?logo=html5&logoColor=white" alt="HTML5" />`{=html}
`<img src="https://img.shields.io/badge/CSS3-Styling-1572B6?logo=css3&logoColor=white" alt="CSS3" />`{=html}
`<img src="https://img.shields.io/badge/JavaScript-Frontend-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript" />`{=html}
`<img src="https://img.shields.io/badge/Deployment-Hostinger-673DE6" alt="Hostinger deployment" />`{=html}
`<img src="https://img.shields.io/badge/Website-English%20%2B%20Arabic-success" alt="Bilingual website" />`{=html}
```{=html}
</p>
```
Front Line Advertisement is a custom-built corporate website and
content-management platform for a UAE-based advertising and
creative-services business.
The project was designed, developed, and deployed from scratch. It
combines a responsive public website with a PHP/MySQL administration
dashboard, allowing the business to present its services and selected
work while managing website content and incoming customer enquiries.
Project at a Glance
---
Item                                Details
---
Business                            Front Line Advertisement
Market                              Ajman, United Arab Emirates
Live website                        https://frontline-adv.co/
Project type                        Corporate website, CMS, and
lead-generation platform
Frontend                            HTML5, CSS3, JavaScript
Backend                             PHP 8.x
Database                            MySQL
Hosting                             Hostinger shared hosting
Languages                           English (default) and Arabic (RTL)
Delivery                            Designed, developed, and deployed
from scratch
---
1. Project Overview
The goal was to create a professional online presence that explains the
company's services, showcases its work, and makes it easy for potential
customers to request quotations or contact the business.
The website supports the company's advertising and creative-services
offering, including:
Branding and rebranding.
Printing and promotional materials.
Signage and signboards.
Corporate gifts.
Digital and social media services.
Photography and videography.
The public website is connected to a custom CMS so that key business
content can be maintained without editing website code for every routine
update.
Key objectives
Present the company and its services clearly.
Provide a consistent English and Arabic experience.
Support Arabic right-to-left (RTL) layout and content.
Showcase selected projects and portfolio work.
Convert website visits into quotation requests and enquiries.
Give administrators control over website content and incoming leads.
---
2. Public Website Features
Bilingual experience
English is the default website language.
Arabic is provided as a separate localized experience.
Arabic pages use RTL direction and layout support.
Navigation, page content, service information, and key website text
support both languages.
Language switching is available across the public website.
Main website sections
---
Section                             Purpose
---
Home                                Introduces the company, its
services, and primary calls to
action
About                               Presents company information and
business positioning
Services                            Displays the service catalogue
Service details                     Provides information about
individual services
Portfolio                           Showcases selected work and project
examples
Request a Quote                     Collects project requirements and
quotation enquiries
Contact                             Provides customer contact pathways
Customer contact and lead generation
Request-a-quote journey.
Contact and enquiry forms.
File attachment support within the quotation request workflow.
Direct phone and email contact links.
WhatsApp contact pathway.
Service-related calls to action that guide visitors toward a
quotation request.
Responsive presentation
The website uses responsive layouts intended to provide a usable
experience across desktop, tablet, and mobile screen sizes.
---
3. Custom CMS and Administration Dashboard
A custom PHP-based administration dashboard supports day-to-day website
content management and enquiry handling.
Dashboard capabilities
---
Module                              Administrative capability
---
Dashboard                           Overview of website activity and
recent quotation requests
Services                            Manage service content, bilingual
text, images, and icons
Portfolio                           Manage portfolio entries and
publication status
Clients                             Manage client information displayed
by the website
Quote Requests                      Review and update incoming
quotation enquiries
Messages                            Review contact messages received
through the website
Website Content                     Manage bilingual website text and
general settings
Company Profile PDF                 Upload or replace the company
profile PDF used by the Arabic
navigation link
Account                             Manage administrator account
details and password
Content management
English and Arabic content fields for supported website settings.
Service content management.
Service image and icon uploads.
Portfolio content management.
Client information management.
Editable website text and selected site settings.
Company profile PDF upload through the dashboard.
Enquiry management
Centralized quotation-request records.
New-enquiry visibility from the dashboard.
Quote request status management.
Contact-message records.
Access to submitted enquiry details and supported attachments.
The CMS is intended to reduce dependence on direct source-code edits for
routine website content updates.
---
4. Technical Architecture
The solution uses a server-rendered PHP application with MySQL
persistence.
``` mermaid
flowchart TD
    Visitor[Website Visitor] --> Website[Public Website]
    Website --> Pages[Home / About / Services / Portfolio]
    Website --> Leads[Quote and Contact Forms]
    Pages --> PHP[PHP Application]
    Leads --> PHP
    Admin[Administrator] --> CMS[Admin Dashboard]
    CMS --> PHP
    PHP --> DB[(MySQL Database)]
    PHP --> Uploads[Uploaded Images and Documents]
    Website --> Analytics[Google Analytics 4]
```
Technology stack
Layer                      Technology
---
Markup                     HTML5
Styling                    CSS3
Browser interactions       JavaScript
Server-side application    PHP 8.x
Database                   MySQL
Database access            PHP Data Objects (PDO)
Hosting environment        Hostinger shared hosting
Web server configuration   Apache-compatible `.htaccess` routing
Analytics                  Google Analytics 4
Application structure
The application is organized around shared public-site components,
server-side routing, reusable helper functions, database-backed content,
and a separate administration area.
Key application areas include:
``` text
Frontline Website
│
├── Public Website
│   ├── Home
│   ├── About
│   ├── Services
│   ├── Service Details
│   ├── Portfolio
│   ├── Request a Quote
│   └── Contact
│
├── Admin Dashboard
│   ├── Dashboard
│   ├── Services
│   ├── Portfolio
│   ├── Clients
│   ├── Quote Requests
│   ├── Messages
│   ├── Website Content
│   └── Account
│
├── Shared Application Components
│   ├── Configuration
│   ├── Database Connection
│   ├── Header and Footer
│   ├── Routing and URL Helpers
│   ├── Language and Translation Helpers
│   └── Form and Content Helpers
│
├── Assets
│   ├── CSS
│   ├── JavaScript
│   └── Images
│
├── Uploads
│   ├── Service Images and Icons
│   ├── Portfolio Images
│   └── Company Profile Documents
│
└── MySQL Database
    ├── Administrator Accounts
    ├── Website Settings
    ├── Services
    ├── Portfolio
    ├── Clients
    ├── Quote Requests
    └── Contact Messages
```
This is a logical overview of the application areas, not a guaranteed
file-by-file repository listing.
---
5. Database and Content Model
MySQL stores the website's managed content and customer enquiries.
The application uses database-backed records for areas such as:
Administrator accounts.
Website settings and bilingual content.
Services.
Portfolio entries.
Client information.
Quotation requests.
Contact messages.
The CMS reads and updates these records so that supported content
changes can appear on the public website.
The deployed application uses a configuration file for database
connection settings. Database credentials must be supplied through the
deployment environment and must not be committed to source control.
---
6. Deployment
The website is deployed on Hostinger shared hosting.
The production setup uses PHP and MySQL, with the public website and
administration dashboard served through the hosting environment.
Deployment outline
Configure the hosting account and domain.
Create the MySQL database and database user.
Import the supplied database schema/data using the hosting database
tools.
Configure the application's database connection settings.
Upload the public website and administration application files to
their intended document roots.
Confirm the PHP version and required PHP extensions.
Verify URL routing and `.htaccess` configuration.
Test the public pages, language switching, forms, uploads, and
dashboard access.
Confirm that production credentials and administrator access are
protected.
Environment configuration
The application contains a PHP configuration file for
environment-specific settings, including database connection details and
the website base URL.
Never commit production database credentials, administrator passwords,
private keys, or customer enquiry data to Git.
---
7. Security and Operational Considerations
The administration workflow includes authentication and password
management. Administrative forms use CSRF tokens, and passwords are
handled through PHP password hashing and verification functions.
Additional operational practices for a production deployment include:
Keep database credentials outside publicly accessible source
documentation.
Use HTTPS for all public and administrative access.
Restrict access to configuration and backup files.
Validate uploaded files by type and size.
Keep administrator passwords strong and unique.
Back up the MySQL database and uploaded media.
Review PHP and hosting logs when diagnosing errors.
Test database restoration and file recovery procedures.
A full independent penetration test or formal security certification is
not claimed by this project description.
---
8. Analytics and Website Visibility
Google Analytics 4 is configured through the public website header to
support website traffic measurement.
The shared public header also includes page metadata and language
alternate links for the English and Arabic website experiences.
Analytics configuration and search-engine metadata should be reviewed
periodically as website content and business requirements evolve.
---
9. Project Delivery Highlights
This project demonstrates end-to-end delivery across both the public
website and its supporting content-management workflow:
Translated business needs into a structured corporate website.
Designed and developed the public-facing website from scratch.
Implemented bilingual English and Arabic experiences with RTL
support.
Built reusable PHP components and database-backed content rendering.
Developed a custom CMS and administration dashboard.
Connected website forms to enquiry records and administrative
workflows.
Implemented content and media upload capabilities.
Configured the production hosting environment and deployed the
website.
Continued maintaining and enhancing the live application.
---
10. Future Enhancements
Potential areas for continued improvement include:
Expanded portfolio case studies and project detail pages.
Further CMS usability improvements.
More detailed enquiry reporting and lead analytics.
Enhanced image optimization and media management.
Automated application testing and deployment checks.
Ongoing accessibility, performance, and security reviews.
These are improvement opportunities, not claims that the features are
already implemented.
---
11. Project Links
Live website: https://frontline-adv.co/
Business: Front Line Advertisement
Market: Ajman, United Arab Emirates
---
```{=html}
<p align="center">
```
`<strong>`{=html}Front Line
Advertisement`</strong>`{=html}`<br />`{=html} A custom-built bilingual
corporate website and content-management platform.
```{=html}
</p>
```
