---
title: Installing a GitHub App in your organization
intro: 'You can install apps from {% data variables.product.prodname_marketplace %} to use in your organization.'
redirect_from:
  - /articles/installing-an-app-in-your-organization
  - /github/customizing-your-github-workflow/installing-an-app-in-your-organization
  - /github/customizing-your-github-workflow/purchasing-and-installing-apps-in-github-marketplace/installing-an-app-in-your-organization
  - /get-started/customizing-your-github-workflow/purchasing-and-installing-apps-in-github-marketplace/installing-an-app-in-your-organization
  - /apps/using-github-apps/installing-an-app-in-your-organization
versions:
  fpt: '*'
  ghec: '*'
shortTitle: Install app organization
---
{% data reusables.marketplace.marketplace-apps-only %}

{% data reusables.marketplace.marketplace-org-perms %}

If you choose a paid plan, you'll pay for your app subscription on your organization's current billing date using your organization's existing payment method.

{% data reusables.marketplace.free-trials %}

For more information about installing an {% data variables.product.prodname_oauth_app %}, see "[AUTOTITLE](/apps/oauth-apps/using-oauth-apps/installing-an-oauth-app-in-your-organization)."

## Installing a {% data variables.product.prodname_github_app %} in your organization

{% data reusables.marketplace.visit-marketplace %}
{% data reusables.marketplace.browse-to-app %}
{% data reusables.marketplace.choose-plan %}
{% data reusables.marketplace.install-buy %}
{% data reusables.marketplace.confirm-install-account-org %}
{% data reusables.marketplace.add-payment-method-org %}
{% data reusables.marketplace.complete-order-begin-installation %}
1. If the app requires access to repositories, select **All repositories** or **Only select repositories**.
{% data reusables.marketplace.select-installation-repos %}
{% data reusables.marketplace.review-app-perms-install %}

## Further reading

- "[AUTOTITLE](/billing/managing-your-github-billing-settings/adding-or-editing-a-payment-method)"
- "[AUTOTITLE](/apps/using-github-apps/installing-an-app-in-your-personal-account)"
