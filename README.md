<<<<<<< HEAD
# Cisco-CXTM-Postman
=======
[![published](https://static.production.devnetcloud.com/codeexchange/assets/images/devnet-published.svg)](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/Cisco-CXTM-Postman)

# Cisco CXTM Postman Collection
This repo contains a [Postman](https://www.postman.com) collection and simple environment that can be used to learn and interact with Cisco's CX Test Manager (CXTM) REST API. The collection contains the REST API calls and optional queries that map to the Swagger API documentation.

## Requirements
The Postman collection and environment will need:
* Postman 8.7.0+
* CXTM 25.5.5+

## Getting Started
Once you install Postman, follow the steps below to import the collection and environment:

### Prerequisites
* If you do not already have Postman installed, you can download and install it [here](https://www.postman.com/downloads/).

### Clone Repo

1. `git clone` this repository

### Import Environment & Collections 
1. Launch Postman
2. Click `File` then click `Import` in the dropdown
3. In the Postman Import pop-up box, click `Upload Files`
4. Browse to the location where you cloned this repo
5. Shift-click both the files below to add them:
    * `Cisco-CXTM.postman_collection.json`
    * `Cisco-CXTM.postman_environment.json`

### Setup
1. In Postman, in the left navigation pane, click Environments
2. Locate and click on the `Cisco-CXTM` environment
3. Update the `cxtm_url` variable with the URL for your CXTM instance
4. Update the `cxtm_api_key` variable with your CXTM API Key
5. In the left navigation pane, click on Collections
6. Ensure you select the `Cisco-CXTM` environment (top-right corner dropdown)
7. Expand the collection titled `Cisco-CXTM`
8. Start making CXTM REST API calls

### Environment Variables
In some instances, POST methods in particular, Javascript tests have been included as part of the API request to populate environment variables. These tests will add the variables automatically to your environment variables list for use in subsequent API requests. These can be overridden in the environment settings where you updated your CXTM URL and CXTM API Key.

##### Note: In case your instance of CXTM has a self signed certificate, please make sure you disable `SSL certificate verification` in Postman's settings.
>>>>>>> 41855a3 (updates to collection)
