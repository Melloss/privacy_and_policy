# Arganon (አርጋኖን)

## Privacy Policy

**Effective date:** 4 August 2026
**Last updated:** 4 August 2026
**Replaces:** the version dated 19 June 2024

### Introduction

Arganon ("we", "us", "our") is a mobile application for browsing, streaming, downloading and studying Ethiopian Orthodox Tewahedo mezmur (hymns) and kidase (liturgy). It is developed and maintained by Mikias Tekalign (Melloss), reachable at mellossdev@gmail.com.

This policy explains what information the App collects, why, who it is shared with, and what choices you have. It applies to the Arganon mobile application on Android and, when released, iOS.

**Arganon has no user accounts.** You do not register, and we never ask for your name, email address, phone number, or location. Most of what the App stores stays on your device.

### What we collect

**1. Information stored only on your device**

Your favourites, downloaded hymns, custom categories, chosen colour palette, category filters, lyric font size and playback preferences are saved in the App's local storage and in your device's file storage. This information is not sent to us. Uninstalling the App or clearing its data removes it.

**2. A random app identifier**

The first time you use a shared feature, the App generates a random identifier (a UUID such as `f47ac10b-58cc-…`) and stores it on your device. It is not your device's hardware id, advertising id, phone number or any other permanent identifier, and it cannot be traced back to you personally.

It is sent to our server only when you publish a category, vote on one, or delete one, so that the server can tell that the person editing or deleting a shared category is the person who created it. Clearing the App's data or reinstalling generates a new one — after which previously published categories can no longer be edited or deleted from your device.

**3. Content you choose to submit**

- **Mezmur requests** — the hymn title and artist name you type.
- **Feedback** — the text you write, the hymn it concerns, and your notification token (below) so that we can send you a reply.
- **Public categories** — the title, description and hymn list of any category you choose to publish, plus the random app identifier described above. Anything you publish becomes visible to other users of the App and can be opened by anyone with the shareable link.
- **Votes** — which shared category you voted on, and the random app identifier, so a category cannot be voted on twice from the same install.

Everything in this group is voluntary. If you never use these features, nothing is submitted.

**4. Notification token**

The App uses Firebase Cloud Messaging (Google) to notify you when new hymns are added. Firebase issues a token that identifies your installation of the App for the purpose of delivering messages. The token is stored by Google and is sent to us together with feedback you submit, so we can reply to it. It is not a personal identifier and changes when you reinstall.

**5. Advertising data**

Some features — downloading a hymn, downloading a whole category, downloading the full kidase, setting a hymn as a ringtone, saving another user's shared category, and publishing a category — are unlocked by watching a short advertisement. Advertisements are served by **Google AdMob**.

To serve, measure and protect those advertisements, Google collects and processes information such as your advertising identifier, IP address, device model, operating system, location, and your interactions with the ad. We never receive this information ourselves; it goes to Google and, where you have consented, to Google's advertising partners, each acting as an independent controller of it.

Where you are shown a consent form, that form names the advertising partners involved and lets you review them individually ("Manage options" → "List of partners"). Depending on the choices you make there, those partners may store and access information on your device and may use **precise geolocation data**. Declining, or choosing "Do not consent", prevents that use; you may still see non-personalised advertisements.

Google's practices are described at:

- https://policies.google.com/technologies/partner-sites — "How Google uses information from sites or apps that use our services"
- https://business.safety.google/adsservices/

Advertisements in Arganon are restricted to a **G (general audiences)** content rating.

**6. Technical information from ordinary use**

When the App fetches the hymn list, streams or downloads audio, or submits any of the above, our hosting providers automatically receive the standard technical information every internet request carries — IP address, request time, and general device/network information. It is used to deliver the content and to keep the service secure and functioning, and is not used to build a profile of you.

### What we do not collect

We do not collect your name, email address, phone number, contacts, calendar, photos, precise GPS location, or the contents of your device's storage. The App contains no analytics or tracking SDK beyond what is described above for advertising and notifications. We do not sell your information, and we do not share it with third parties for their own marketing.

### Your advertising choices (consent)

If you are in the European Economic Area, the United Kingdom, Switzerland, or a US state with applicable privacy legislation, the App shows you a consent form from Google's User Messaging Platform **before** any advertisement is requested. You choose whether Google may use your data for personalised advertising.

- If you consent, you may see personalised advertisements.
- If you decline, you may still see advertisements, but non-personalised ones.
- You can change your answer at any time: **Settings → የማስታወቂያ ፈቃድ** ("Ad consent"). The option appears wherever the law requires it.
- If no advertisement can be shown to you at all, the ad-supported feature is unlocked anyway. **You are never denied a feature because of an advertising choice.**

On Android you can also reset or delete your advertising id in your device settings (Settings → Google → Ads).

### Permissions the App asks for

| Permission | Why |
| --- | --- |
| Internet / network state | Fetch the hymn list, stream and download audio, serve advertisements |
| Notifications | Tell you when new hymns are added and show download/playback controls |
| Storage / audio media | Save downloaded hymns to your Downloads folder and read them back |
| Modify system settings | Only when you choose "set as ringtone" |
| Foreground service, wake lock | Keep playback and downloads running while the screen is off |

Declining a permission only disables the feature that needs it; the rest of the App keeps working.

### Who your information is shared with

| Provider | What it receives | Purpose |
| --- | --- | --- |
| Google AdMob / Google Ireland & LLC | Advertising data (section 5) | Serving and measuring advertisements |
| Google Firebase Cloud Messaging | Notification token | Delivering notifications |
| Supabase | Requests, feedback, published categories, votes, random app identifier, IP | Hosting the hymn database and shared content |
| Cloudflare R2 | IP and request metadata | Delivering audio files |
| Google Play / Apple App Store | Install and crash information they collect themselves | Distributing the App |

These providers process data on servers outside Ethiopia, including in the European Union and the United States. By using the App you agree to that transfer. Where required, we rely on the providers' standard contractual clauses.

### How long it is kept

- Data on your device: until you delete it or uninstall the App.
- Published categories and votes: until you delete them in the App, or until we remove them under the Terms below.
- Requests and feedback: for as long as needed to act on them, and afterwards as a record of changes made to the App.
- Advertising and notification data: according to Google's own retention policies, linked above.

### Your rights

Depending on where you live, you may have the right to access, correct, delete, or export your information, to object to or restrict its processing, and to lodge a complaint with your data protection authority.

In practice, for Arganon:

- **Categories you published** — delete them yourself in the App; deletion is immediate and permanent.
- **Anything else** — email mellossdev@gmail.com. Because the App has no accounts, please include the App identifier so we can find your data: open the About screen and **long-press the Arganon logo** to copy it to your clipboard, then paste it into the email. Without it we may be unable to locate records that belong to you.

We answer requests within 30 days.

### Children

Arganon is not directed at children under 13 (or the equivalent minimum age where you live) and we do not knowingly collect information from them. Advertisements are limited to a G content rating. If you believe a child has provided us with information, contact us and we will delete it.

### Security

Data in transit is encrypted with HTTPS/TLS. Access to our hosting is restricted, and the shared-content database enforces that only the device that published a category can change it. No system is completely secure, and we cannot guarantee absolute security.

### Changes to this policy

We may update this policy. The "Last updated" date at the top will change, and material changes will be announced in the App. Continuing to use the App after a change means you accept it.

### Contact

- Email: mellossdev@gmail.com
- Telegram: https://t.me/mellossDev

---

## Terms of Service

**Effective date:** 4 August 2026
**Replaces:** the version dated 19 June 2024

Welcome to Arganon. These Terms govern your access to and use of the Arganon mobile application. By using the App you agree to them. If you disagree with any part, please do not use the App.

### 1. What Arganon is

Arganon is a free application providing Ethiopian Orthodox Tewahedo hymns and liturgy for personal, devotional and study use. It is offered as a service to the community, not as a commercial product, and no account is required.

### 2. Content and ownership

The App itself — its software, design, layout, logo and original text — belongs to its developer, Mikias Tekalign (Melloss).

**The hymns, recordings, lyrics and liturgical texts in the App are not ours.** They remain the property of the singers, composers, choirs, publishers and rights holders who created them, and are made available here for devotional and educational use. Portions of the kidase material originate from publicly available recordings, credited in the App's About screen.

If you hold rights in any recording, lyric or text in the App and want it credited differently or removed, email mellossdev@gmail.com with proof of your rights and identification of the material. We will act on valid requests promptly.

You may listen to and download content for your own personal use. You may not redistribute it commercially, sell it, or present it as your own work.

### 3. Content you share

When you publish a category, submit a request, or send feedback, you confirm that what you submit is yours to share and that it is appropriate for a devotional application.

You give us permission to store, display and distribute what you publish inside the App, for as long as it remains published. You keep any rights you have in it.

Do not publish content that is offensive, misleading, unrelated to Orthodox worship, commercial, or unlawful. We may remove any shared content, or restrict access to the sharing features, without notice.

### 4. Advertisements

Some features are unlocked by watching an advertisement. Advertisements are supplied by third parties and we do not control or endorse what they show. You agree not to circumvent, automate, or otherwise interfere with the advertising features. If an advertisement cannot be shown, the feature is unlocked anyway — you are never required to watch one to use the App.

### 5. Acceptable use

You agree not to use the App to break the law, infringe anyone's rights, transmit harmful or offensive material, attempt to gain unauthorised access to our systems or another user's data, or interfere with the App's normal operation.

### 6. Availability

The App depends on services we do not control. Hymns may be added, changed or removed, features may change, and the App or its servers may be unavailable at times. We may discontinue the App or any feature at any time.

### 7. Disclaimer

The App is provided "as is" and "as available", without warranty of any kind, express or implied, including merchantability, fitness for a particular purpose, and non-infringement. We do not warrant that the App will be uninterrupted, error-free, or free of harmful components, nor that the lyrics or liturgical texts are free of transcription errors.

### 8. Limitation of liability

To the fullest extent permitted by law, we are not liable for any indirect, incidental, special or consequential damages, or for loss of data, arising out of your use of or inability to use the App, including loss of downloaded content or of categories you published. Nothing in these Terms limits liability that cannot be limited by law.

### 9. Termination

We may suspend or terminate your access to the App, or to individual features such as publishing categories, at any time, if you breach these Terms or where necessary to protect the App or its users.

### 10. Changes

We may update these Terms. The effective date above will change and material changes will be announced in the App. Continuing to use the App after a change means you accept it.

### 11. Contact

Questions about these Terms: mellossdev@gmail.com
