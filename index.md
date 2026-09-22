# Privacy Policy for FartWorld

**Last updated: September 22, 2026**

## 1. Introduction

Welcome to FartWorld ("we," "our," or "us"). This Privacy Policy explains how we collect, use, and protect your information when you use our mobile application FartWorld (the "App").

**Developer:** Carlos Domínguez Cid  
**Location:** Staufen im Breisgau, Germany  
**Contact:** fartworld.app@gmail.com

## 2. Information We Collect

### 2.1 Your account
- **An account is created for you automatically.** The first time you use the App, it creates an account without an email or password (an "anonymous account") and gives it a user ID. You can use the whole App this way.
- **If you register:** your email address and a password. Registering keeps the same account, recordings and team.
- **If you do not register and you log out, reset your profile, uninstall the App or clear its data, you lose access to that account for good.** What it published stays public (see section 7 for how to ask us to delete it).

### 2.2 Information you provide
- **Username.** Required. It is public.
- **League / category.** Required. It includes categories based on gender, and **it is public**: it is shown next to your recordings and decides which leaderboard you appear in.
- **Avatar.** Public.
- **Audio recordings** you choose to save, with their loudness, duration and score. **Saved recordings are public** (see section 5).
- **Team information:** the teams you create or join. If you buy a custom team logo, the image you upload.

### 2.3 Information collected automatically
- **Device information:** device model, operating system version, app version, language, country.
- **Usage data (only if you accept analytics):** which screens you visit, which features you use, how long recordings last, timestamps. These events are linked to your FartWorld user ID. They are not anonymous.
- **Crash and performance data:** crash reports, error logs and app performance measurements (see Sentry, section 9).
- **Push notification token,** if you allow notifications.
- **Purchase information,** if you buy something: what you bought and when. We never see your payment details; Google Play handles the payment.

### 2.4 Permissions
- **Microphone:** to record audio, only while you are recording.
- **Notifications:** to send you alerts about likes and achievements (optional).

## 3. How We Use Your Information

We use your information to:
- Provide and maintain the App
- Create and manage your account
- Display your recordings on public leaderboards
- Send push notifications about likes and achievements
- Understand how the App is used and improve it (only if you accept analytics)
- Detect and fix crashes and bugs
- Process purchases
- Respond to your inquiries and requests

## 4. Where Your Data Is Stored, and Security

- **In the European Union:** the database with your profile, recordings' data and teams (Firebase Firestore, EU multi-region), and the copy of analytics events we keep for our own analysis (Google BigQuery, Belgium).
- **In the United States:** **your audio files and team logo images** (Firebase Cloud Storage, us-central1); the server code that reacts to new recordings, likes and achievements (Cloud Functions, us-central1), which reads the data it needs to do that; Firebase Authentication; and the providers RevenueCat and Expo (section 9). Google Analytics data may also be processed in the United States.
- **Sentry** stores crash and performance data in its EU region (Germany); Sentry is a US company.
- Data is encrypted in transit.
- No system is perfectly secure; we cannot guarantee absolute security.

## 5. What Is Public, and Data Sharing

We do **NOT** sell your personal data.

- **Public leaderboards:** your username, avatar, league/category, team name and your saved recordings (audio, loudness, duration, score, date) are visible to other users of the App, **and can be read by anyone on the internet, not only by App users.**
- **Teams:** your team's name, logo, score and member list are public.
- **Service providers:** see section 9.
- **Legal requirements:** if required by law or to protect our rights.

## 6. Your Rights (GDPR)

You have the following rights:

- **Access:** request a copy of your personal data
- **Rectification:** request correction of inaccurate data
- **Erasure:** request deletion of your data ("right to be forgotten")
- **Portability:** request your data in a portable format
- **Objection:** object to certain processing of your data
- **Withdraw consent:** you can withdraw your consent to analytics at any time (section 9)
- **Complaint:** you can lodge a complaint with your data protection authority

To exercise these rights, contact us at: **fartworld.app@gmail.com**. We answer within one month.

## 7. Data Retention and Deletion

- Your data is kept while your account exists.
- **The App does not currently have a button to delete your account or individual recordings.** To delete your account, your recordings or both, write to us: see **How to Delete Your FartWorld Account** (https://github.com/Yantahari/fartworld-privacy-policy/blob/main/DELETE_ACCOUNT.md). We process requests within 30 days.
- Before deleting anything, we need to make sure the request comes from the person who owns the account. That page explains how.
- After deletion, copies may remain for up to 7 days in the database and file storage (Firebase point-in-time recovery and soft delete), and for up to 14 days in our analytics copy (BigQuery time travel and fail-safe).
- **Analytics data** (only if you accepted analytics): Google Analytics keeps event data for 14 months. Data tied to your user profile in Google Analytics is also kept for 14 months, **counted from your last activity: each time you use the App the period starts again, so while you keep using the App this data is kept longer than 14 months.** The copy of analytics events we keep in BigQuery is deleted about 14 months after each day's events are recorded.
- **Crash and performance reports** in Sentry: about 30 days.
- **Purchase records:** as long as tax and accounting law requires.

## 8. Children's Privacy

FartWorld is not directed at children. We do not knowingly collect personal data from children under 16, the age from which you can consent to this kind of data processing yourself in Germany. If you believe a child under 16 has provided us with personal data, please contact us and we will delete it.

## 9. Third-Party Services

- **Google Firebase** (Google Ireland Ltd): authentication, database, file storage, push delivery.
- **Google Analytics for Firebase** (Google Ireland Ltd): usage analytics. **Only if you tap "Accept" on the privacy screen shown when you first open the App.** If you decline, it stays completely off. Events are linked to your FartWorld user ID. **To change your choice:** the current version of the App has no switch for this yet; the next update adds one in your profile. Until then, clearing the App's data in your device settings resets the choice, **but if you have not registered, that also loses your account (section 2.1)**. So register first (create an account in your profile: it keeps the same account, recordings and team), then clear the App's data, open the App, choose again, and sign back in with "Already have an account? Sign in".
- **Sentry** (Functional Software Inc, EU region): crash reports and performance data, so we can detect and fix bugs. It runs whether or not you accept analytics. We do not send your user ID, username or email to Sentry.
- **RevenueCat** (RevenueCat Inc): manages in-app purchases. It receives your FartWorld user ID and your purchase history in the App.
- **Google Play Billing:** processes payments. We never receive your payment details.
- **Expo** (650 Industries Inc): push notification delivery. It receives your push notification token.

Their privacy policies:
- Google: https://policies.google.com/privacy
- Sentry: https://sentry.io/privacy/
- RevenueCat: https://www.revenuecat.com/privacy
- Expo: https://expo.dev/privacy

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we update the "Last updated" date on this page.

## 11. Contact Us

**Carlos Domínguez Cid**  
Staufen im Breisgau, Germany  
Email: fartworld.app@gmail.com

---

*This Privacy Policy is governed by the laws of Germany and the European Union, including the General Data Protection Regulation (GDPR).*
