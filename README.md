# aad-tesla

Test demonstrating slow response to AAD Oauth requests when access from the browser in a Telsa

## To run the test

Before starting note that you will need an active Azure AD account to run this test.

Go to http://johnshew.github.io/aad-tesla/public/test1.html.  Then click the Login button.

## Expected behavior and the issue on the Tesla

You can see that the redirect back to test2.html happens quickly with most browsers - typically it is a few seconds or less. 

Using the browser in the Tesla this same redirection back to test2.thml takes more than a minute to complete.

We would like to determine if this slow redirection is due to a bug in the Tesla browser or if it is something AAD is doing that is a problem for the Tesla browser.

Any suggestions appreciated.
