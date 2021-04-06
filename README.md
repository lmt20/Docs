# Docs
## 
<!--- These are examples. See https://shields.io for others or to customize this set of shields. You might want to include dependencies, project status and licence info here --->
![GitHub repo size](https://img.shields.io/github/repo-size/lmt20/Docs)
![GitHub issues](https://img.shields.io/github/issues/lmt20/Docs)
![GitHub contributors](https://img.shields.io/github/contributors/lmt20/Docs)
![Twitter Follow](https://img.shields.io/twitter/follow/TruongLeManh?style=social)

# In App Purchase Workflow

Step 1: Sign a Paid Applications Agreement

Detail in: [https://help.apple.com/app-store-connect/#/devb6df5ee51](https://help.apple.com/app-store-connect/#/devb6df5ee51)

Step 2: Configure in-app purchases in App Store Connect

* Create an in-app purchase:
    1. From My Apps, select your app.
    2. In the sidebar under In-App Purchases, click Manage.
    3. To add an in-app purchase, go to In-App Purchases and click the Add button (+).
    4. Select auto-renewable subscription, then click create.
    5. Add your in-app purchase reference name and product ID, then click Next.
    6. If this is the first auto-renewable subscription product you are creating, you'll need to also create a subscription group (you'll be able to add details to it later), by selecting Choose New Subscription Group. If you've already created subscription products and groups before, add your subscription product to an existing group or create a new subscription group. Then click Create.
    7. Once you've created your subscription product, you'll be taken to its information page to add more details. Under Subscription Duration, choose a duration from the pop-up menu.
    8. Under Subscription Prices
    9. Under Localizations, click on the Add button (+) to add a language for your localized display name.
    10. Enter your localized information.
    11. Under App Store Promotion, optionally add an promotional image
    12. Under Review Information, provide any additional information that may help the App Review team review your in-app purchase.
    13. Click Save.
* Add subscription group information and levels
    1. From My Apps, select your app.
    2. In the sidebar, under In-App Purchases, click Subscription Groups.
    3. Click the Subscription Group you wish to edit.
    4. To set subscription levels, click the reordering control on the right side of a subscription row and drag it to a new position to change its level. (Set montly package level 2 and yearly package level 1)
    5. Under Localizations, click on the Add button (+) to add a language for your localized subscription group name.
    6. Enter your localized Subscription Group Display Name.
    7. Click Save.
    8. Generate a receipt validation code for your app (use this value to verify your auto-renewable subscriptions for your app)
        - From My Apps, select your app.
        - In the sidebar under In-App Purchases, click Manage.
        - Click App-Specific Shared Secret to view the shared secret for the app.
        - To generate a shared secret, click Generate App-Specific Shared Secret or Regenerate from the dialog.
        - Copy the code and use it for your transactions receipt for this app.

Step 3: Enable in-app purchase in Xcode

- Add in-app purchase capability in Xcode: [https://help.apple.com/xcode/mac/current/#/dev88ff319e7](https://help.apple.com/xcode/mac/current/#/dev88ff319e7)
- Make sure that the bundle identifier and product identifiers for your app in Xcode match the identifiers for your app in your developer account and for the in-app purchases you configured in App Store Connect.

Step 4: Design and create your in-app purchase

Step 5: Test in-app purchases

- Create a Sandbox Tester Account: [https://help.apple.com/app-store-connect/#/dev8b997bee1](https://help.apple.com/app-store-connect/#/dev8b997bee1)

Step 6: Publish your app and in-app purchase on the App Store
    

AUTHOR
-----------
👤 **Le Manh Truong**
* Twitter: [@TruongLeManh](https://twitter.com/TruongLeManh)
* Github: [@lmt20](https://github.com/lmt20)
* LinkedIn: [@truong-le-manh](https://www.linkedin.com/in/truong-le-manh/)

