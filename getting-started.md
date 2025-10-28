---

copyright:
  years: 2020, 2024
lastupdated: "2024-08-08"

keywords: migration, virtual servers migration, migrating to virtual private cloud

subcollection: wanclouds-vpc-plus

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:external: target="_blank" .external}
{:pre: .pre}
{:tip: .tip}
{:important: .important}
{:table: .aria-labeledby="caption"}

# Getting started with VPC+ Cloud Migration
{: #getting-started-tutorial}

Use {{site.data.keyword.vpc-plus-migration}} to migrate your {{site.data.keyword.cloud}} classic infrastructure to {{site.data.keyword.cloud_notm}} Virtual Private Cloud (VPC).
{: shortdesc}

## Step 1. Learn more about {{site.data.keyword.vpc-plus-migration}}
{: #step-1-learn}

Before you begin migrating your classic infrastructure to VPC, learn more about {{site.data.keyword.vpc-plus-migration}} and which classic resources can be migrated. To learn more, see [About {{site.data.keyword.vpc-plus-migration}}](/docs/wanclouds-vpc-plus?topic=wanclouds-vpc-plus-about-wanclouds).

## Step 2. Plan for your migration 
{: #step-2-plan}

To get the best results from your VPC migration, spend time analyzing your classic environment and learning how the {{site.data.keyword.vpc-plus-migration}} tool handles different components of your environment. For more information, see [Planning for migration](/docs/wanclouds-vpc-plus?topic=wanclouds-vpc-plus-planning-for-migration).

## Step 3. Create an instance of {{site.data.keyword.vpc-plus-migration}} through the VPC+ Cloud Migration
{: #step-3-create}

Complete the following steps to create an instance of {{site.data.keyword.vpc-plus-migration}} through the {{site.data.keyword.cloud_notm}} catalog. 

1. Log in to the VPC+ Wanclouds Account by using your IBMid/Account credentials.
2. In the **Migrate Infrastructure section**, select IBM Cloud Classic to VPC Migration.
3. On the VPC+ **Virtual Servers** page, click on the Setup the Backup Manager and follow the instructions provided there.

## Step 4. Add your IBM Cloud account to Wanclouds VPC+
{: #step-4-access}

For VPC+ Cloud Migration to access details of your IBM Cloud configuration, you must add your IBM Cloud account information. Complete the following steps to add your IBM Cloud accounts.

1. In the VPC+ Cloud Migration interface, click **Cloud Accounts**. 
2. On the IBM Cloud Classic tab, provide account information for your IBM Cloud Classic infrastructure environment. This information is used to discover your current environment.
3. On the IBM Cloud VPC tab, provide account information for your VPC environment. See Gathering IBM Cloud account information for information on where to get these values.

After you log in to the {{site.data.keyword.vpc-plus-migration}} tool, you can access the _User Guide_ and _Tutorial Videos_ that were developed by Wanclouds. These resources are located in the Help menu in the {{site.data.keyword.vpc-plus-migration}} interface.
{: tip}

## Next steps
{: #cloud-account-next-steps}

After you add your {{site.data.keyword.cloud_notm}} accounts to {{site.data.keyword.vpc-plus-migration}}, you are now ready to discover the resources in your classic infrastructure. See [Discovering your {{site.data.keyword.cloud_notm}} classic infrastructure](/docs/wanclouds-vpc-plus?topic=wanclouds-vpc-plus-migrate-discovery).
