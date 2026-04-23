# Support for Word Love

**Last Updated: April 15, 2026**

If you need help with Word Love, contact support at **deeperlanguage@gmail.com**.

Please include:
- your device type (`iPhone`, `iPad`, or `Android`)
- your app version
- a short description of the issue
- screenshots if they help explain the problem

## Premium and Billing

For subscription billing, upgrades, cancellations, and refunds, Apple App Store and Google Play billing policies apply. You can manage or cancel subscriptions through your store account settings.

## Word Jar

Free users can save up to **10** words in Word Jar.
Premium users can save unlimited words.

If premium expires, words already saved in Word Jar remain visible even when the jar is already above 10 words. In that case, new words cannot be added until the saved count drops below 10 again. Removing saved words is always allowed.

## Daily Word Reminders

On iOS, Word Love can send a daily first-word reminder at **4:30 PM** according to your device's local time.

The reminder is local to your device. It does not use server push notifications, Firebase Cloud Messaging, or a backend reminder service.

You will only receive the daily reminder when:
- onboarding has been completed
- the vocabulary content has loaded
- iOS notification permission is enabled for Word Love
- Word Love has had a chance to schedule the reminder
- iOS system settings allow the notification to be delivered

Opening Word Love earlier in the same local day does not cancel that day's 4:30 PM reminder in the current testing setup.

If Word Love is already open when the 4:30 PM reminder is due, iOS should still present the banner/list reminder subject to system notification settings.

The notification title is:
- `Today's word: <word>`

The notification body uses the compact daily definition for that first word.

Free and premium users receive the same first-word reminder because the first daily word is available to everyone.

Tapping the reminder opens the daily word in Word Love when the notification still matches the current daily word selection. If an older notification is tapped after the daily selection has changed, Word Love safely opens the current daily word selection instead.

If you deny notification permission, Word Love will not repeatedly ask again. You can enable notifications later in iOS Settings, and reminders can resume after Word Love next refreshes its local schedule.

## Privacy and Account Deletion

For privacy questions, please refer to the [Word Love Privacy Policy](PrivacyPolicy.md).

Account deletion is available in the app at `Settings` > `Account` > `Delete account`.

If you cannot access your signed-in account and still need deletion help, contact support at **deeperlanguage@gmail.com** from the email address associated with your account.

## Terms of Use

Word Love subscriptions use Apple's Standard Licensed Application End User License Agreement (EULA):

https://www.apple.com/legal/internet-services/itunes/dev/stdeula/
