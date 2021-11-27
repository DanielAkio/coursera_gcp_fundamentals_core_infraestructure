# There are four ways to interact with GCP

- Google Cloud Platform Console
    - Web-based administrative user interface
    - Manage and create projects
    - Access to Google Cloud Platform APIs
    - Offers access to Cloud Shell
        - A temporary virtual machine with Google SDK preinstalled

- Cloud Shell and Cloud SDK
    - Command-line tools for Cloud Platform products and services
        - gcloud, gsutil (Cloud Storage), bq (Big Query)
    - Available via Cloud Shell, own computer, docker image

- Cloud Console Mobile App
    - For iOs and Android
    - Manage virtual machines and database instances
    - Manage apps in Goole App Engine
    - Mange your billing
    - Visualize your pojects with a customizable dashboard

- REST-based API
    - Programmatic access to products and services
        - Typically use JSON as an interchange format
        - Use OAuth 2.0 for authntication and authorization
    - Enabled through the Google Cloud Platform Console
    - Most APIs include daily quotas and rates (limits) that can be raised by request
        - Important to pln ahead to maanage your required capacity
    - Experiment with APIs Explorer

# Use APIs Explorer to help you write your code

- The APIs Explorer is an interactive tool that lets you easily try Google APIs using a browser

- With the APIs Explorer, you can:
    - Browse quicly through available APIs and versions
    - See methods available for each API and what parameters they supoport along with inline documentation
    - Execute requests for any method and see responses in real time
    - Easily make authenticated and authorized API calls

# Use client libraries to control GCP resources from within your code

- Cloud Client Libraries
    - Community-owned, hand-crafted client libraries

- Google API Client Libraries
    - Open source, generated
    - Support various languages
        - Java
        - Python
        - JavaScript
        - PHPm .NET
        - Go
        - Node.js
        - Ruby
        - Objective-C
        - Dart
