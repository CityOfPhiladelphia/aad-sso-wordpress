# phila-aad-sso-wordpress
Single Sign-on with Azure Active Directory (for WordPress)

## Changes after plugin fork.
* Now you can hide the regular WordPress login inputs (username and password), so everything has to use the OAuth2 Login with ADFS. The configuration option for this is *Hide default WordPress Login*.
 
* You can select a default WordPress User for any ADFS Logged-in user that is not registered on WordPress. The configuration option for this is *Default WordPress User*

* All *Default WordPress User* and *Subscribers* will be redirected to the **Home Page** when the login preoccess finishes.
