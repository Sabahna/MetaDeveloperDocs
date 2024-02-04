# Facebook Login Api

## [Authentication Versus Data Access](https://developers.facebook.com/docs/facebook-login/auth-vs-data)

Facebook Login provides two major benefits: **authentication and data access**. However, the expiration periods for authentication and data access are different and depend on different factors.

## [Long-Lived Access Tokens](https://developers.facebook.com/docs/facebook-login/guides/access-tokens/get-long-lived)

Default User and Page access tokens are **short-lived, expiring in hours**, however, you can exchange a short-lived token for a long-lived token.

## [Access Tokens: Debugging and Error Handling](https://developers.facebook.com/docs/facebook-login/guides/%20access-tokens/debugging/)

When working with an access token, you may need to check what information is associated with it, such as its user or expiry.

## [Permissions with Facebook Login](https://developers.facebook.com/docs/facebook-login/guides/permissions)

When a person logs into your app via Facebook Login you can access a subset of that person's data stored on Facebook. [Permissions](https://developers.facebook.com/docs/permissions) are how you ask someone if you can access that data.

## [Requesting & Revoking Permissions](https://developers.facebook.com/docs/facebook-login/guides/permissions/request-revoke)

Each type of login flow(web, mobile, desktop sdks or server-side code) has its own method of requesting permissions, depending on your platform and how you choose to integrate Facebook Login:

## [Handling Declined Permissions](https://developers.facebook.com/docs/facebook-login/guides/permissions/handle-declined)

When people create accounts or log into your app using Facebook Login, they have the opportunity to grant the [permissions you request](https://developers.facebook.com/docs/permissions). But people also have an opportunity to decline all permissions except their public profile.

## [Manually Build a Login Flow](https://developers.facebook.com/docs/facebook-login/guides/advanced/manual-flow)

You can build a Login flow for yourself by using browser redirects. This guide will take you through each step of the login flow and show you how to implement each one without using Facebook SDKs.

### [Re-asking for Declined Permissions](https://developers.facebook.com/docs/facebook-login/guides/advanced/manual-flow#reaskperms)

Facebook Login lets people decline sharing some permissions with your app. If someone were to uncheck some permissions, checking `/me/permissions` for which permissions have been granted results in.

### [Detecting When People Uninstall Apps](https://developers.facebook.com/docs/facebook-login/guides/advanced/manual-flow#deauth-callback)

People are able to uninstall apps via Facebook.com without interacting with the app itself. To help apps detect when this has happened, we allow them to provide a de-authorize callback URL which will be pinged whenever this occurs. You can enable a deauthorize callback through the App Dashboard.

## [Facebook Login for Business](https://developers.facebook.com/docs/facebook-login/facebook-login-for-business)

**Note:: Still Reading**

Facebook Login for Business is the preferred authentication and authorization solution for Tech Providers and business app developers who need access to their business clients' assets. It is an alternative to Facebook Login.
