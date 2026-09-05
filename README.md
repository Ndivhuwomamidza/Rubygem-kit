Rubygem Kit

Rubygem Kit is a mobile-friendly Progressive Web App (PWA) built with Dreamspace to help creators automate RubyGem release workflows, monitor CI/CD activity, and track subscription conversions using Google Analytics.

Features

RubyGem release workflow automation
GitHub Actions CI/CD integration
RubyGems publishing support
PayPal subscription redirect tracking
Google Analytics 4 integration
Installable PWA (desktop + mobile)
Offline-ready experience
Mobile-first UI
Dreamspace analytics compatible
Tech Stack
Dreamspace
React
GitHub Actions
RubyGems
Google Analytics 4
PayPal
Progressive Web App (PWA)
Installation
Clone the repository:

git clone https://github.com/Ndivhuwomamidza/rubyGem kit.git
Navigate into the project:

cd YOUR_REPOSITORY
Install dependencies:

bundle install
GitHub Actions Workflow
The project uses GitHub Actions to:

Build Ruby gems
Publish packages to GitHub Packages
Publish gems to RubyGems.org
Ensure the following GitHub Secrets are configured:

Secret	Description
RUBYGEMS_AUTH_TOKEN	RubyGems API key
GITHUB_TOKEN	Automatically provided by GitHub
Ruby Version
Recommended Ruby version:

2.6.10
Workflow recommendation:

runs-on: ubuntu-latest
uses: ruby/setup-ruby@v1
Google Analytics
GA4 tracking is enabled for:

Page views
SPA route changes
PayPal subscription redirects
PWA interactions
Measurement ID:

G-JG3HZB88WQ
Progressive Web App
Rubygem Kit can be installed on:

Android
iPhone/iPad
Desktop browsers
Features include:

Install button
Offline shell
App manifest
Service worker
Deployment
Deployment is handled through Dreamspace publishing tools and GitHub Actions workflows.

Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss your ideas.

License
MIT License

Author

Created by Ndivhuwo Justice using Dreamspace.
