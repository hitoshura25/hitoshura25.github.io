# Privacy Policy for HealthSyncApp

Last updated: December 14, 2025

The HealthSyncApp app as an open source application. This SERVICE is provided at no cost and is intended for use as is.

This page is used to inform visitors regarding our policies with the collection, use, and disclosure of Personal Information if anyone decided to use our Service.

If you choose to use our Service, then you agree to the collection and use of information in relation to this policy. The Personal Information that we collect is used for providing and improving the Service. We will not use or share your information with anyone except as described in this Privacy Policy.

## Information Collection and Use

For a better experience, while using our Service, we may require you to provide us with certain personally identifiable information. The information that we request will be retained on your device and may be synchronized to cloud storage as described below.

## Health Data

This app integrates with **Health Connect** to access your health and fitness data for the purpose of displaying and visualizing your health metrics.

### Health Data Types Accessed

Our app requests permission to READ the following health data types from Health Connect:

**Activity Data:**
- Active calories burned
- Cycling pedaling cadence
- Distance traveled
- Elevation gained
- Exercise sessions
- Floors climbed
- Heart rate
- Heart rate variability
- Power output
- Resting heart rate
- Speed
- Steps
- Steps cadence
- Total calories burned
- VO2 Max

**Body Measurements:**
- Basal body temperature
- Basal metabolic rate
- Body fat percentage
- Body temperature
- Body water mass
- Bone mass
- Height
- Lean body mass
- Weight

**Nutrition:**
- Hydration
- Nutrition information

**Sleep:**
- Sleep sessions

**Vitals:**
- Blood glucose
- Blood pressure
- Oxygen saturation
- Respiratory rate

**Background Access:**
- READ_HEALTH_DATA_IN_BACKGROUND permission is used to synchronize health data in the background for up-to-date visualization.

### Purpose of Health Data Collection

We access your health data solely to display and visualize health metrics within the app. This allows you to:
- View comprehensive health dashboards
- Track trends over time
- Monitor your fitness activities
- Analyze body composition changes
- Review sleep patterns
- Monitor vital signs

### Health Data Storage

Your health data is stored both locally on your device and synchronized to cloud storage:
- **Local Storage:** Health data is cached locally using Room database for offline access
- **Cloud Storage:** Data may be synchronized to cloud storage for backup and multi-device access
- **Encryption:** Data transmissions use HTTPS encryption. We recommend enabling encryption at rest if storing sensitive health data.

### Health Data Sharing

**We do NOT share your health data with any third parties.** Your health information remains:
- Stored locally on your device
- Optionally synchronized to your cloud storage
- Never sold or shared with advertisers
- Never used for marketing purposes
- Never transmitted to external analytics services

### Your Health Data Rights

You have the following rights regarding your health data:
- **Access:** View all health data displayed in the app
- **Deletion:** Clear all locally stored health data through the app settings
- **Revocation:** Revoke Health Connect permissions at any time through Android settings
- **Portability:** Export your data through Health Connect

To delete your health data:
1. Open HealthSyncApp
2. Go to Settings (if available)
3. Select "Delete All Data" or "Clear Cache"
4. Alternatively, uninstall the app to remove all local data

To revoke health permissions:
1. Open Android Settings
2. Go to Apps → HealthSyncApp → Permissions
3. Tap "Health Connect"
4. Revoke individual or all permissions

## Data Retention

- **Local Data:** Retained on your device until you manually delete it or uninstall the app
- **Cloud Data:** Retained according to your cloud storage provider's policies
- **Health Connect:** We only read data from Health Connect; we do not store separate copies beyond local caching

## Third-Party Services

This app uses the following third-party libraries and services:

### Health Connect
We use Health Connect to access your health and fitness data. Health Connect is developed by Google and follows strict privacy and security standards.
- Privacy Policy: https://support.google.com/android/answer/12098244

### Android Jetpack Libraries
We use standard Android Jetpack libraries for app functionality:
- Room (local database)
- WorkManager (background synchronization)
- Compose (user interface)
- Hilt (dependency injection)

These libraries run entirely on your device and do not transmit data to external services.

### No Analytics or Tracking
This app does NOT use:
- Firebase Analytics
- Google Analytics
- Crashlytics
- Ad networks
- Third-party tracking SDKs

## Log Data

We want to inform you that whenever you use our Service, in case of an error in the app, we may collect data and information (through third-party products) on your phone called Log Data. This Log Data may include information such as your device Internet Protocol ("IP") address, device name, operating system version, the configuration of the app when utilizing our Service, the time and date of your use of the Service, and other statistics.

Since we do not use crash reporting services, log data remains on your device and is not automatically transmitted to us.

## Security

We value your trust in providing us with your Personal Information, thus we strive to use commercially acceptable means of protecting it. We employ the following security practices:

- **HTTPS Encryption:** All network communications use HTTPS encryption
- **Local Storage Security:** Health data is stored in Android's secure app data directory
- **Permission Controls:** Access to health data requires explicit user permission
- **No External Sharing:** Health data never leaves your device except for your chosen cloud storage

However, remember that no method of transmission over the internet or method of electronic storage is 100% secure and reliable, and we cannot guarantee its absolute security.

## Open Source

This app is open source. The source code is available at:
- GitHub Repository: https://github.com/hitoshura25/health-sync-app

You can review the code to verify:
- How health data is accessed and stored
- That no data is shared with third parties
- The security measures implemented
- Compliance with this privacy policy

## Children's Privacy

This Service does not address anyone under the age of 13. We do not knowingly collect personally identifiable information from children under 13 years of age. If we discover that a child under 13 has provided us with personal information, we immediately delete this from our servers. If you are a parent or guardian and you are aware that your child has provided us with personal information, please contact us so that we can take necessary action.

## Health Connect Policy Compliance

This app complies with Google's Health Connect data policy:
- We only access health data necessary for app functionality
- Health data is not used for advertising or marketing
- Health data is not sold to third parties
- Users can revoke permissions at any time
- Privacy policy clearly discloses health data usage
- Prominent disclosure is provided before requesting permissions

## Changes to This Privacy Policy

We may update our Privacy Policy from time to time. Thus, you are advised to review this page periodically for any changes. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Last updated" date.

Changes are effective immediately after they are posted on this page.

## Your Consent

By using our Service, you consent to our Privacy Policy and agree to its terms.

## Contact Us

If you have any questions or suggestions about our Privacy Policy, or concerns about how your health data is handled, please do not hesitate to contact us:

**GitHub Issues:** https://github.com/hitoshura25/health-sync-app/issues

---

*This privacy policy is hosted on [GitHub Pages](https://hitoshura25.github.io/health-sync-app/privacy-policy) and complies with Google Play Store requirements for health apps.*
