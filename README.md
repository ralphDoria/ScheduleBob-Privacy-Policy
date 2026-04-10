# Privacy Policy for ScheduleBob

**Last updated:** April 10, 2026

ScheduleBob is a Chrome extension that helps UC Davis students find conflict-free course schedules and optionally share course selections with friends. This privacy policy explains what data we collect, how we use it, and your choices.

## Data We Collect

### Data collected with your consent (Friends feature)

If you choose to sign in with Google to use the Friends feature, we collect:

- **Google account information:** Your name, email address, and profile picture, obtained via Google OAuth 2.0.
- **Course selections:** The course names you have added in ScheduleBuilder, synced so friends can view them.
- **Friend connections:** Records of friend requests you send or receive, and your accepted friendships.

This data is stored in a Supabase-hosted database to enable the social features of the extension.

### Data stored locally

- **Authentication state:** Your Google OAuth token and basic profile info are stored in Chrome's local storage (`chrome.storage.local`) to keep you signed in between sessions.
- **Extension preferences:** Any settings you configure within the extension are stored locally on your device.

### Data we do NOT collect

- We do not collect browsing history, passwords, or financial information.
- We do not collect any data from pages other than UC Davis ScheduleBuilder (`my.ucdavis.edu/schedulebuilder`).
- We do not track your activity or use analytics/tracking scripts.
- We do not access any Google services beyond your basic profile information (name, email, picture).

## How We Use Your Data

- **Google account info** is used solely to identify you within the Friends feature so other users can find and connect with you.
- **Course selections** are shared only with users you have mutually accepted as friends.
- **Friend request data** is used to manage your social connections within the extension.

We do not sell, rent, or share your personal data with any third parties. Data is used exclusively to provide the extension's functionality.

## Third-Party Services

- **Google OAuth 2.0:** Used for authentication. Google's privacy policy applies to the authentication flow: https://policies.google.com/privacy
- **Supabase:** Used to store user profiles, friend connections, and shared course data. Supabase's privacy policy: https://supabase.com/privacy
- **UC Davis ScheduleBuilder:** The extension interacts with ScheduleBuilder's existing APIs on `my.ucdavis.edu` to read and manage your course schedules. No additional data is sent to UC Davis beyond what ScheduleBuilder normally processes.

## Data Retention and Deletion

- **Local data:** You can clear all locally stored data by removing the extension from Chrome or clearing extension data in Chrome settings.
- **Server data:** To delete your account and all associated data (profile, courses, friend connections) from our database, please contact us at the email below. Upon request, we will permanently delete all your data from our servers.
- **Google token:** When you sign out, your Google OAuth token is revoked and removed from local storage.

## Your Choices

- **The Friends feature is entirely optional.** You can use ScheduleBob's schedule conflict solver without signing in or sharing any personal data.
- You can sign out at any time from within the Friends modal, which revokes your Google token and clears your local session.
- You can remove friends or decline friend requests at any time.

## Security

We take reasonable measures to protect your data, including using HTTPS for all network communication and restricting database access through Supabase's row-level security policies.

## Children's Privacy

This extension is intended for UC Davis students. We do not knowingly collect personal information from children under 13.

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be reflected by the "Last updated" date above. Continued use of the extension after changes constitutes acceptance of the updated policy.

## Contact

If you have questions about this privacy policy or want to request deletion of your data, please email rpdoria@ucdavis.edu.
