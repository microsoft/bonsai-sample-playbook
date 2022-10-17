# How to publish a Bonsai Sample 

## 1. Request
Fill out the [request form](https://forms.office.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR7aXU-DHqdpDt_gxbUyYOYdUME1OVTM1S0UxUUZORUY5SFZEM0RDTzVCWCQlQCN0PWcu)

- You will need a current brain version and simulator package. The package must be publishable to the [Microsoft Container Registry](https://github.com/microsoft/containerregistry) so multiple users can provision it.

- Note, your simulator container container image will become public. It is important to remove any secrets inside, such as licensing keys.


## 2. Recieve
You will receive a URL at the end of the provisioning process that can be used with Marketplace, App Source, or from your company announcements.
- Learn more about publishing in the Microsoft Marketplace in the [docs](https://learn.microsoft.com/en-us/azure/marketplace/plan-saas-offer)

## 3. Publish to App Source and Marketplace

- You need to be a registered in the [Microsoft Partner Center](https://partner.microsoft.com/en-US/)

- You will create a free [Get it now](https://docs.microsoft.com/en-us/azure/marketplace/plan-saas-offer) offer

### Offer Setup
- Click Marketplace offers from the Partner Center
![](/assets/img/MicrosoftPartnerCenter.png)

-  Click the + then Software as a Service
![](/assets/img/MarketplaceOffers.png)

-  Enter the details of your offer (these do not impact discoverability by Bonsai)

-  Under the **Setup details** on the *Offer setup page*, select “No, I would prefer to only list my offer through the marketplace and process transactions independently”

- If you are publishing a full sample, Click the **Get it now (Free)** option and enter the URL provided by the Bonsai team for the Offer URL

- If you are publishing content for a *works with simulator*, select the **Contact me** option

![image](/assets/img/OfferSetup.png)

### Categories
- An important note about Categories: Your offer’s transaction capabilities and the category/subcategory selection will determine the storefront where your offer will be published. Depending on your category selection, offers targeted to a technical (IT/Dev) audience will be published to Azure Marketplace and offers intended for a business audience will be published to Microsoft AppSource.

- The Bonsai UI launches the user to search **Azure Marketplace**, so you want to ensure your listing is there. 

- The samples produced by Bonsai are categorized under **AI for Business** (for App Source) and **ML Service** (for Marketplace)

### Offer listing
- Enter the name of your offer that will display when users are searching for content and a brief search summary​

- Fill out additional details required by the Marketplace offer (ie, description, documentation, etc.)​

- Add an optional link to GitHub repo or other posting where details may be found about the offer​

- Select a logo for your offer. This may or may not be the same as the image that displays within Bonsai once the sample is provisioned.​

- Optionally, add videos to enhance the listing

- **Important** At least one of your keywords should be bonsai_samples. This is what the Bonsai UI uses as a pre-built query for users to search for new content from within Bonsai.

### Publish the Offer

- Preview your offer in Marketplace and App Source

- Click the Go live button when you are ready to launch

![image](/assets/img/OfferOverview.png)


