# Tip & tax calculator

This app has been deployed to _AWS Amplify_. **Access the app [here](https://master.d1iemwqyd0h8xm.amplifyapp.com/).**

This project was built as a 'practice run' for React and Redux in a single-page
application. This project uses the Material-UI React component for inputs
and layout elements.

## Why so few states?

As you might notice, the main feature missing from this app is the lack of
states and their corresponding jurisdictions for sales tax information. However, with
many states having jurisdiction-specific taxes, and hundreds of jurisdictions per
state, and even with some jurisdicitons having sub-jurisdictions, it is
unfeasible to manually implement extensive tax data as it would be tedious and a
tremendous waste of time.

Perhaps in the future I will use a tax API to retrieve tax information, but that
is a feature for another time.
