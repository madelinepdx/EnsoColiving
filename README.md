# Enso Co-living

Enso Co-living is a mobile application tailored specifically for residents of Enso Co-living spaces, offering a digital platform to manage various aspects of co-living experiences. Developed with Bubble.io, this app integrates seamlessly with Monday.com (CRM) to automate workflows and enhance user interactions.

## Key Features

- **Profile Management**: Residents can view and update their personal information, such as contact details and contractual documents. Integration with Monday.com ensures real-time data accuracy.
- **Maintenance Requests**: Submit incident request form for all housing issues (sent to Monday.com).
- **Event Calendar**: Participate in community events; ability to view, sign up, and submit events.
- **Resident Handbook**: Quick access to community rules and guidelines.
- **Dynamic Contact Options**: Contact management across various departments with options adapted to selected city locations.
### Automated User Management
- **Webhook Integration Challenges**: While the system is designed to utilize webhooks from Monday.com to manage user access based on their current tenant status, there were challenges in retrieving and processing the webhook data effectively within Bubble.io. The webhook setup was successful on Monday.com’s end, but the data retrieval and subsequent handling on Bubble.io's backend did not perform as expected. This area is a potential opportunity for further development and optimization.

- **Automated User Management**: Utilizes webhooks from Monday.com to manage user access based on their current tenant status.

## Technologies Used

- **Bubble.io**: Primary development platform for creating the frontend and backend of the app.
- **Monday.com**: Integration for CRM and automated workflows via webhooks, facilitating dynamic user and content management.
- **APIs**: Custom APIs for real-time data retrieval and management, enhancing user experience and operational efficiency.

## Screenshots
![Home Screen - Logged In](screenshots/homepage-logged-in(iPhone%20SE).png)
![Home Screen - Sign Up](screenshots/homepage-not-logged-in(iphone%20SE).png)
![Home Screen - About Us clicked](screenshots/homepage-about-us-clicked%20(iPhone%20SE).png)
![Profile](screenshots/profile(iPhone%20XR).png)
![Profile - edit](screenshots/profile-edit(iPhone%20SE).png)
![Incidents](screenshots/incidents(iPhone%20XR).png)
![Incidents - full form](screenshots/incident3%20(iPhone%20SE).png)
![Incidents - warning](screenshots/incident4(iPhone%20SE).png)
![Incidents - N/A](screenshots/incident2(iPhone%20SE).png)
![Contact](screenshots/contact(iPhone%2014).png)
![Contact - Community](screenshots/contact-community(iPhone%20XR).png)
![Events](screenshots/events%20(iPhone%20XR).png)
![Handbook](screenshots/handbook%20(iPhone%20XR).png)
![Sign Up](screenshots/sign-up(iPhone%20SE).png)
![Log In](screenshots/Login(iPhone%20SE).png)

## Installation and Setup

Clone the repository and follow the setup instructions for local development and testing:

```bash
git clone https://github.com/madelinepdx/EnsoApp.git
cd EnsoApp
# Follow specific setup instructions

### Requirements
- Node.js 12.x or higher
- npm 6.x or higher
- Flutter: for developing and testing iOS and Android applications
- CocoaPods: for managing library dependencies for iOS projects.
- Alamofire: ensure this is included in your Podfile for network requests.

### Setup
1. Install Node.js dependencies:
   ```bash
   npm install

2. Setup Flutter:
  ```bash
  flutter doctor
This command checks your environment and displays a report to the terminal window. The Dart SDK is bundled with Flutter; it is not necessary to install Dart separately. Make sure your environment is set up according to the output from flutter doctor.

3. Install CocoaPods dependencies:
  ```bash
  cd ios
  pod install
  cd ..

4.Run the application:
  ```bash
  flutter run
   ```

## Contributing
Contributions are welcome and greatly appreciated. Please fork this repository and open a pull request to add more features or submit issues for anything you feel could be improved or reported.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
## Contact
Madeline: madelinepdx@gmail.com
Project Link: https://github.com/madelinepdx/EnsoApp

## Acknowledgements
- **Bubble.io**: For providing the platform to build the app.
- **Monday.com**: For CRM and automated workflows integration.
- **Cordova**: For supporting cross-platform development.
- **Flutter**: For building beautiful, natively compiled applications.
- **Alamofire**: For handling network requests.
