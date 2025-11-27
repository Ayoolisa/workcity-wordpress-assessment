# WorkCity Africa Landing Page

## Setup Instructions
1. Install XAMPP and start Apache & MySQL.  
2. Create a database for the WordPress installation via phpMyAdmin.  
3. Download WordPress and extract it to the `htdocs` folder (e.g., `htdocs/workcity-assessment`).  
4. Update `wp-config.php` with your database name, username, and password.  
5. Access the site via `http://localhost/workcity-assessment` or via your local IP on mobile.  
6. Install and activate the chosen WordPress theme.  
7. Install Elementor and required plugins for SEO, caching, and forms.  
8. Import or build page content sections: Hero, Services, Testimonials, Contact.  

## Tools & Technologies Used
- WordPress  
- Elementor Page Builder  
- XAMPP (Local development)  
- Google Analytics (setup in progress, pending live deployment)  
- Plugins for SEO, caching, and forms  

## Challenges Encountered & Resolution
- **Google Analytics Integration:** Could not fully connect because the website was hosted locally; tracking is pending live deployment or tunnel setup.  
- **Icons & Assets Loading on Mobile:** Mixed content issues when accessing the site from HTTP. Resolved by updating WordPress site URL to the local network IP and regenerating Elementor CSS.  

## Knowledge Graph / SEO Considerations
- Structured Organization and Contact schema implemented.  
- SEO optimized headings, URLs, meta titles, descriptions, and images.  
- Sitemap submitted (for future live deployment).  

## Video Walkthrough
I created a 5–10 minute video demonstrating the development process, technical decisions, SEO/schema considerations, and challenges.  
[Watch the Walkthrough](https://youtu.be/8582RlzBnVA)

**Short Description:**  
This video showcases the workflow for building the WorkCity Africa landing page, highlighting research, design, implementation using WordPress & Elementor, SEO optimizations, and challenges with analytics setup on a local environment.

## Meaningful Commit History
- Commit messages reflect workflow stages: setup, theme installation, Elementor page design, SEO configuration, troubleshooting issues.
