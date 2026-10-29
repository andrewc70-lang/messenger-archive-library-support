# Messenger Archive Library — App Store release checklist

This is a working checklist, not confirmation that the app is already App Store-ready.

## Before submission
- [ ] Confirm the exact app name, subtitle, category, keywords and price in App Store Connect.
- [ ] Confirm the final feature list and make sure the description matches the shipped build.
- [ ] Verify the app's bundle identifier, version and build number.
- [ ] Configure Apple Developer signing and required App Sandbox capabilities in Xcode.
- [ ] Test a clean Release build on a supported macOS version.
- [ ] Test opening representative XML archives, sender names, dates, search, printing and PDF export.
- [ ] Test malformed, empty and unusually large files; ensure errors are understandable.
- [ ] Check that no private archive content is included in screenshots, logs, crash reports or the submitted package.
- [ ] Create the required app icon and accurate App Store screenshots.
- [ ] Verify the privacy policy against the actual binary, including all SDKs and network behaviour.
- [ ] Complete App Store Connect privacy disclosures and age-rating questions accurately.
- [ ] Confirm the Paid Apps agreement, tax and banking details, and price tier.
- [ ] Archive in Xcode, validate/upload with Organizer, then test the uploaded build in App Store Connect.
- [ ] Complete review information and submit for App Review.

## Draft listing
**Name:** Messenger Archive Library

**Subtitle:** Rediscover your old chat history

**Promotional description:** Bring classic instant messenger conversations back to life. Browse supported XML archives on your Mac.

**Description (verify each feature before use):**

Bring your old instant messenger conversations back to life.

Messenger Archive Library helps you revisit conversations saved in classic MSN Messenger XML archive files, with a nostalgic desktop interface inspired by the early days of instant messaging.

- Browse supported archived conversations and messages
- Search message history
- View sender names and conversation dates
- Print conversations or save them as PDF
- Enjoy a classic blue-and-green desktop design

Designed for people who want to preserve and revisit their digital memories.

This is an independent archive viewer, not an official Microsoft product. Compatibility depends on the format and contents of your archive files.

## Important
A locally packaged test app is not necessarily ready for App Store distribution. Confirm sandboxing, signing, architecture/deployment target, and release behaviour in Xcode before uploading.