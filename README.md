# SAMTL (Sterling Asset Management And Trustees Limited) - Static Site

A pre-built static website for SAMTL, configured for deployment on DigitalOcean App Platform.

## Deploying the App

Click this button to deploy the app to the DigitalOcean App Platform. If you are not logged in, you will be prompted to log in with your DigitalOcean account.

[![Deploy to DigitalOcean](https://www.deploytodo.com/do-btn-blue.svg)](https://cloud.digitalocean.com/apps/new?repo=https://github.com/digitalocean/sample-html/tree/samtl-static-site)

### Requirements

* A DigitalOcean account. Sign up at https://cloud.digitalocean.com/registrations/new if you don't have one.

### Manual Deployment

1. Fork this repository to your own GitHub account.
2. Visit https://cloud.digitalocean.com/apps and click **Create App**.
3. Select **GitHub**, choose your forked repository, and select the `samtl-static-site` branch.
4. App Platform will detect it as a static site and deploy it automatically.
5. Once the build completes, click the **Live App** link to view your site.

### SPA Routing

This is a single-page application (React). The `catchall_document` is set to `index.html` in the App Platform config, so all routes are handled client-side.

### Making Changes

Push changes to the `samtl-static-site` branch and App Platform will automatically re-deploy with zero downtime.

## Deleting the App

1. Visit https://cloud.digitalocean.com/apps.
2. Navigate to the SAMTL app.
3. In the **Settings** tab, click **Destroy**.
