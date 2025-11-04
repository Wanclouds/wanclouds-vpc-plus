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

# Getting started with VPC+
{: #getting-started-tutorial}

Use {{site.data.keyword.vpc-plus-migration}} to migrate your {{site.data.keyword.cloud}} classic infrastructure to {{site.data.keyword.cloud_notm}} Virtual Private Cloud (VPC).
{: shortdesc}

## Step 1. Learn more about {{site.data.keyword.vpc-plus-migration}}
{: #step-1-learn}

Before you begin migrating your classic infrastructure to VPC, learn more about {{site.data.keyword.vpc-plus-migration}} and which classic resources can be migrated. To learn more, see [About {{site.data.keyword.vpc-plus-migration}}](/docs/wanclouds-vpc-plus?topic=wanclouds-vpc-plus-about-wanclouds).

## Step 2. Plan for your migration 
{: #step-2-plan}

To get the best results from your VPC migration, spend time analyzing your classic environment and learning how the {{site.data.keyword.vpc-plus-migration}} tool handles different components of your environment. For more information, see [Planning for migration](/docs/wanclouds-vpc-plus?topic=wanclouds-vpc-plus-planning-for-migration).

## Step 3. Create an instance of Custom Migration DR and Management as a Service tile through the IBM Catalog
{: #step-3-create}

Complete the following steps to create an instance.

1. From the tile Creation via IBM Marketplace: Custom Migration DR and Management as a Service
2. Login to your IBM Cloud account.
3. Navigate to the [IBM Cloud Catalog](https://cloud.ibm.com/catalog).
4. In the search bar, type "Custom Migration DR and Management as a Service" and select the tile from the search results.
5. Select "Custom Migration Request" as the pricing plan.
6. Click "Create" to create the service instance.
7. Once the instance is created, you will be redirected to a [form](https://migration.wanclouds.net/?state=abcdefghij&code=fAQjJUXnQ2k). Fill out the required details and submit the form.

## Step 4. Add your IBM Cloud account to Wanclouds VPC+ (Step 4 onward will be completed with assistance from the "Wanclouds team")
{: #step-4-access}

For VPC+ to access details of your IBM Cloud configuration. Complete the following steps to add your IBM Cloud accounts.

1. In the VPC+ interface, click **Cloud Accounts** in the left pane. 
2. On the IBM Cloud Classic tab, provide account information for your IBM Cloud Classic infrastructure environment. This information is used to discover your current environment.
3. On the IBM Cloud VPC tab, provide account information for your VPC environment. See Gathering IBM Cloud account information for information on where to get these values.

After you log in to the {{site.data.keyword.vpc-plus-migration}} tool, you can access the _User Guide_ and _Tutorial Videos_ that were developed by Wanclouds. These resources are located in the Help menu in the {{site.data.keyword.vpc-plus-migration}} interface.
{: tip}

## Next steps
{: #cloud-account-next-steps}

After you add your {{site.data.keyword.cloud_notm}} accounts to {{site.data.keyword.vpc-plus-migration}}, you are now ready to discover the resources in your classic infrastructure. See [Discovering your {{site.data.keyword.cloud_notm}} classic infrastructure](/docs/wanclouds-vpc-plus?topic=wanclouds-vpc-plus-migrate-discovery).
