# Emaily

Emaily is a MERN stack application for sending survey emails to gather user feedback. Through the use of OAuth, users can sign up for Emaily with their Google account. Emaily makes use of the Stripe API to handle user payments and the SendGrid API to handle the email functionality.

## How It Works

- User signs up with their Google account
- User adds credits through Stripe in order to send out email surveys
- User creates survey and sends it to desired recipients
- Survey responses are tracked in order to provide the user with useful feedback
- User can refer to their list of surveys in order to gather and analyze feedback

## Usage

After logging in through their Google account, users are greeted with a list of surveys that they have sent out.

![Survey List](./survey-list.png 'Survey List')

Users can add more credits in order to send out more surveys.

![Add Credits](./add-credits.png 'Add Credits')

Users can specify the content and recipients when creating surveys.

![Survey Form](./survey-form.png 'Survey Form')

Survey results will be tracked and added to the user's list of surveys.

## License

Emaily is licensed under the MIT License - see [LICENSE.txt](./LICENSE.txt) for details.
