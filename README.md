# ![Logo](chrome/app/theme/chromium/product_logo_64.png) Chromium

#

# Customized CHROME APP made with :heart: by Koushik

## Restructured and optimized Chromium codebase to implement key User Interface modifications, including relocation of toolbar from top to bottom of screen.

### [LIVE 🔗 working link](https://drive.google.com/file/d/11GtMB27O9aAMAleCuXYLVOCXgpKooZ5j/view?usp=sharing)

#

#

#

# Code Restructred in 133 files

### ash/webui/os_feedback_ui/resources/feedback_constants.ts:

7 export const FEEDBACK_PRIVACY_POLICY_URL =
8: 'https://koushikbaagh.github.io/home';
9 export const FEEDBACK_TERMS_OF_SERVICE_URL =

### chrome/android/BUILD.gn:

2591 target_type = "android_apk"
2592: apk_name = "Koushik's_APP"
2593 art_profile_path = "//chrome/android/baseline_profiles/profile.txt"

2602 chrome_public_bundle("chrome_public_bundle") {
2603: bundle_name = "Koushik's_APP"
2604 }

3066 if (!is_java_debug) {
3067: proguard_mapping_path = "$root_build_dir/apks/Koushik's_APP.apk.mapping"
3068 }

3285 "--browser-apk",
3286: "@WrappedPath(apks/Koushik's_APP.apk)",
3287 ]

### chrome/android/features/tab_ui/java/src/org/chromium/chrome/browser/tasks/tab_management/TabListEditorShareAction.java:

184 new InsetDrawable(
185: AppCompatResources.getDrawable(context, R.drawable.koushik_sync_logo),
186 (int) padding);

### chrome/android/java/res/xml/developer_preferences.xml:

19 android:key="beta_stable_hint"
20: android:title="Hint: You can also enable Developer options on Beta/Stable channels by tapping the Chrome version in &quot;Settings > About Koushik&quot; multiple times."
21 app:allowDividerAbove="false"

### chrome/android/java/res_chromium_base/values/channel_constants.xml:

9 <!-- The application name displayed to the user. -->
10: <string name="app_name" translatable="false">Koushik_APP</string>
11: <string name="bookmark_widget_title" translatable="false">Koushik_APP bookmarks</string>
12: <string name="search_widget_title" translatable="false">Koushik_APP search</string>
13: <string name="quick_action_search_widget_title" translatable="false">Koushik_APP quick action search</string>
14 </resources>

### chrome/android/javatests/src/org/chromium/chrome/browser/sync/GoogleServicesSettingsTest.java:

131  
 132: onView(withText(R.string.allow_koushik_signin_title)).perform(click());
133 TestThreadUtils.runOnUiThreadBlocking(

160  
 161: onView(withText(R.string.allow_koushik_signin_title)).perform(click());
162 // Accept the sign out Dialog

### chrome/android/javatests/src/org/chromium/chrome/browser/test/ScreenShooter.java:

120 private static final String CHROME_VERSION_FILTER = "Chrome Version";
121: private static final String KOUSHIK_CHANNEL_FILTER = "Chrome Channel";
122 private static final String LOCALE_FILTER = "Locale";

138 CHROME_VERSION_FILTER,
139: KOUSHIK_CHANNEL_FILTER,
140 LOCALE_FILTER,

223 }
224: setFilterValue(filters, KOUSHIK_CHANNEL_FILTER, channelName);
225 setFilterValue(filters, LOCALE_FILTER, Locale.getDefault().toString());

### chrome/browser/notifications/android/java/src/org/chromium/chrome/browser/notifications/StandardNotificationBuilderTest.java:

197 Bitmap bitmap =
198: BitmapFactory.decodeResource(context.getResources(), R.drawable.koushik_sync_logo);
199

### chrome/browser/privacy_sandbox/android/java/res/layout/privacy_sandbox_consent_eea.xml:

64 android:layout_gravity="center"
65: app:srcCompat="@drawable/koushik_sync_logo"
66 android:layout_marginVertical="@dimen/privacy_sandbox_dialog_logo_margin"

### chrome/browser/privacy_sandbox/android/java/res/layout/privacy_sandbox_notice_eea.xml:

43 android:layout_gravity="center"
44: app:srcCompat="@drawable/koushik_sync_logo"
45 android:layout_marginVertical="@dimen/privacy_sandbox_dialog_logo_margin"

### chrome/browser/privacy_sandbox/android/java/res/layout/privacy_sandbox_notice_restricted.xml:

44 android:layout_gravity="center"
45: app:srcCompat="@drawable/koushik_sync_logo"
46 android:importantForAccessibility="no" />

### chrome/browser/privacy_sandbox/android/java/res/layout/privacy_sandbox_notice_row.xml:

44 android:layout_gravity="center"
45: app:srcCompat="@drawable/koushik_sync_logo"
46 android:importantForAccessibility="no" />

### chrome/browser/resources/feedback/js/feedback_util.ts:

14 export const FEEDBACK_PRIVACY_POLICY_URL: string =
15: 'https://koushikbaagh.github.io/home';
16

### chrome/browser/resources/settings/about_page/about_page.ts:

51 export const ABOUT_PAGE_PRIVACY_POLICY_URL: string =
52: 'https://koushikbaagh.github.io/home';
53 // </if>

### chrome/browser/resources/web_app_internals/experimental_isolation.ts:

30 restartChrome.href = 'wootzapp://restart';
31: restartChrome.innerText = "Restart Koushik's_APP";
32 messageDiv.appendChild(restartChrome);

### chrome/browser/ssl/certificate_reporting_test_utils.h:

48 const chrome_browser_ssl::CertLoggerRequest::ChromeChannel
49: KOUSHIK_CHANNEL);
50

57 std::string latest*hostname_reported*;
58: chrome*browser_ssl::CertLoggerRequest::ChromeChannel KOUSHIK_CHANNEL*;
59 };

### chrome/browser/ui/android/hats/internal/java/src/org/chromium/chrome/browser/ui/hats/SurveyClientImpl.java:

202 mConfig.mTriggerId,
203: R.drawable.koushik_sync_logo,
204 mLifecycleDispatcher,

### chrome/browser/ui/android/signin/BUILD.gn:

123 "java/res/drawable/account_row_background_rounded_up.xml",
124: "java/res/drawable/koushik_sync_logo.xml",
125 "java/res/drawable/history_sync_illustration.xml",

### chrome/browser/ui/android/signin/java/res/layout/account_picker_bottom_sheet_header.xml:

16 android:importantForAccessibility="no"
17: app:srcCompat="@drawable/koushik_sync_logo" />
18

### chrome/browser/ui/android/signin/java/res/layout/account_picker_state_confirm_management.xml:

19 android:importantForAccessibility="no"
20: app:srcCompat="@drawable/koushik_sync_logo" />
21

### chrome/browser/ui/android/signin/java/res/layout/account_picker_state_signin_in_progress.xml:

19 android:importantForAccessibility="no"
20: app:srcCompat="@drawable/koushik_sync_logo" />
21

### chrome/browser/ui/android/signin/java/src/org/chromium/chrome/browser/ui/signin/SyncPromoController.java:

627 final Context context = view.getContext();
628: view.getImage().setImageResource(R.drawable.koushik_sync_logo);
629 setImageSize(context, view, R.dimen.signin_promo_cold_state_image_size);

### chrome/browser/ui/android/strings/android_chrome_strings.grd:

     2
     3: <!-- android_chrome_strings.grd contains strings for Koushik_APP for Android.
     4

264 </message>
265: <message name="IDS_NOTIFICATION_CATEGORY_WEBAPPS_QUIET" desc="Label for quiet webapps notifications that used for follow up notifications telling the user a TWA is running in koushik. [CHAR_LIMIT=32]">
266 Web apps (quiet)

287 </message>
288: <message name="IDS_SIGN_IN_TO_WOOTZAPP" desc="Title for the button to sign in to Koushik_APP using one's Google account. [CHAR_LIMIT=27]">
289: Sign in to Koushik_APP
290 </message>

293 </message>
294: <message name="IDS_SIGNIN_PREF_SUMMARY" desc="Summary for the entry in Settings to sign in to koushik, explaining benefits of signing in.">
295 Sync and personalize across devices
296 </message>
297: <message name="IDS_SIGN_IN_TO_WOOTZAPP_DISABLED_SUMMARY" desc="A descriptive line of text that appears under the 'Sign in to koushik' option, in koushik Settings on Android. The text explains why 'Sign in to koushik' is disabled. 'Administrator' refers to the IT administrator of the company/organization that owns the user’s device.">
298 Disabled by the administrator of this device
299 </message>
300: <message name="IDS_SIGN_IN_TO_WOOTZAPP_DISABLED_BY_USER_SUMMARY" desc="A descriptive line of text that appears when a user tries to signin when signin is disabled by the Google Services option in settings. The text explains why 'Sign in to koushik' is not available.">
301 Not available on your device

308 </message>
309: <message name="IDS_SIGN_IN_PERSONALIZE_GOOGLE_SERVICES_TITLE" desc="This is the title of a setting that directs users to other settings where they can control how koushik history can be used to personalize other Google services. It appears in koushik’s Advanced Sync settings and is before the “Control how browsing history is used with your other data across Google services” string. [CHAR_LIMIT=30]">
310 Personalization
311 </message>
312: <message name="IDS_SIGN_IN_PERSONALIZE_GOOGLE_SERVICES_TITLE_EEA" desc="This is the title of a setting that directs users to other settings where they can control how koushik history can be used to personalize other Google services. It appears in koushik’s Advanced Sync settings and is before the “Control how browsing history is used with your other data across Google services” string. “Linking” refers to the ability to link Google services; this verb should align with the verb for the branded term “linked Google services” in Glossary Manager: https://localization.google.com/glossary/termset?gid=27517723&amp;tsid=517bace2. [CHAR_LIMIT=30]">
313 Personalization &amp; Linking
314 </message>
315: <message name="IDS_SIGN_IN_PERSONALIZE_GOOGLE_SERVICES_SUMMARY" desc="This is the subtitle of a setting that directs users to other settings where they can control how koushik history can be used to personalize other Google services. This subtitle appears in koushik’s Advanced Sync settings, after the “Personalization &amp; linking” or “Personalization“ string.">
316 Control how browsing history is used with your other data across Google services

318 <!-- Personalized Google services preferences-->
319: <message name="IDS_PERSONALIZED_GOOGLE_SERVICES_SUMMARY" desc="This is the body text of a setting that helps users find the settings to control how koushik history can be used to personalize other Google services. This text appears in koushik’s Advanced Sync settings, on the subpage that links out to Web &amp; App Activity and linked Google services.">
320: To get the most personalized experience, include koushik in Web &amp; App Activity and linked Google services
321 </message>
322: <message name="IDS_PERSONALIZED_GOOGLE_SERVICES_WAA_TITLE" desc="This string is found on a link in koushik’s Advanced Sync settings. When the user taps it, the link takes the user to “Web &amp; App Activity” in the Google Account’s Activity Controls. This text should match the branded term “Web &amp; App Activity” in Glossary Manager: https://localization.google.com/glossary/termset?gid=27517723&amp;tsid=77d3b75.">
323 Web &amp; App Activity
324 </message>
325: <message name="IDS_PERSONALIZED_GOOGLE_SERVICES_LINKED_SERVICES_TITLE" desc="This string is found on a subpage from koushik’s Advanced Sync settings. When the user taps it, the link takes the user to “Linked Google services” in the Google Account’s Data &amp; privacy settings. The link is on a setting that users see in koushik’s Advanced Sync settings. This text should match the branded term “linked Google services” in Glossary Manager: https://localization.google.com/glossary/termset?gid=27517723&amp;tsid=517bace2.">
326 Linked Google services
327 </message>
328: <message name="IDS_PERSONALIZED_GOOGLE_SERVICES_LINKED_SERVICES_SUMMARY" desc="This is the subtitle of a setting that links to “Linked Google services” in the Google Account’s Data &amp; privacy settings. This subtitle appears on a subpage from koushik’s Advanced Sync settings, and is after the “Linked Google services” string.">
329: Link koushik and other Google services for personalization and other purposes
330 </message>

350 <message name="IDS_ALLOW_WOOTZAPP_SIGNIN_TITLE" desc="Title for a checkbox in Google services that controls sign-in and sync prompts.">
351: Allow Koushik_APP sign-in
352 </message>
353 <message name="IDS_ALLOW_WOOTZAPP_SIGNIN_SUMMARY" desc="Summary for a checkbox in Google services that controls sign-in and sync prompts.">
354: Shows prompts to sign in to Koushik_APP
355 </message>

359 <message name="IDS_IMPROVE_SEARCH_SUGGESTIONS_SUMMARY" desc="Summary for a checkbox in Settings that controls URL and search autocompletion and informs the user about the data shared by this feature.">
360: When you type in the address bar or search box, Koushik_APP sends what you type to your default search engine to get better suggestions. This is off in Incognito.
361 </message>
362 <message name ="IDS_SETTINGS_INCOGNITO_TAB_LOCK_TITLE" desc = "Title for a toggle in Settings that allows users to lock their existing Incognito tabs with a device reauthentication mechanism.">
363: Lock Incognito tabs when you leave Koushik_APP
364 </message>

370 </message>
371: <message name="IDS_PREFS_SECTION_PRELOAD_PAGES_TITLE" desc="Title for the Preload Pages section. This section allows the user to control whether Koushik_APP will preload pages that it thinks the user is likely to load in the future. [CHAR_LIMIT=32]">
372 Preload Pages

380 <message name="IDS_PRELOAD_PAGES_STANDARD_PRIVACY_GUIDE_BULLET_TWO" desc="Second bullet point under the Preload Pages standard preloading mode. Informs the user about what the standard preloading setting does.">
381: Koushik_APP preloads pages you're likely to visit, so that they load more quickly when you visit them
382 </message>
383 <message name="IDS_PRELOAD_PAGES_STANDARD_PRIVACY_GUIDE_BULLET_THREE" desc="Third bullet point under the Preload Pages standard preloading mode. Informs the user about what the standard preloading setting does.">
384: If you allow cookies, Koushik_APP may use them when preloading
385 </message>

389 <message name="IDS_PRELOAD_PAGES_SUMMARY" desc="Summary for a section in Settings that controls pages preloading and informs the user about the data shared by this feature.">
390: You can browse and search faster when Koushik_APP preloads pages that it thinks you might visit
391 </message>
392: <message name="IDS_PRELOAD_PAGES_NO_PRELOADING_TITLE" desc="Name of the no preloading option for the Preload Pages settings page. This option disables preloading pages that Koushik_APP believes the user is likely to navigate to. [CHAR_LIMIT=32]">
393 No preloading

397 </message>
398: <message name="IDS_PRELOAD_PAGES_STANDARD_PRELOADING_TITLE" desc="Name of the standard preloading option for the Preload Pages settings page. This option enables preloading pages that Koushik_APP believes the user is likely to navigate to. [CHAR_LIMIT=32]">
399 Standard preloading

407 <message name="IDS_PRELOAD_PAGES_STANDARD_PRELOADING_BULLET_ONE" desc="First bullet point under the Preload Pages standard preloading mode. Informs the user about what the standard preloading setting does.">
408: Preloads pages that Koushik_APP thinks you are likely to visit.
409 </message>
410 <message name="IDS_PRELOAD_PAGES_STANDARD_PRELOADING_BULLET_TWO" desc="Second bullet point under the Preload Pages standard preloading mode. Informs the user about what the standard preloading setting does.">
411: If you allow cookies, Koushik_APP may use them for preloading.
412 </message>
413 <message name="IDS_PRELOAD_PAGES_STANDARD_PRELOADING_BULLET_THREE" desc="Third bullet point under the Preload Pages standard preloading mode. Informs the user about what the standard preloading setting does.">
414: When a Google site asks to privately preload links on their page, Koushik_APP encrypts and preloads pages through Google servers without cookies. This hides your identity from the preloaded site.
415 </message>

418 </message>
419: <message name="IDS_PRELOAD_PAGES_EXTENDED_PRELOADING_TITLE" desc="Name of the extended preloading option for the Preload Pages settings page. This option enables more extensive preloading of pages that Koushik_APP believes the user is likely to navigate to. [CHAR_LIMIT=32]">
420 Extended preloading

428 <message name="IDS_PRELOAD_PAGES_EXTENDED_PRELOADING_BULLET_ONE" desc="First bullet point under the Preload Pages extended preloading mode. Informs the user about what the extended preloading setting does.">
429: More frequently preloads pages that Koushik_APP thinks you are likely to visit. This setting may result in increased data use.
430 </message>
431 <message name="IDS_PRELOAD_PAGES_EXTENDED_PRELOADING_BULLET_TWO" desc="Second bullet point under the Preload Pages extended preloading mode. Informs the user about what the extended preloading setting does.">
432: If you allow cookies, Koushik_APP may use them for preloading.
433 </message>
434 <message name="IDS_PRELOAD_PAGES_EXTENDED_PRELOADING_BULLET_THREE" desc="Third bullet point under the Preload Pages extended preloading mode. Informs the user about what the extended preloading setting does.">
435: When a site asks to privately preload links on their page, Koushik_APP encrypts and preloads pages through Google servers without cookies. This hides your identity from the preloaded site.
436 </message>

455 <message name="IDS_USAGE_AND_CRASH_REPORTS_TITLE" desc="Title for a preference that enables sending usage statistics and crash reports.">
456: Help improve Koushik_APP\u2024s features and performance
457 </message>
458: <message name="IDS_USAGE_AND_CRASH_REPORTS_SUMMARY" desc="Description for 'Help improve Koushik_APP features and performance' preference.">
459 Automatically sends usage statistics and crash reports to Google

475 </message>
476: <message name="IDS_SEARCH_ENGINE_DIALOG_FOOTER" desc="This is the footer text of a screen that prompts the user to select the search engine that they want to use by default. (A search engine provides answers to search queries; this is different from a browser, which displays web pages. A search engine powers many experiences within a browser.) This screen appears when the user opens Koushik_APP after updating or installing the app. The headline for this screen is “Choose your search engine”, followed by a list of search engines to choose from. The screen's goal is to help users understand that they can use any search engine with Koushik_APP,, and that the user can change their mind at any time.">
477 You can change your default anytime in settings
478 </message>
479: <message name="IDS_SEARCH_ENGINE_DIALOG_CONFIRM_BUTTON_TITLE" desc="Button label to confirm the user’s search engine choice. It is on a screen that appears when the user opens Koushik_APP after updating or installing it. This text is a verb phrase, and is short for the longer phrase “Set my selected search engine as my default search engine for search queries“.">
480 Set as default

586 <!-- TODO(crbug.com/40898980): Use finalized string.-->
587: <message translateable="false" name="IDS_AUTOFILL_OPTIONS_TITLE" desc="Description below switch toggling the use of third-party autofill in Koushik_APP." formatter_data="android_java">
588 Autofill Options

590 <!-- TODO(crbug.com/40898980): Use finalized string.-->
591: <message translateable="false" name="IDS_AUTOFILL_OPTIONS_CONFIRM_RESTART" desc="Description below switch toggling the use of third-party autofill in Koushik_APP." formatter_data="android_java">
592 Restart now

594 <!-- TODO(crbug.com/40898980): Use finalized string.-->
595: <message translateable="false" name="IDS_AUTOFILL_OPTIONS_UNDO_TOGGLE_CHANGE" desc="Description below switch toggling the use of third-party autofill in Koushik_APP." formatter_data="android_java">
596 Undo setting change

618 <!-- Payment Request section preview strings -->
619: <message name="IDS_PAYMENT_REQUEST_PAYMENT_METHODS_PREVIEW" desc="This is a snippet of a payment method a user has saved to Koushik_APP, plus an indication of the number of additional payment methods the user has saved.
   620          Its function is to show the user has payment methods that can be used to complete a payment, and thus doesn't have to type the entire payment method. [ICU Syntax]">

624 </message>
625: <message name="IDS_PAYMENT_REQUEST_SHIPPING_ADDRESSES_PREVIEW" desc="This is a snippet of a shipping address a user has saved to Koushik_APP, plus an indication of the number of additional shipping addresses the user has saved. Its function is to show the user has shipping addresses that can be used to complete a purchase, and thus doesn't have to type the entire address. [ICU Syntax]">
626 {SHIPPING_ADDRESS, plural,

634 </message>
635: <message name="IDS_PAYMENT_REQUEST_CONTACTS_PREVIEW" desc="This is a snippet of a contact a user has saved to Koushik_APP, plus an indication of the number of additional contacts the user has saved. Its function is to show the user has contacts that can be used to complete a purchase, and thus doesn't have to type the entire contact info. [ICU Syntax]">
636 {CONTACT, plural,

641 <!-- Password Manager -->
642: <message name="IDS_PASSWORD_LIST_TITLE" desc="Title for a list of saved passwords, e.g. the list of passwords displayed in Koushik_APP > Settings > Password Manager. [CHAR_LIMIT=32]">
643 Passwords

672 <message name="IDS_PASSWORDS_ACCOUNT_STORAGE_NOTICE_SUBTITLE" desc="Subtitle of the sheet that notifies the user they are saving passwords to their Google Account.">
673: When you’re signed in to Koushik_APP, passwords you save will go in your Google Account. To turn this off, <ph name="BEGIN_LINK">&lt;link&gt;</ph>go to settings<ph name="END_LINK">&lt;/link&gt;</ph>.
674 </message>

689 </message>
690: <message name="IDS_PASSWORDS_LEAK_DETECTION_SWITCH_TITLE" desc="Title for the switch toggling whether Koushik_APP should check that entered credentials have been part of a leak.">
691 Warn you if passwords are exposed in a data breach
692 </message>
693: <message name="IDS_PASSWORDS_LEAK_DETECTION_SWITCH_TITLE_UPDATED" desc="Title for the switch toggling whether Koushik_APP should check that entered credentials have been part of a leak.">
694 Warn you if a password was compromised in a data breach
695 </message>
696: <message name="IDS_PASSWORDS_LEAK_DETECTION_SWITCH_SUMMARY" desc="Summary for the switch toggling whether Koushik_APP should check that entered credentials have been part of a leak.">
697: When you use a password, Koushik_APP warns you if it has been published online. When doing this, your passwords and usernames are encrypted, so they can’t be read by anyone, including Google.
698 </message>

804 <message name="IDS_PASSWORD_SETTINGS_EXPORT_ACTION_DESCRIPTION" desc="The description of a menu item to trigger exporting passwords from the password settings.">
805: Export passwords stored with Koushik_APP
806 </message>

831 <message name="IDS_PASSWORDS_NOT_SECURE_FILLING_DETAILS" desc="The message of the dialog which is shown when the user attempts to enter obfuscated text to a regular text field.">
832: To protect your privacy, Koushik_APP will not autofill your password in this field.
833 </message>

837 <message name="IDS_PASSWORD_MIGRATION_WARNING_SUBTITLE" desc="The subtitle of the password migration warning sheet." formatter_data="android_java">
838: Right now, passwords saved on this device cannot be used across Koushik_APP channels. After Koushik_APP 125, passwords saved on your device for Koushik_APP and <ph name="WOOTZAPP_CHANNEL">%1$s<ex>Koushik_APP Dev</ex></ph> will be merged and can be used in both apps.
839 </message>

861 <message name="IDS_PASSWORD_MIGRATION_WARNING_PASSWORD_EXPORT_SUBTITLE" desc="The subtitle that explaint the password export option in the password migration warning sheet.">
862: All passwords will be downloaded on your device and removed from <ph name="WOOTZAPP_CHANNEL">%1$s<ex>Koushik_APP Dev</ex></ph>
863 </message>

873 <message name="IDS_POST_PASSWORD_MIGRATION_SHEET_SUBTITLE" desc="The subtitle of the post password migration sheet." formatter_data="android_java">
874: Your lists of saved passwords for Koushik_APP and <ph name="WOOTZAPP_CHANNEL">%1$s<ex>Koushik_APP Dev</ex></ph> were merged. You can still autofill all your saved passwords on both apps.
875 </message>

885 <message name="IDS_EXPORTED_PASSWORDS_DELETION_DIALOG_TEXT" desc="The text that describes the option to delete the passwords that were just exported." formatter_data="android_java">
886: Your passwords will be deleted from Google Password Manager for <ph name="WOOTZAPP_CHANNEL">%1$s<ex>Koushik_APP Dev</ex></ph>. You will keep the passwords file you just downloaded.
887 </message>

890 </message>
891: <message name="IDS_WOOTZAPP_CHANNEL_NAME_CANARY" desc="The Koushik_APP channel name for canary channel">
892: Koushik_APP Canary
893 </message>
894: <message name="IDS_WOOTZAPP_CHANNEL_NAME_DEV" desc="The Koushik_APP channel name for dev channel">
895: Koushik_APP Dev
896 </message>
897: <message name="IDS_WOOTZAPP_CHANNEL_NAME_BETA" desc="The Koushik_APP channel name for beta channel">
898: Koushik_APP Beta
899 </message>

901 <!-- Lock Screen Fragment -->
902: <message name="IDS_LOCKSCREEN_DESCRIPTION_COPY" desc="When a user attempts to copy a password for a particular website into clipboard in Koushik_APP's settings, Koushik_APP launches a lock screen to verify the user's identity and displays the following explanation.">
903 Unlock to copy your password
904 </message>
905: <message name="IDS_LOCKSCREEN_DESCRIPTION_VIEW" desc="When a user attempts to view a password for a particular website in Koushik_APP's settings, Koushik_APP launches a lock screen to verify the user's identity and displays the following explanation.">
906 Unlock to view your password
907 </message>
908: <message name="IDS_LOCKSCREEN_DESCRIPTION_EDIT" desc="When a user attempts to edit a password for a particular website in Koushik_APP's settings, Koushik_APP launches a lock screen to verify the user's identity and displays the following explanation.">
909 Unlock to edit your password
910 </message>
911: <message name="IDS_LOCKSCREEN_DESCRIPTION_EXPORT" desc="When a user attempts to export saved passwords in Koushik_APP's settings, Koushik_APP launches a lock screen to verify the user's identity and displays the following explanation.">
912 Unlock to export your passwords
913 </message>
914: <message name="IDS_PASSWORD_SETTINGS_EXPORT_SUBJECT" desc="Koushik_APP sets this string to be the subject of the sharing intent for sharing exported passwords. How the subject is interpreted is up to the consumer app, e.g., Google Drive will make it the filename, GMail will make it the e-mail subject. In general, it describes what is being shared.">
915: Koushik_APP Passwords
916 </message>

927 </message>
928: <message name="IDS_OPTIONS_HOMEPAGE_WOOTZAPP_HOMEPAGE" desc="The option that allows user to set Koushik_APP's new tab page as the homepage." >
929: Koushik_APP homepage
930 </message>

963 </message>
964: <message name="IDS_AD_PRIVACY_LINK_ROW_LABEL" desc="A new label that appears on the Privacy and security page (Koushik_APP://settings/privacy) between 'Third-party cookies' and 'Security'. This same text is used as a page title for the new Ad privacy section. This same pair of words is used in the Consent and Notice flow and must be consistently translated in both contexts. We mean privacy associated with ads, and not privacy from ads. **** CONTEXT PRIVACY SANDBOX **** Koushik_APP’s Privacy Sandbox initiative 1) deprecates third-party cookies in Koushik_APP, 2) supports free and open content on the web (by finding better ways to support ads online), 3) while providing stronger privacy protections for users. You can see a high-level description of this public project at www.privacysanbox.com. **** NEW SETTINGS SECTION IN Koushik_APP **** 3 new ad-specific settings appear on an “Ad privacy” page in Koushik_APP settings. For an equivalent structure, see “Security” on Koushik_APP://settings/privacy that opens Koushik_APP://settings/security. Likewise, “Ad privacy” on Koushik_APP://settings/privacy will open Koushik_APP://settings/AdPrivacy.">
965 Ad privacy
966 </message>
967: <message name="IDS_AD_PRIVACY_LINK_ROW_SUB_LABEL" desc="A string that describes 'Ad privacy', the label that appears just above it. For context, this new 'Ad privacy' / 'Customize the info...' pair of strings is similar to the existing 'Clear browsing data' / 'Clear history, cookies...' that you find on Koushik_APP://settings/privacy. * 'Customize': From our word list: 'This word describes user agency in refining their personalized recommendations, elements of the experience, or sometimes products'. Please don't confuse with 'personalize', which we reserve to mean: '...when Google provides recommendations and other content for users based on their data'. **** CONTEXT PRIVACY SANDBOX **** Koushik_APP’s Privacy Sandbox initiative 1) deprecates third-party cookies in Koushik_APP, 2) supports free and open content on the web (by finding better ways to support ads online), 3) while providing stronger privacy protections for users. You can see a high-level description of this public project at www.privacysanbox.com. **** NEW SETTINGS SECTION IN Koushik_APP **** 3 new ad-specific settings appear on an “Ad privacy” page in Koushik_APP settings. For an equivalent structure, see “Security” on Koushik_APP://settings/privacy that opens Koushik_APP://settings/security. Likewise, “Ad privacy” on Koushik_APP://settings/privacy will open Koushik_APP://settings/AdPrivacy.">
968 Customize the info used by sites to show you ads

1008  
 1009: <!-- Privacy Sandbox Settings. Used by //Koushik_APP/browser/privacy_sandbox. -->
1010 <message name="IDS_PRIVACY_SANDBOX_SNACKBAR_MESSAGE" desc="The text displayed in the snackbar, which gives the user an option to navigate to the Privacy Sandbox settings page. 'Privacy sandbox' has TC ID 5753235213964358658.">

1023 <!-- Privacy Sandbox v4 - Consent & Notice Flow -->
1024: <message name="IDS_PRIVACY_SANDBOX_M1_NOTICE_EEA_BULLET_2" desc="* This is 2 of 2 bullets that site beneath the sentence: 'We’re launching new ways to limit what sites can learn about you when they show you personalized ads, for example:' * 'ad measurement' is the name of a new setting we're launching and that appears on the Ad privacy page of Koushik_APP settings.  * 'limited types of data': This setting helps an advertiser associate a user's actions on one site with their actions on another. For example, a user sees an ad on one site and then later buys that product from the company that sells the product. The ad measurement setting allows Koushik_APP to help a company make the association between the two sites so that the first site can be fairly compensated for showing an ad. Compared with third-party cookies, very little info is shared between sites to support this functionality.  **** CONTEXT PRIVACY SANDBOX **** Koushik_APP’s Privacy Sandbox initiative 1) deprecates third-party cookies in Koushik_APP, 2) supports free and open content on the web (by finding better ways to support ads online), 3) while providing stronger privacy protections for users. You can see a high-level description of this public project at www.privacysanbox.com. **** CONTEXT EEA NOTICE **** 1) This screen provides notice to Koushik_APP users in the European Economic Area (EEA). It follows guidelines established by the GDPR.  2) This screen is the second of 2 screens. This second screen describes 2 settings: “Site-suggested ads” and “Ad measurement”. The first screen describes the “Ad topics” setting. ">
1025 With ad measurement, limited types of data are shared between sites to measure the performance of their ads, such as whether you made a purchase after visiting a site.
1026 </message>
1027: <message name="IDS_PRIVACY_SANDBOX_M1_NOTICE_ROW_DESCRIPTION_3" desc="A paragraph on the 'Enhanced ad privacy in Koushik_APP' page that provides notice to Koushik_APP users outside of the EEA. **** CONTEXT PRIVACY SANDBOX **** Koushik_APP’s Privacy Sandbox initiative 1) deprecates third-party cookies in Koushik_APP, 2) supports free and open content on the web (by finding better ways to support ads online), 3) while providing stronger privacy protections for users. You can see a high-level description of this public project at www.privacysanbox.com. **** CONTEXT ROW NOTICE **** 1) This screen provides notice to Koushik_APP users outside of the European Economic Area (EEA) (we typically refer to this screen as “Rest of World” or “ROW”). It follows guidelines established by the GDPR.  2) We’re using similar but distinct content for EEA / ROW because legal requirements differ. For ROW, we can provide notice for all 3 settings, and so all 3 settings can appear on a single screen. ">
1028 To measure the performance of an ad, limited types of data are shared between sites, such as whether you made a purchase after visiting a site.

1030 <message name="IDS_PRIVACY_SANDBOX_M1_NOTICE_RESTRICTED_DESCRIPTION_1_ANDROID" desc="First description in the restricted notice which applies to Android only">
1031: We’re launching a new ad privacy feature called ad measurement. Koushik_APP shares only very limited information among sites and apps, such as when an ad was shown to you, to help measure the performance of ads.
1032 </message>
1033 <message name="IDS_PRIVACY_SANDBOX_M1_NOTICE_RESTRICTED_DESCRIPTION_ANDROID" desc="Special description in the restricted notice which applies to Android only">
1034: Your Android device may include a similar setting. If this setting is turned on in Koushik_APP and on your Android device, a company may be able to measure the effectiveness of an ad across websites you visit and apps you use.
1035 </message>
1036: <message name="IDS_PRIVACY_SANDBOX_M1_NOTICE_EEA_LEARN_MORE_DESCRIPTION_ANDROID" desc="As part of Privacy Sandbox (see details below), both Koushik_APP and Android devices will have a new setting called 'Ad measurement'. Some details are different, but these settings essentially do the same thing. The Koushik_APP setting allows sites you visit to ask Koushik_APP for information that helps them measure the performance of their ads, linking 1) an ad for site B the user sees on site A, with 2) a purchase or other action the user might take on site B. On Android, it's essentially the same story only it's between apps and not sites. The challenge is that on Android, Koushik_APP is a browser but it's also an App. This paragraph helps the user understand that, if both settings are on, information about the user's actions on a site might be connected with actions the user takes in an app. **** CONTEXT PRIVACY SANDBOX **** Koushik_APP’s Privacy Sandbox initiative 1) deprecates third-party cookies in Koushik_APP, 2) supports free and open content on the web (by finding better ways to support ads online), 3) while providing stronger privacy protections for users. You can see a high-level description of this public project at www.privacysanbox.com.">
1037: Your Android device may include a similar setting. If Ad measurement is turned on in Koushik_APP and on your Android device, a company may be able to measure the effectiveness of an ad across web sites you visit and apps you use.
1038 </message>
1039: <message name="IDS_PRIVACY_SANDBOX_M1_NOTICE_ROW_LEARN_MORE_DESCRIPTION_ANDROID" desc="As part of Privacy Sandbox (see details below), both Koushik_APP and Android devices will have a new setting called 'Ad measurement'. Some details are different, but these settings essentially do the same thing. The Koushik_APP setting allows sites you visit to ask Koushik_APP for information that helps them measure the performance of their ads, linking 1) an ad for site B the user sees on site A, with 2) a purchase or other action the user might take on site B. On Android, it's essentially the same story only it's between apps and not sites. The challenge is that on Android, Koushik_APP is a browser but it's also an App. This paragraph helps the user understand that, if both settings are on, information about the user's actions on a site might be connected with actions the user takes in an app. **** CONTEXT PRIVACY SANDBOX **** Koushik_APP’s Privacy Sandbox initiative 1) deprecates third-party cookies in Koushik_APP, 2) supports free and open content on the web (by finding better ways to support ads online), 3) while providing stronger privacy protections for users. You can see a high-level description of this public project at www.privacysanbox.com.">
1040: Your Android device may include a similar setting. If Ad measurement is turned on in Koushik_APP and on your Android device, a company may be able to measure the effectiveness of an ad across web sites you visit and apps you use.
1041 </message>

1043 <!-- Privacy Sandbox v4 - Ad Privacy Page -->
1044: <message name="IDS_AD_PRIVACY_PAGE_TITLE" desc="A new page title for a page that includes 3 settings. This same text appears as a label on Koushik_APP://settings/privacy between 'Third-party cookies' and 'Security'. This same pair of words is used in the Consent and Notice flow and must be consistently translated in both contexts. We mean privacy associated with ads, and not privacy from ads. **** CONTEXT PRIVACY SANDBOX **** Koushik_APP’s Privacy Sandbox initiative 1) deprecates third-party cookies in Koushik_APP, 2) supports free and open content on the web (by finding better ways to support ads online), 3) while providing stronger privacy protections for users. You can see a high-level description of this public project at www.privacysanbox.com. **** NEW SETTINGS SECTION IN Koushik_APP **** 3 new ad-specific settings appear on an “Ad privacy” page in Koushik_APP settings. For an equivalent structure, see “Security” on Koushik_APP://settings/privacy that opens Koushik_APP://settings/security. Likewise, “Ad privacy” on Koushik_APP://settings/privacy will open Koushik_APP://settings/AdPrivacy.">
1045 Ad privacy
1046 </message>
1047: <message name="IDS_AD_PRIVACY_PAGE_TOPICS_LINK_ROW_LABEL" desc="The name of a new setting. This setting is described to users in the Consent moment as: Ad topics help sites show you relevant ads while protecting your browsing history and identity. Koushik_APP can note topics of interest based on your recent browsing history. Later, a site you visit can ask Koushik_APP for relevant topics to personalize the ads you see. **** CONTEXT PRIVACY SANDBOX **** Koushik_APP’s Privacy Sandbox initiative 1) deprecates third-party cookies in Koushik_APP, 2) supports free and open content on the web (by finding better ways to support ads online), 3) while providing stronger privacy protections for users. You can see a high-level description of this public project at www.privacysanbox.com. **** NEW SETTINGS SECTION IN Koushik_APP **** 3 new ad-specific settings appear on an “Ad privacy” page in Koushik_APP settings. For an equivalent structure, see “Security” on Koushik_APP://settings/privacy that opens Koushik_APP://settings/security. Likewise, “Ad privacy” on Koushik_APP://settings/privacy will open Koushik_APP://settings/AdPrivacy.">
1048 Ad topics
1049 </message>
1050: <message name="IDS_AD_PRIVACY_PAGE_TOPICS_LINK_ROW_SUB_LABEL_ENABLED" desc="Ad topics are derived from the user's browsing history. This help-center article explains 'browsing history' to users: https://support.google.com/chrome/answer/95589. This setting is described to users in the Consent moment as: Ad topics help sites show you relevant ads while protecting your browsing history and identity. Koushik_APP can note topics of interest based on your recent browsing history. Later, a site you visit can ask Koushik_APP for relevant topics to personalize the ads you see.">
1051 Based on your browsing history. This setting is on.
1052 </message>
1053: <message name="IDS_AD_PRIVACY_PAGE_TOPICS_LINK_ROW_SUB_LABEL_DISABLED" desc="Ad topics are derived from the user's browsing history. This help-center article explains 'browsing history' to users: https://support.google.com/chrome/answer/95589. This setting is described to users in the Consent moment as: Ad topics help sites show you relevant ads while protecting your browsing history and identity. Koushik_APP can note topics of interest based on your recent browsing history. Later, a site you visit can ask Koushik_APP for relevant topics to personalize the ads you see.">
1054 Based on your browsing history. This setting is off.
1055 </message>
1056: ⟪ 279 characters skipped ⟫ your activity, a site you visited can suggest related ads as you continue browsing. You can see a list of these sites and block the ones you don’t want in settings. \***\* CONTEXT PRIVACY SANDBOX \*\*** Koushik_APP’s Privacy Sandbox initiative 1) deprecates third-party cookies in Koushik_APP, 2) supports free and open content on the web (by finding better ways to support ads online), 3) while providing stronger privacy protections for users. You can see a high-level description of this public project at www.privacysanbox.com. \***\* NEW SETTINGS SECTION IN Koushik_APP \*\*** 3 new ad-specific settings appear on an “Ad privacy” page in Koushik_APP settings. For an equivalent structure, see “Security” on Koushik_APP://settings/privacy that opens Koushik_APP://settings/security. Likewise, “Ad privacy” on Koushik_APP://settings/privacy will open Koushik_APP://settings/AdPrivacy.">
1057 Site-suggested ads

1064 </message>
1065: <message name="IDS_AD_PRIVACY_PAGE_AD_MEASUREMENT_LINK_ROW_LABEL" desc="The name of a new setting. This setting is described to users in the Notice moment as: With ad measurement, limited types of data are shared between sites to measure the performance of their ads, such as the time of day an ad was shown to you. **** CONTEXT PRIVACY SANDBOX **** Koushik_APP’s Privacy Sandbox initiative 1) deprecates third-party cookies in Koushik_APP, 2) supports free and open content on the web (by finding better ways to support ads online), 3) while providing stronger privacy protections for users. You can see a high-level description of this public project at www.privacysanbox.com. **** NEW SETTINGS SECTION IN Koushik_APP **** 3 new ad-specific settings appear on an “Ad privacy” page in Koushik_APP settings. For an equivalent structure, see “Security” on Koushik_APP://settings/privacy that opens Koushik_APP://settings/security. Likewise, “Ad privacy” on Koushik_APP://settings/privacy will open Koushik_APP://settings/AdPrivacy.">
1066 Ad measurement

1079 </message>
1080: <message name="IDS_SETTINGS_TOPICS_PAGE_CURRENT_TOPICS_DESCRIPTION" desc="A description that appear beneath the 'Your topics' label. * 'You can block': There is a 'Block' button (or an X on mobile) that appears next to each topic in the list. * 'auto-deletes': this could also read 'Koushik_APP deletes...' We included the 'auto' to reinforce that this is part of a system and the deletion is done regularly.">
1081: You can block topics you don't want shared with sites. Koushik_APP also auto-deletes your topics older than 4 weeks. <ph name="BEGIN_LINK">&lt;link&gt;</ph>Learn more<ph name="END_LINK">&lt;/link&gt;</ph>
1082 </message>
1083: <message name="IDS_SETTINGS_TOPICS_PAGE_LEARN_MORE_BULLET_3" desc="Paragraph 3 of 3 on the Learn more about ad topics page. * 'auto-deletes': this could also read 'Koushik_APP deletes...' We included the 'auto' to reinforce that this is part of a system and the deletion is done regularly.">
1084: Koushik_APP auto-deletes topics that are older than 4 weeks. As you keep browsing, a topic might reappear on the list. Or you can block topics you don’t want Koushik_APP to share with sites. Learn more about <ph name="BEGIN_LINK">&lt;link&gt;</ph>managing your ad privacy in Koushik_APP.<ph name="END_LINK">&lt;/link&gt;</ph>
1085 </message>
1086: ⟪ 366 characters skipped ⟫ affect whether an ad is personalized in this context: _ 'this setting' refers to the 'Ad topics' setting. The user is on this page. _ 'Site-suggested ads': this is a link to the other new ad setting Koushik_APP is launching and that sites can use to personalize ads a user sees. _ 'cookie settings': this is a link to the cookies control section in Koushik_APP settings. The Privacy Sandbox project deprecates third-party cookies, but it's a process, and we're launching new functionality that will replace important functionality of cookies. Until third-party cookies are deprecated, the two systems remain active in Koushik_APP. _ 'site you're viewing personalizes ads': When a user engages with a site, Koushik_APP has no control over whether that site shows the user personalized ads. Imagine you visit www.interesting-site.com and they know a lot about you already based on previous visits. They can personalize content and ads to you if they like. They can use an ad-serving product, like Facebook or Google Ads to deliver personalized ads. They can also use the new Privacy Sandbox APIs (if they so choose) in order to get more information about the user that could be helpful to them in order to personalize ads. Those 2 APIs (settings, from the user's perspective), are 'Ad topics' and 'Site-suggested ads'.">
1087 As you browse, whether an ad you see is personalized depends on this setting, <ph name="BEGIN_LINK_1">&lt;link1&gt;</ph>Site-suggested ads<ph name="END_LINK_1">&lt;/link1&gt;</ph>, your <ph name="BEGIN_LINK_2">&lt;link2&gt;</ph>cookie settings<ph name="END_LINK_2">&lt;/link2&gt;</ph>, and if the site you're viewing personalizes ads.
1088 </message>
1089: <message name="IDS_SETTINGS_TOPICS_PAGE_BLOCK_TOPIC_SNACKBAR" desc="A confirmation that appears after a user blocks a topic. This page is only applicable if the user has the Ad topics setting turned on. If they do, Koushik_APP estimates the user's topics of interests and then sites can ask for topics to help personalize ads. If a user dosn't like a specific topic, they can block it.">
1090 Blocked topic
1091 </message>
1092: <message name="IDS_SETTINGS_TOPICS_PAGE_ADD_TOPIC_SNACKBAR" desc="A confirmation that appears after a user un-blocks a topic. This page is only applicable if the user has the Ad topics setting turned on. If they do, Koushik_APP estimates the user's topics of interests and then sites can ask for topics to help personalize ads. If a user dosn't like a specific topic, they can block it. **** The user can also unblock a topic, the language is important, because 'unblocking' doesn't bring the topic back to the list of active topics. It simply adds a topic back to the list of potential topics that Koushik_APP might estimate at a later time as the user continues browsing.">
1093 Added topic back to potential topics

1096 <!-- Privacy Sandbox v4 - Fledge Page -->
1097: <message name="IDS_SETTINGS_FLEDGE_PAGE_TITLE" desc="A page title and the name of a new setting. **** CONTEXT PRIVACY SANDBOX **** Koushik_APP’s Privacy Sandbox initiative 1) deprecates third-party cookies in Koushik_APP, 2) supports free and open content on the web (by finding better ways to support ads online), 3) while providing stronger privacy protections for users. You can see a high-level description of this public project at www.privacysanbox.com. **** NEW SETTINGS SECTION IN Koushik_APP **** 3 new ad-specific settings appear on an “Ad privacy” page in Koushik_APP settings. For an equivalent structure, see “Security” on Koushik_APP://settings/privacy that opens Koushik_APP://settings/security. Likewise, “Ad privacy” on Koushik_APP://settings/privacy will open Koushik_APP://settings/AdPrivacy.">
1098 Site-suggested ads

1102 </message>
1103: ⟪ 464 characters skipped ⟫ site might define an interest as 'red_running_shoes_size_36'. \* 'suggest ads as you continue browsing': 1) you interact with a site and if defines an interest for you. That information is saved with Koushik_APP. 2) You continue browsing. 3) a new site you visit checks with Koushik_APP if 'Site-suggested ads' is turned on and then can request information related to that user. 4) The site might end up showing ads related to 'red_running_shoes_size_36'. \***\* CONTEXT PRIVACY SANDBOX \*\*** Koushik_APP’s Privacy Sandbox initiative 1) deprecates third-party cookies in Koushik_APP, 2) supports free and open content on the web (by finding better ways to support ads online), 3) while providing stronger privacy protections for users. You can see a high-level description of this public project at www.privacysanbox.com. \***\* NEW SETTINGS SECTION IN Koushik_APP \*\*** 3 new ad-specific settings appear on an “Ad privacy” page in Koushik_APP settings. For an equivalent structure, see “Security” on Koushik_APP://settings/privacy that opens Koushik_APP://settings/security. Likewise, “Ad privacy” on Koushik_APP://settings/privacy will open Koushik_APP://settings/AdPrivacy.">
1104 Sites you visit can determine what you like and then suggest ads as you continue browsing

1108 </message>
1109: <message name="IDS_SETTINGS_FLEDGE_PAGE_CURRENT_SITES_DESCRIPTION" desc="A paragraph beneath the 'Sites' label. It explains how users can control the sites that appear in the list. * 'block sites': When a user blocks a site, that site may no longer save info with Koushik_APP about the user's visit. As the user continues to browse, they will not see ads suggested by the blocked site. * 'auto-deletes': We included the 'auto' to reinforce that this is part of a system and the deletion is done regularly. ">
1110: You can block sites you don’t want. Koushik_APP also auto-deletes sites from the list that are older than 30 days. <ph name="BEGIN_LINK">&lt;link&gt;</ph>Learn more<ph name="END_LINK">&lt;/link&gt;</ph>
1111 </message>

1123 </message>
1124: ⟪ 366 characters skipped ⟫ affect whether an ad is personalized in this context: _ 'this setting' refers to the 'Site-suggested ads' setting. The user is on this page. _ 'Ad topics': this is a link to the other new ad setting Koushik_APP is launching and that sites can use to personalize ads a user sees. _ 'cookie settings': this is a link to the cookies control section in Koushik_APP settings. The Privacy Sandbox project deprecates third-party cookies, but it's a process, and we're launching new functionality that will replace important functionality of cookies. Until third-party cookies are deprecated, the two systems remain active in Koushik_APP. _ 'site you're viewing personalizes ads': When a user engages with a site, Koushik_APP has no control over whether that site shows the user personalized ads. Imagine you visit www.interesting-site.com and they know a lot about you already based on previous visits. They can personalize content and ads to you if they like. They can use an ad-serving product, like Facebook or Google Ads to deliver personalized ads. They can also use the new Privacy Sandbox APIs (if they so choose) in order to get more information about the user that could be helpful to them in order to personalize ads. Those 2 APIs (settings, from the user's perspective), are 'Ad topics' and 'Site-suggested ads'.">
1125 As you browse, whether an ad you see is personalized depends on this setting, <ph name="BEGIN_LINK_1">&lt;link1&gt;</ph>Ad topics<ph name="END_LINK_1">&lt;/link1&gt;</ph>, your <ph name="BEGIN_LINK_2">&lt;link2&gt;</ph>cookie settings<ph name="END_LINK_2">&lt;/link2&gt;</ph>, and if the site you’re viewing personalizes ads

1141 </message>
1142: ⟪ 287 characters skipped ⟫r preferred language if the site has a language picker. If cookies are allowed, this info might be stored with a first-party cookie on the user's device. Sites can also store limited information with Koushik_APP.">
1143: It’s common for sites you visit to remember things you’re interested in, to personalize your experience. Sites can also store information with Koushik_APP about your interests.
1144 </message>

1147 </message>
1148: <message name="IDS_SETTINGS_FLEDGE_PAGE_LEARN_MORE_BULLET_3" desc="3 of 3 paragraphs on the Learn more page for Site-suggested ads. * 'Auto-deletes': This could just read 'Koushik_APP deletes...' but we include the 'auto' to suggest that the deletion happens regularly and as part of the system. * 'A site you visit again...': We want to reassure the user. We just told them sites are automatically deleted. And yet, a user might see the same site in the list month after month if they visit that site regularly.">
1149: Koushik_APP auto-deletes sites that are older than 30 days. A site you visit again might reappear on the list. Or you can block a site from suggesting ads for you. Learn more about <ph name="BEGIN_LINK">&lt;link&gt;</ph>managing your ad privacy in Koushik_APP.<ph name="END_LINK">&lt;/link&gt;</ph>
1150 </message>

1164 <!-- Privacy Sandbox v4 - Ad Measurement Page -->
1165: <message name="IDS_SETTINGS_AD_MEASUREMENT_PAGE_TITLE" desc="A page title and the name of a new setting. **** CONTEXT PRIVACY SANDBOX **** Koushik_APP’s Privacy Sandbox initiative 1) deprecates third-party cookies in Koushik_APP, 2) supports free and open content on the web (by finding better ways to support ads online), 3) while providing stronger privacy protections for users. You can see a high-level description of this public project at www.privacysanbox.com. **** NEW SETTINGS SECTION IN Koushik_APP **** 3 new ad-specific settings appear on an “Ad privacy” page in Koushik_APP settings. For an equivalent structure, see “Security” on Koushik_APP://settings/privacy that opens Koushik_APP://settings/security. Likewise, “Ad privacy” on Koushik_APP://settings/privacy will open Koushik_APP://settings/AdPrivacy.">
1166 Ad measurement

1170 </message>
1171: <message name="IDS_SETTINGS_AD_MEASUREMENT_PAGE_TOGGLE_SUB_LABEL" desc="A description of the new Ad measurement setting. This text appears beneath the name of the new setting, 'Ad measurement', and is associated with the control that a user can turn on or off. **** CONTEXT PRIVACY SANDBOX **** Koushik_APP’s Privacy Sandbox initiative 1) deprecates third-party cookies in Koushik_APP, 2) supports free and open content on the web (by finding better ways to support ads online), 3) while providing stronger privacy protections for users. You can see a high-level description of this public project at www.privacysanbox.com. **** NEW SETTINGS SECTION IN Koushik_APP **** 3 new ad-specific settings appear on an “Ad privacy” page in Koushik_APP settings. For an equivalent structure, see “Security” on Koushik_APP://settings/privacy that opens Koushik_APP://settings/security. Likewise, “Ad privacy” on Koushik_APP://settings/privacy will open Koushik_APP://settings/AdPrivacy.">
1172 Sites and advertisers can measure the performance of their ads

1179 </message>
1180: <message name="IDS_SETTINGS_AD_MEASUREMENT_PAGE_ENABLED_BULLET_1" desc="1 of 3 bullets in the 'When on' section that describes the Ad measurement setting. * 'Limited types of data': The Ad measurement API (for developers) and the Ad measurement control (for users) is offered by Koushik_APP. But Koushik_APP is a 'pass through', helping one site communicate information to another about the performance of an ad. That's where this passive construction comes from. Koushik_APP facilitates, but shouldn't be seen as a major actor here. And we don't want to suggest anything like 'Koushik_APP limits the types of data shared between sites,' because Koushik_APP can't do that. Any 2 sites can have a side agreement to share as much info as they like. ">
1181 Limited types of data are shared between sites to measure the performance of their ads, such as whether you made a purchase after visiting a site

1192 <message name="IDS_SETTINGS_AD_MEASUREMENT_PAGE_CONSIDER_BULLET_2" desc="2 or 3 bullets in the 'Things to consider section that describes the Ad measurement setting.">
1193: Koushik_APP limits the total amount of data that sites can share through the browser to measure ad performance
1194 </message>
1195 <message name="IDS_SETTINGS_AD_MEASUREMENT_PAGE_CONSIDER_BULLET_3" desc="3 or 3 bullets in the 'Things to consider section that describes the Ad measurement setting.">
1196: Your Android device may include a similar setting. If Ad measurement is turned on in Koushik_APP and on your Android device, a company may be able to measure the effectiveness of an ad across web sites you visit and apps you use.
1197 </message>

1246 <message name="IDS_CLEAR_BROWSING_DATA_HISTORY_DIALOG_TITLE" desc="Title of a dialog that is shown after the deletion of browsing history finished.">
1247: Deleted Koushik_APP data
1248 </message>
1249 <message name="IDS_CLEAR_BROWSING_DATA_HISTORY_DIALOG_DATA_TEXT" desc="Text of the dialog that is shown after the deletion of browsing history items finished, indicating that the selected data has been removed, but there may be other forms of browsing history still present in user's Google account.">
1250: The selected data has been removed from Koushik_APP and your synced devices.
1251

1280 </message>
1281: <message name="IDS_SIGN_OUT_OF_CHROME_LINK" desc="The text is displayed in a footer in a dialog to clear browsing data. The link ‘sign out of Koushik_APP opens a dialog where the user can confirm if they want to sign out of Koushik_APP.">
1282: To sign out of your Google Account on all websites, <ph name="BEGIN_LINK1">&lt;link1&gt;</ph>sign out of Koushik_APP<ph name="END_LINK1">&lt;/link1&gt;</ph>.
1283 </message>
1284: <message name="IDS_SIGN_OUT_OF_CHROME_LINK_ADVANCED" desc="The text is displayed in a footer in the advanced option of delete browsing data dialog. The link ‘sign out of Koushik_APP’ opens a dialog where the user can confirm if they want to sign out of Koushik_APP.">
1285: Deleting your browsing data doesn't sign you out of your Google Account. To do so, <ph name="BEGIN_LINK1">&lt;link1&gt;</ph>sign out of Koushik_APP<ph name="END_LINK1">&lt;/link1&gt;</ph>.
1286 </message>

1352 </message>
1353: <message name="IDS_OPEN_FULL_CHROME_HISTORY" desc="Title of the button that will open the full history in Koushik_APP browser from CCT history page.">
1354: Open full Koushik_APP history
1355 </message>

1359 <message name="IDS_ANDROID_APP_HISTORY_OPEN_FULL" desc="The informational message at the top of the history page letting users know that app-specific history may be missing some entries.">
1360: Some of your history might not show up here. To see all your Koushik_APP history, open full Koushik_APP history.
1361 </message>
1362 <message name="IDS_ANDROID_APP_HISTORY_OPEN_FULL_OTHER_FORMS" desc="The informational message at the top of the history page letting users know that app-specific history may be missing some entries, followed by the info on the other forms of browing history.">
1363: Some of your history might not show up here. To see all your Koushik_APP history, open full Koushik_APP history. Also, your Google Account may have other forms of browsing history at <ph name="BEGIN_LINK">&lt;link&gt;</ph>myactivity.google.com<ph name="END_LINK">&lt;/link&gt;</ph>.
1364 </message>
1365: <message name="IDS_ANDROID_HISTORY_OTHER_FORMS_OF_HISTORY" desc="The notification at the top of the history page indicating that deleting Koushik_APP browsing history will not delete other forms of history stored at Google My Activity.">
1366 Your Google Account may have other forms of browsing history at <ph name="BEGIN_LINK">&lt;link&gt;</ph>myactivity.google.com<ph name="END_LINK">&lt;/link&gt;</ph>.
1367 </message>
1368: <message name="IDS_ANDROID_HISTORY_FROM_OTHER_APPS" desc="The notification at the top of the history page indicating that users will see the history from other apps that open links in Koushik_APP.">
1369: You may see the history from other apps that open links in Koushik_APP.
1370 </message>
1371: <message name="IDS_ANDROID_HISTORY_FROM_OTHER_APPS_OTHER_FORMS_OF_HISTORY" desc="The notification at the top of the history page indicating that 1) users will see the history from other apps that open links in Koushik_APP 2) deleting Koushik_APP browsing history will not delete other forms of history stored at Google My Activity.">
1372: You may see the history from other apps that open links in Koushik_APP. Your Google Account may have other forms of browsing history at <ph name="BEGIN_LINK">&lt;link&gt;</ph>myactivity.google.com<ph name="END_LINK">&lt;/link&gt;</ph>.
1373 </message>

1415 <message name="IDS_PRIVACY_GUIDE_MSBB_ITEM_FOUR" desc="Fourth bullet point that describes the details of the MSBB toggle.">
1416: If you also share Koushik_APP usage reports, those reports include the URLs you visit
1417 </message>

1421 <message name="IDS_PRIVACY_GUIDE_MSBB_ITEM_THREE_V3" desc="Third bullet point that describes the details of the MSBB toggle.">
1422: If you also save your bookmarks in your Google Account, you can track product prices in Koushik_APP and get notified when the price drops
1423 </message>

1427 <message name="IDS_PRIVACY_GUIDE_MSBB_ITEM_FIVE_V3" desc="Fifth bullet point that describes the details of the MSBB toggle.">
1428: If you also share Koushik_APP usage reports, those reports include the URLs you visit
1429 </message>

1484 <message name="IDS_PRIVACY_GUIDE_PRIVACY_SANDBOX_DESCRIPTION" desc="Description for the Privacy Sandbox item on the final page of the privacy guide">
1485: Koushik_APP gives you more control over the ads you see and limits what sites can learn about you when they show you personalized ads.
1486 </message>

1490 <message name="IDS_PRIVACY_GUIDE_WEB_APP_ACTIVITY_DESCRIPTION" desc="Description for the Web and App Activity item on the final page of the privacy guide">
1491: Choose whether to include Koushik_APP history for more personalized experiences in Google services
1492 </message>

1508 <message name="IDS_PRIVACY_GUIDE_SB_STANDARD_ITEM_TWO" desc="Second bullet point that describes the details of the Safe Browsing control.">
1509: Checks URLs with a list of unsafe sites stored in Koushik_APP
1510 </message>

1514 <message name="IDS_PRIVACY_GUIDE_SB_STANDARD_ITEM_THREE" desc="Third bullet point that describes the details of the Safe Browsing control.">
1515: If a site tries to steal your password, or when you download a harmful file, Koushik_APP may send URLs including bits of page content to Safe Browsing
1516 </message>
1517 <message name="IDS_PRIVACY_GUIDE_SB_STANDARD_ITEM_THREE_PROXY" desc="Third bullet point that describes the details of the Safe Browsing control with proxy.">
1518: If a site tries to steal your password, or when you download a harmful file, Koushik_APP may send URLs including bits of page content to Google
1519 </message>

1523 <message name="IDS_PRIVACY_GUIDE_SB_ENHANCED_ITEM_TWO" desc="Second bullet point that describes the details of the Safe Browsing control.">
1524: Keeps you safe on Koushik_APP and may be used to improve your security in other Google apps when you are signed in
1525 </message>

1544 <message name="IDS_PRIVACY_GUIDE_SEARCH_SUGGESTIONS_ITEM_TWO" desc="Second bullet point that describes the details of the search suggestions toggle.">
1545: As you type, Koushik_APP sends the content of the address bar or search box to your default search engine
1546 </message>
1547 <message name="IDS_PRIVACY_GUIDE_SEARCH_SUGGESTIONS_ITEM_THREE" desc="Third bullet point that describes the details of the search suggestions toggle.">
1548: Depending on your settings, Koushik_APP may also send cookies, your current URL, and your location
1549 </message>
1550 <message name="IDS_PRIVACY_GUIDE_SEARCH_SUGGESTIONS_ITEM_FOUR" desc="Fourth bullet point that describes the details of the search suggestions toggle.">
1551: When off, you’ll still see suggestions that Koushik_APP provides locally
1552 </message>

1571 <message name="IDS_SAFETY_CHECK_DESCRIPTION" desc="Introduces the safety check categories to the user. Followed by several items, such as 'Safe Browsing', 'Updates', 'Passwords'.">
1572: Koushik_APP can help keep you safe from data breaches, unsafe websites, and more
1573 </message>

1618 <message name="IDS_SAFETY_CHECK_PASSWORDS_ERROR" desc="Text to display when the password check has an unknown error.">
1619: Koushik_APP can’t check your passwords
1620 </message>
1621 <message name="IDS_SAFETY_CHECK_PASSWORDS_ERROR_OFFLINE" desc="Text to display when the password check has an unknown error.">
1622: Offline. Koushik_APP can’t check your passwords.
1623 </message>

1627 <message name="IDS_SAFETY_CHECK_PASSWORDS_ERROR_QUOTA_LIMIT" desc="Text to display when the password check hits the daily quota limit.">
1628: Koushik_APP couldn’t check all passwords
1629 </message>

1633 <message name="IDS_SAFETY_CHECK_UPDATES_UPDATED" desc="Text to display when the updates check confirms that the latest version is already installed.">
1634: Koushik_APP is up to date
1635 </message>
1636 <message name="IDS_SAFETY_CHECK_UPDATES_OUTDATED" desc="Text to display when the updates check detects a new version.">
1637: Koushik_APP is out of date
1638 </message>
1639 <message name="IDS_SAFETY_CHECK_UPDATES_OFFLINE" desc="Text to display when the updates check failed because of no connectivity.">
1640: Offline. Koushik_APP can’t check for updates.
1641 </message>
1642 <message name="IDS_SAFETY_CHECK_UPDATES_ERROR" desc="Text to display when the updates check failed for some reason.">
1643: Koushik_APP can’t check for updates
1644 </message>

1698 <message name="IDS_SAFE_BROWSING_STANDARD_PROTECTION_SUMMARY_UPDATED_PROXY" desc="Summary for Safe Browsing standard protection mode with proxy.">
1699: Protects against sites, downloads, and extensions that are known to be dangerous. When you visit a site, Koushik_APP sends an obfuscated portion of the URL to Google through a privacy server that hides your IP address. If a site does something suspicious, full URLs and bits of page content are also sent.
1700 </message>

1721 <message name="IDS_SAFE_BROWSING_ENHANCED_PROTECTION_BULLET_ONE_UPDATED" desc="First bullet point that describes the details of the Safe Browsing control.">
1722: Warns you about dangerous sites, even ones Google didn’t know about before, by analyzing more data from sites than standard protection. You can choose to skip Koushik_APP warnings.
1723 </message>
1724 <message name="IDS_SAFE_BROWSING_ENHANCED_PROTECTION_BULLET_TWO" desc="Second bullet point under the Safe Browsing enhanced protection mode">
1725: Keeps you safe on Koushik_APP and may be used to improve your security in other Google apps when you are signed in.
1726 </message>

1757 <message name="IDS_SAFE_BROWSING_ENHANCED_PROTECTION_LEARN_MORE_LABEL" desc="The text for a link to a help center article that gives more information about Safe Browsing.">
1758: Learn more about <ph name="BEGIN_LINK">&lt;link&gt;</ph>how Koushik_APP keeps your data private<ph name="END_LINK">&lt;/link&gt;</ph>
1759 </message>

1788 <message name="IDS_SAFE_BROWSING_STANDARD_PROTECTION_BULLET_TWO" desc="Second bullet point under the Safe Browsing standard protection mode.">
1789: Checks URLs with a list of unsafe sites stored in Koushik_APP. If a site tries to steal your password, or when you download a harmful file, Koushik_APP may also send URLs, including bits of page content, to Safe Browsing.
1790 </message>
1791 <message name="IDS_SAFE_BROWSING_STANDARD_PROTECTION_BULLET_TWO_PROXY" desc="Second bullet point under the Safe Browsing standard protection mode when proxy is enabled.">
1792: Sends an obfuscated portion of the URL to Google through a privacy server that hides your IP address. If a site tries to steal your password, or when you download a harmful file, Koushik_APP may also send URLs, including bits of page content, to Google.
1793 </message>

1818 </message>
1819: <message name="IDS_APP_LANGUAGE_TITLE" desc="Title of Language settings section to change Koushik_APP’s user interface language. [CHAR_LIMIT=32]">
1820: <ph name="APP_NAME">%1$s<ex>Koushik_APP</ex></ph>’s language
1821 </message>

1827 </message>
1828: <message name="IDS_LANGUAGES_SELECT" desc="Option in overflow menu on Language settings page to change Koushik_APP’s user interface language. [CHAR_LIMIT=32]">
1829 Select language

1836 </message>
1837: <message name="IDS_LANGUAGES_CONTENT_TITLE" desc="Title of Language settings section to add or remove preferred content languages. Content languages are selected by the user and tell Koushik_APP what language the user prefers webpage content in.  [CHAR_LIMIT=32]">
1838 Preferred languages
1839 </message>
1840: <message name="IDS_LANGUAGES_CONTENT_DESCRIPTION" desc="Description of Content language on the Language settings screen. Appears above a list of one or more languages that the user selects to tell Koushik_APP which languages they prefer webpage content in.">
1841 To show content in your preferred languages, the sites you visit can see your preferences
1842 </message>
1843: <message name="IDS_LANGUAGES_LIST_DESCRIPTION" desc="Description on the Languages settings screen. Appears above a list of one or more languages that the user selects, to tell Koushik_APP which languages they prefer to use to read website content.">
1844 Let websites know the languages you speak. They’ll show content in those languages, when possible.
1845 </message>
1846: <message name="IDS_LANGUAGES_OFFER_TRANSLATE_SWITCH" desc="Appears next to the 'offer to translate' switch that controls whether or not Koushik_APP will display the Google Translate UI on web pages that are not in the user's preferred language(s).">
1847 Offer to translate pages in other languages
1848 </message>
1849: <message name="IDS_LANGUAGES_SEND_TRANSLATE_SWITCH" desc="Appears next to the switch controlling whether or not Koushik_APP will offer to translate pages in other languages.  When enabled the Google Translate UI will be displayed on web pages that are not in the user's preferred language(s).">
1850 Offer to send pages in other languages to Google Translate
1851 </message>
1852: <message name="IDS_LANGUAGES_ITEM_OPTION_OFFER_TO_TRANSLATE" desc="Option in language item menu. User can click the 'Offer to translate' option to toggle whether they want Koushik_APP to translate pages in this language. [CHAR_LIMIT=32]">
1853 Offer to translate
1854 </message>
1855: <message name="IDS_LANGUAGES_SRP_TITLE" desc="Title of the dialog that explicitly asks the user what language they want Koushik_APP on Android to be in.">
1856: Pick Koushik_APP’s language
1857 </message>
1858: <message name="IDS_LANGUAGES_SRP_SUBTITLE" desc="Subtitle warning a user that the language of their keyboard will not change if they change the application language of Koushik_APP on Android.">
1859 Your keyboard won’t change

1866 </message>
1867: <message name="IDS_LANGUAGES_SPLIT_DOWNLOADING" desc="Text to display next to the native name of a language when it is being downloaded to use as Koushik_APP's UI language. The dash separates the native name from the description.">
1868 <ph name="LANG">%1$s<ex>हिन्दी</ex></ph> - Downloading…
  1869        </message>
  1870:       <message name="IDS_LANGUAGES_SPLIT_READY" desc="Text to display next to the native name of a language when it has been downloaded to use as Koushik_APP's UI language. The dash separates the native name from the description.">
  1871:         <ph name="LANG">%1$s<ex>हिन्दी</ex></ph> - Language ready, restart <ph name="APP_NAME">%2$s<ex>Koushik_APP</ex></ph>.
1872 </message>

1878 </message>
1879: <message name="IDS_LANGUAGES_INFOBAR_RESTART" desc="The clickable link letting the user know they can click to restart Koushik_APP. [CHAR_LIMIT=32]">
1880: Restart Koushik_APP
1881 </message>

2060  
 2061: <!-- About Koushik_APP preferences -->
2062: <message name="IDS_PREFS_ABOUT_WOOTZAPP" desc="Title for the About Koushik_APP page. [CHAR_LIMIT=32]">
2063: About Koushik_APP
2064 </message>

2070 </message>
2071: <message name="IDS_VERSION_WITH_UPDATE_TIME" desc="Message showing Koushik_APP's version and the time it was last updated">
2072: <ph name="VERSION">%1$s<ex>Koushik_APP 40.0.2214.67</ex></ph> (Updated <ph name="TIME_SINCE_UPDATE">%2$s<ex>5 minutes ago</ex></ph>)
2073 </message>

2076 </message>
2077: <message name="IDS_DEPRECATION_WARNING" desc="Warning about Koushik_APP updates no longer being supported">
2078: Koushik_APP updates are no longer supported for this version of Android
2079 </message>

2084 </message>
2085: <message name="IDS_ACCOUNT_MANAGEMENT_SIGN_OUT" desc="Button text for signing out of Koushik_APP">
2086: Sign out of Koushik_APP
2087 </message>

2138 </message>
2139: <message name="IDS_SYNC_IS_DISABLED_BY_ADMINISTRATOR" desc="Message to show when Koushik_APP sync is disabled by administrator">
2140 Sync is disabled by your administrator

2159 <message name="IDS_GOOGLE_TERMS_OF_SERVICE_TITLE" desc="Title for Google terms of service">
2160: Koushik_APP Terms of Service
2161 </message>
2162 <message name="IDS_GOOGLE_TERMS_OF_SERVICE_URL" desc="URL for Google terms of service" translateable="false">
2163: https://koushikbaagh.github.io/home
2164 </message>
2165 <message name="IDS_GOOGLE_TERMS_OF_SERVICE_DARK_MODE_URL" desc="URL for Google terms of service for dark mode" translateable="false">
2166: https://koushikbaagh.github.io/home
2167 </message>
2168: <message name="IDS_CHROME_ADDITIONAL_TERMS_OF_SERVICE_TITLE" desc="Title for Koushik_APP and ChromeOS addtional terms of service">
2169: Koushik_APP &amp; ChromeOS Additional Terms of Service
2170 </message>
2171: <message name="IDS_CHROME_ADDITIONAL_TERMS_OF_SERVICE_URL" desc="URL for Koushik_APP and ChromeOS additional terms of service" translateable="false">
2172: https://koushikbaagh.github.io/home
2173 </message>
2174: <message name="IDS_PRIVACY_POLICY_TITLE" desc="Title for the Koushik_APP privacy policy">
2175: Koushik_APP Privacy Policy
2176 </message>
2177: <message name="IDS_WOOTZAPP_PRIVACY_POLICY_URL" desc="URL for the Koushik_APP privacy policy" translateable="false">
2178: https://koushikbaagh.github.io/home
2179 </message>

2181 <!-- Sign-in strings -->
2182: <message name="IDS_SIGNOUT_TITLE" desc="The text is displayed as the title of a dialog to confirm if the user wants to sign out of Koushik_APP. The user can cancel and stay signed in, or confirm and sign out.">
2183: Sign out of Koushik_APP?
2184 </message>
2185: <message name="IDS_TURN_OFF_SYNC_AND_SIGNOUT_TITLE" desc="Title for sign out of Koushik_APP dialog [CHAR_LIMIT=40]">
2186 Sign out and turn off sync?

2190 </message>
2191: <message name="IDS_SIGNOUT_MANAGED_ACCOUNT_TITLE" desc="Title for sign out of Koushik_APP dialog for enterprise account [CHAR_LIMIT=40]">
2192: Delete your Koushik_APP data from this device?
2193 </message>
2194: <message name="IDS_SIGNOUT_MESSAGE" desc="The text is displayed as the message of a dialog to confirm whether the user wants to sign out of Koushik_APP. The dialog is titled ‘Sign out of Koushik_APP?’. The user can cancel and stay signed in, or confirm and sign out.">
2195: Some Koushik_APP features won\u2019t be available anymore
2196 </message>
2197 <message name="IDS_TURN_OFF_SYNC_AND_SIGNOUT_MESSAGE" desc="Message to display in 'Sign out and turn off sync?' dialog">
2198: Your bookmarks, history, passwords, and other Koushik_APP data will no longer be synced to your Google Account
2199 </message>
2200 <message name="IDS_TURN_OFF_SYNC_AND_SIGNOUT_MESSAGE_WITHOUT_PASSWORDS" desc="Message to display in 'Sign out and turn off sync?' dialog, without explicitly mentioning passwords. Similar to IDS_TURN_OFF_SYNC_AND_SIGNOUT_MESSAGE">
2201: Your bookmarks, history, and other Koushik_APP data will no longer be synced to your Google Account
2202 </message>
2203 <message name="IDS_REMOVE_LOCAL_DATA" desc="Checkbox to delete all existing data in local device storage">
2204: Also delete your Koushik_APP data from this device
2205 </message>
2206: <message name="IDS_SIGNOUT_MANAGED_ACCOUNT_MESSAGE" desc="Message to display for sign out of Koushik_APP dialog when the account has enterprise management, and all user data will be erased">
2207: Because you're signing out of an account managed by <ph name="DOMAIN_NAME">%1$s<ex>google.com</ex></ph>, your Koushik_APP data will be deleted from this device. It will remain in your Google Account.
2208 </message>

2211 </message>
2212: <message name="IDS_SIGN_OUT_UNSAVED_DATA_TITLE" desc="Title of a dialog shown to users when they sign out of Koushik_APP but Koushik_APP hasn't synced some data yet, which is permanently deleted if the user proceeds.">
2213 Some data isn\u2019t saved yet
2214 </message>
2215: <message name="IDS_SIGN_OUT_UNSAVED_DATA_MESSAGE" desc="Body of a dialog shown to users when they sign out of Koushik_APP but Koushik_APP hasn't synced some data yet, which is permanently deleted if the user proceeds.">
2216: Some of your Koushik_APP data hasn\u2019t been saved in your Google Account yet.\nTry waiting a few minutes before signing out. If you sign out now, this data will be deleted.
2217 </message>
2218: <message name="IDS_SIGN_OUT_UNSAVED_DATA_PRIMARY_BUTTON" desc="Button title of a dialog shown to users when they sign out of Koushik_APP but Koushik_APP hasn't synced some data yet, which is parmanently deleted if the user proceeds by pressing this button">
2219 Delete and sign out

2235 <message name="IDS_SIGN_IN_MANAGED_ACCOUNT_DESCRIPTION" desc="Description for signing in to managed accounts">
2236: You are signing in with an account managed by <ph name="MANAGED_DOMAIN">%1$s<ex>Google</ex></ph> and giving its administrator control over your Koushik_APP data. Your data will become permanently tied to this account. Signing out of Koushik_APP will delete your data from this device, but it will remain stored in your Google Account.
  2237        </message>
  2238        <message name="IDS_MANAGED_SIGNIN_WITH_USER_POLICY_SUBTITLE" desc="The subtitle of the Sign in with a managed account dialog when user policies are enabled.">
  2239:         Your organization, <ph name="MANAGED_DOMAIN">%1$s<ex>Google</ex></ph>, manages the account you're signing in to and how Koushik_APP can be used. Your administrator can set up or restrict certain features.
2240 </message>

2243 </message>
2244: <message name="IDS_ENABLE_SYNC_BUTTON" desc="Text that displayed or button that allows the user to open Koushik_APP settings to enable sync.">
2245 Open settings

2256 <message name="IDS_NTP_RECENT_TABS_SYNC_PROMO_INSTRUCTIONS" desc="Information about sync displayed on the NTP when the user has signed in on mobile but not on desktop">
2257: Tabs that you've opened in Koushik_APP on your other devices will appear here.
2258 </message>

2262 <message name="IDS_RECENT_TABS_SIGN_IN_ON_OTHER_DEVICES" desc="Text appearing on an empty recent tab page that indicates user can see tabs from other devices here">
2263: To see your tabs from wherever you use Koushik_APP, sign in on all your devices
2264 </message>

2336 <message name="IDS_SYNC_PASSPHRASE_TYPE_CUSTOM" desc="Option to encrypt sync data with a custom passphrase.">
2337: Use your own passphrase to encrypt all the Koushik_APP data in your Google Account
2338 </message>

2345 <message name="IDS_SYNC_ENCRYPTION_CREATE_PASSPHRASE" desc="Prompt user to create a custom sync password.">
2346: Payment methods and addresses from Google Pay won’t be encrypted. Browsing history from Koushik_APP won’t sync.
2347: Only someone with your passphrase can read your encrypted data. The passphrase is not sent to or stored by Google. If you forget your passphrase or want to change this setting, <ph name="BEGIN_LINK">BEGIN_LINK</ph>delete the Koushik_APP data in your account<ph name="END_LINK">END_LINK</ph>.
2348 </message>

2355 <message name="IDS_SYNC_ENTER_PASSPHRASE_BODY_WITH_EMAIL" desc="Instructions for the dialog where the user enters their Sync passphrase.">
2356: Your data is encrypted with your passphrase. Enter it to use and save Koushik_APP data in your Google Account.
2357 </message>

2364 <message name="IDS_SYNC_PASSPHRASE_RECOVER" desc="Inform the user how they can reset their passphrase if they have forgotten it." meaning="Android">
2365: If you forgot your passphrase or want to change this setting, <ph name="BEGIN_LINK">BEGIN_LINK</ph>delete the Koushik_APP data in your account<ph name="END_LINK">END_LINK</ph>.
2366 </message>

2372  
 2373: To change this setting, <ph name="BEGIN_LINK">BEGIN_LINK</ph>delete the Koushik_APP data in your account<ph name="END_LINK">END_LINK</ph>.
2374 </message>

2440 <message name="IDS_HINT_CLIENT_OUT_OF_DATE" desc="Hint message to resolve sync protocol error for out-of-date client.">
2441: Update <ph name="PRODUCT_NAME">%1$s<ex>Koushik_APP</ex></ph> to start sync
2442 </message>

2448 <message name="IDS_CLIENT_OUT_OF_DATE_ERROR_CARD_BUTTON" desc="Button text for client out of date error in sync error cards.">
2449: Update <ph name="PRODUCT_NAME">%1$s<ex>Koushik_APP</ex></ph>
2450 </message>

2471 <message name="IDS_SYNC_ERROR_UPGRADE_CLIENT" desc="Sync error string for out-of-date client. [CHAR_LIMIT=80]">
2472: <ph name="PRODUCT_NAME">%1$s<ex>Koushik_APP</ex></ph> is out of date.
2473 </message>

2488 <message name="IDS_IDENTITY_ERROR_CARD_PASSPHRASE_REQUIRED" desc="Error message to resolve passphrase required error.">
2489: To use and save Koushik_APP data in your Google Account, enter your passphrase
2490 </message>
2491 <message name="IDS_IDENTITY_ERROR_CARD_CLIENT_OUT_OF_DATE" desc="Error message to resolve sync protocol error for out-of-date client.">
2492: To use and save Koushik_APP data in your Google Account, update Koushik_APP
2493 </message>
2494 <message name="IDS_IDENTITY_ERROR_CARD_AUTH_ERROR" desc="Error message to resolve auth error.">
2495: To use and save Koushik_APP data in your Google Account, verify it’s you
2496 </message>
2497 <message name="IDS_IDENTITY_ERROR_CARD_SYNC_RETRIEVE_KEYS_FOR_EVERYTHING" desc="Error message to resolve sync encryption error, required to resume sync.">
2498: To use and save Koushik_APP data in your Google Account, verify it’s you
2499 </message>

2503 <message name="IDS_IDENTITY_ERROR_CARD_SYNC_RECOVERABILITY_DEGRADED_FOR_EVERYTHING" desc="Error message to resolve sync degraded recoverability, for users that have not chosen to encrypt all sync data.">
2504: To use and save Koushik_APP data in your Google Account, verify it’s you
2505 </message>

2522 <message name="IDS_IDENTITY_ERROR_MESSAGE_BODY" desc="Error message/notification to resolve passphrase required error, sync encryption error, auth error, outdated client error.">
2523: Keep using the Koushik_APP data in your Google Account
2524 </message>

2528 <message name="IDS_IDENTITY_ERROR_MESSAGE_BODY_SYNC_RECOVERABILITY_DEGRADED_FOR_EVERYTHING" desc="Error message/notification to resolve sync degraded recoverability, for users that have chosen to encrypt all sync data.">
2529: Make sure you can always use the Koushik_APP data in your Google Account
2530 </message>

2537 <message name="IDS_IDENTITY_ERROR_MESSAGE_TITLE_CLIENT_OUT_OF_DATE" desc="Error message/notification title for client out-of-date error.">
2538: Update Koushik_APP
2539 </message>

2598 </message>
2599: <message name="IDS_DOWNLOAD_MESSAGE_MULTIPLE_DOWNLOAD_IN_PROGRESS" desc="Download message text describing that Koushik_APP is downloading multiple files.">
2600 {FILE_COUNT, plural,

2650 </message>
2651: <message name="IDS_ERROR_PRINTING_FAILED" desc="Generic error message shown when Koushik_APP fails to print the current page for some reason.">
2652 There was a problem printing the page. Please try again.

2687 <!-- Runtime permission strings -->
2688: <message name="IDS_MISSING_STORAGE_PERMISSION_DOWNLOAD_EDUCATION_TEXT" desc="Text shown educating the user that Koushik_APP is missing the Android storage permission, which is required to download files.">
2689: Koushik_APP needs storage access to download files.
2690 </message>

2767 </message>
2768: <message name="IDS_CONTEXTMENU_OPEN_IN_NEW_CHROME_TAB" desc="Context sensitive menu item to open the selected link in a new Koushik_APP tab from Koushik_APP Custom Tab. [CHAR_LIMIT=30]">
2769: Open in new Koushik_APP tab
2770 </message>
2771: <message name="IDS_CONTEXTMENU_OPEN_IN_CHROME_INCOGNITO_TAB" desc="Context sensitive menu item to open the selected link in a Koushik_APP Incognito tab from Koushik_APP Custom Tab. [CHAR_LIMIT=30]">
2772 Open in Incognito tab

2886 <message name="IDS_UPDATE_NEEDED" desc="The help message is displayed on launch if an update is required to function.">
2887: Your device couldn’t open Koushik_APP. To fix the issue, download the latest Koushik_APP update from your app store.
2888 </message>

2914 </message>
2915: <message name="IDS_NOTIFICATION_MANAGE_BUTTON" desc="Text of a button shown on notifications, that opens the Koushik_APP notifications settings page. This allows users to edit notification settings when a site asks them to allow notifications. [CHAR_LIMIT=9]">
2916 Manage

3159 <message name="IDS_HISTORY_MANAGER_APP_SPECIFIC_EMPTY_STATE_DESCRIPTION" desc="Description text in app-specific history zero state that states history for a specific-app will be displayed here.">
3160: The pages you've opened in Koushik_APP while using <ph name="APP_LABEL">%1$s<ex>YouTube</ex></ph> will show up here.
3161 </message>

3166 <message name="IDS_HISTORY_MANAGER_EMPTY_STATE_VIEW_OR_OPEN_MORE_HISTORY" desc="Indicates that users can search something else or open more history">
3167: Try searching for something else or open full Koushik_APP history to see more results.
3168 </message>

3188 </message>
3189: <message name="IDS_HISTORY_OPEN_IN_CHROME" desc="App-specific history selection men item to open the selected link in Koushik_APP. [CHAR_LIMIT=30]">
3190: Open in new Koushik_APP tab
3191 </message>
3192: <message name="IDS_HISTORY_OPEN_IN_INCOGNITO_CHROME" desc="App-specific history selection men item to open the selected link in Koushik_APP in incognito mode. [CHAR_LIMIT=30]">
3193: Open in Incognito Koushik_APP tab
3194 </message>

3205 <message name ="IDS_INCOGNITO_REAUTH_PROMO_TITLE" desc="The title of the incognito re-auth promo card.">
3206: Lock Incognito tabs when you leave Koushik_APP
3207 </message>

3210 </message>
3211: <message name ="IDS_INCOGNITO_REAUTH_LOCK_ACTION_TEXT" desc="The label of the button which upon click would turn on the corresponding Koushik_APP level Incognito lock setting after a re-authentication.">
3212 Turn on Incognito lock

3214 <message name ="IDS_INCOGNITO_REAUTH_SNACKBAR_TEXT" desc="The label of the snackbar notification which appears after the incognito re-authentication is turned on from the promo card shown inside the Incognito grid tab switcher.">
3215: Incognito tabs will be locked when you leave Koushik_APP
3216 </message>

3230 <message name="IDS_FRE_ACTIVITY_LABEL" desc="Label for first run dialog in Android Recents.">
3231: Koushik_APP First Run Experience
3232 </message>
3233: <message name="IDS_LIGHTWEIGHT_FRE_ASSOCIATED_APP_TOS" desc="Message explaining that use of Koushik_APP is governed by Koushik_APP's terms of service.">
3234: <ph name="APP_NAME">%1$s<ex>Google Maps</ex></ph> will open in Koushik_APP. By continuing, you agree to the <ph name="BEGIN_LINK1">&lt;LINK1&gt;</ph>Google Terms of Service<ph name="END_LINK1">&lt;/LINK1&gt;</ph>, and the <ph name="BEGIN_LINK2">&lt;LINK2&gt;</ph>Koushik_APP and ChromeOS Additional Terms of Service<ph name="END_LINK2">&lt;/LINK2&gt;</ph>.
  3235        </message>
  3236:       <message name="IDS_LIGHTWEIGHT_FRE_ASSOCIATED_APP_TOS_AND_PRIVACY_CHILD_ACCOUNT" desc="Message explaining that use of Koushik_APP is governed by Koushik_APP's terms of service, and the Google Privacy Policy.">
  3237:         <ph name="APP_NAME">%1$s<ex>Google Maps</ex></ph> will open in Koushik_APP. By continuing, you agree to the <ph name="BEGIN_LINK1">&lt;LINK1&gt;</ph>Google Terms of Service<ph name="END_LINK1">&lt;/LINK1&gt;</ph>, and the <ph name="BEGIN_LINK2">&lt;LINK2&gt;</ph>Koushik_APP and ChromeOS Additional Terms of Service<ph name="END_LINK2">&lt;/LINK2&gt;</ph>. The <ph name="BEGIN_LINK3">&lt;LINK3&gt;</ph>Privacy Policy<ph name="END_LINK3">&lt;/LINK3&gt;</ph> also applies.
3238 </message>

3241 </message>
3242: <message name="IDS_FRE_WELCOME" desc="Text for greeting the user on Koushik_APP First Run">
3243: Welcome to Koushik_APP
3244 </message>

3252 <!-- Signin First Run strings -->
3253: <message name="IDS_SIGNIN_FRE_DISMISS_BUTTON" desc="Button on the very first screen of Koushik_APP to continue without signing into Koushik_APP. Ensure consistency with OneGoogle strings while still omitting “Koushik_APP” (see e.g. TC ID 5336438894576002929).">
3254 Use without an account
3255 </message>
3256: <message name="IDS_SIGNIN_FRE_FOOTER" desc="The text is displayed in a footer on the very first screen of Koushik_APP. The link ‘Terms of Service’ opens the Google Terms of Service. Preferably, ensure consistency with the “Usage statistics and crash reports” section of the Koushik_APP Privacy Policy (https://koushikbaagh.github.io/home). Separate the first and the second part through a line break.">
3257: By continuing, you agree to the <ph name="BEGIN_TOS_LINK">&lt;TOS_LINK&gt;</ph>Terms of Service<ph name="END_TOS_LINK">&lt;/TOS_LINK&gt;</ph>.\nTo help improve the app, Koushik_APP sends usage and crash data to Google. <ph name="BEGIN_UMA_LINK">&lt;UMA_LINK&gt;</ph>Manage<ph name="END_UMA_LINK">&lt;/UMA_LINK&gt;</ph>
3258 </message>
3259: <message name="IDS_SIGNIN_FRE_FOOTER_TOS" desc="The text is displayed in a footer on the very first screen of Koushik_APP. The link ‘Terms of Service’ opens the Google Terms of Service.">
3260 By continuing, you agree to the <ph name="BEGIN_TOS_LINK">&lt;TOS_LINK&gt;</ph>Terms of Service<ph name="END_TOS_LINK">&lt;/TOS_LINK&gt;</ph>.
3261 </message>
3262: <message name="IDS_SIGNIN_FRE_FOOTER_METRICS_REPORTING" desc="The text is displayed in a footer on the very first screen of Koushik_APP. Preferably, ensure consistency with the “Usage statistics and crash reports” section of the Koushik_APP Privacy Policy (https://koushikbaagh.github.io/home).">
3263: To help improve the app, Koushik_APP sends usage and crash data to Google. <ph name="BEGIN_UMA_LINK">&lt;UMA_LINK&gt;</ph>Manage<ph name="END_UMA_LINK">&lt;/UMA_LINK&gt;</ph>
3264 </message>
3265: <message name="IDS_SIGNIN_FRE_UMA_DIALOG_TITLE" desc="Title of the dialog where users can change their Koushik_APP metric sharing settings, like usage data. This appears when they open the Koushik_APP app for the first time on their phone.">
3266: Make Koushik_APP better
3267 </message>

3271 <message name="IDS_SIGNIN_FRE_UMA_DIALOG_FIRST_SECTION_BODY" desc="Text that describes the benefits users will get if they turn on the metrics sharing option.">
3272: Help make Koushik_APP better for people who use it the way you do
3273 </message>

3277 <message name="IDS_SIGNIN_FRE_UMA_DIALOG_SECOND_SECTION_BODY" desc="Text with info about the data that users share with Google if they turn on the metric sharing option.">
3278: Info is sent to Google about your Koushik_APP usage, but it isn\u2019t tied to you\n\nIf Koushik_APP crashes, details about the crash may include some personal info\n\nIf you turn on sync, metrics may also include info about URLs you visit
3279 </message>

3281 <message name="IDS_SIGNIN_FRE_TITLE" translateable="false">
3282: Make Koushik_APP your own
3283 </message>
3284: <message name="IDS_SIGNIN_FRE_SUBTITLE" desc="Subtitle shown below a welcoming title on the very first screen after opening Koushik_APP for the first time. Asks the user to sign in to Koushik_APP with their Google Account to get more useful features when they're signed in across multiple devices (like phones and computers). Try to limit translations to 50 characters. Do not exceed 75 characters.">
3285 Sign in to browse easier across devices

3314 </message>
3315: <message name="IDS_DEVICE_LOCK_NOTICE" desc="Notice appearing on the profile lock page informing users that data saved on Koushik_APP will be erased if they remove the profile lock from the device.">
3316 Turning off your profile lock will remove your saved info

3328 </message>
3329: <message name="IDS_MISSING_DEVICE_LOCK_DESCRIPTION" desc="Text description explaining that a profile lock is required on automotive devices, and that sensitive personal data will be deleted from the profile if the user continues to Koushik_APP without re-creating a profile lock.">
3330: Opening Koushik_APP without a profile lock will remove your saved passwords and payment methods from the car. Using a profile lock keeps this data secure.
3331 </message>
3332: <message name="IDS_MISSING_DEVICE_LOCK_REMOVE_LOCAL_DATA" desc="Option given to the user to delete all Koushik_APP profile data, particularly mentioning bookmarks and history.">
3333 Also delete bookmarks, history, and more from this car
3334 </message>
3335: <message name="IDS_DELETE_AND_CONTINUE" desc="Text for the button that will delete any sensitive data and then navigate the user back to Koushik_APP.">
3336 Delete &amp; continue

3394 <message name="IDS_SIGNIN_ACCOUNT_PICKER_BOTTOM_SHEET_TITLE_FOR_SEND_TAB_TO_SELF" desc="The title for the bottom sheet that shows the list of accounts on the device and asks the user to select one of these accounts, when send-tab-to-self triggered the UI. [CHAR_LIMIT=27]">
3395: Sign in to Koushik_APP
3396 </message>
3397 <message name="IDS_ACCOUNT_PICKER_BOTTOM_SHEET_ACCESSIBILITY_OPENED" is_accessibility_with_no_ui="true" desc="The accessibility text to read when account picker bottom sheet is opened.">
3398: Sign in to Koushik_APP, opened.
3399 </message>
3400 <message name="IDS_ACCOUNT_PICKER_BOTTOM_SHEET_ACCESSIBILITY_CLOSED" is_accessibility_with_no_ui="true" desc="The accessibility text to read when account picker bottom sheet is closed.">
3401: Sign in to Koushik_APP, closed.
3402 </message>
3403 <message name="IDS_SIGNIN_ACCOUNT_PICKER_BOTTOM_SHEET_SUBTITLE" desc="The subtitle for the account picker bottom sheet that tells the user what happens if the button 'Continue as John Doe' is clicked">
3404: Sign in to this site and Koushik_APP
3405 </message>
3406 <message name="IDS_SIGNIN_ACCOUNT_PICKER_BOTTOM_SHEET_SUBTITLE_FOR_SEND_TAB_TO_SELF" desc="The subtitle for the account picker bottom sheet that tells the user what happens if the button 'Continue as John Doe' is clicked, when send-tab-to-self triggered the UI.">
3407: To send this tab to another device, sign in to Koushik_APP on both devices
3408 </message>

3427 <message name="IDS_SIGNIN_ACCOUNT_PICKER_BOTTOM_SHEET_TITLE_FOR_BACK_OF_CARD_MENU_SIGNIN" desc="The title for the bottom sheet that shows the list of accounts on the device and asks the user to select one of these accounts, when signin from BoC triggered the UI. [CHAR_LIMIT=27]">
3428: Sign in to Koushik_APP
3429 </message>

3432 </message>
3433: <message name="IDS_SIGNIN_ACCOUNT_PICKER_BOTTOM_SHEET_BENEFITS_SUBTITLE" desc="This string is on a sign-in page, after the user taps on a promotion about signing in to Koushik_APP with the user's Google Account. It explains the overarching user benefit of signing in (access to bookmarks, passwords, history, settings, etc.). We want users to understand why signing in is beneficial, and click 'Continue as name' to sign in to their Google Account. The tone should be informative and lightweight.">
3434 Get your bookmarks, passwords, and more on all your devices

3445 <!-- Personalized Signin Promos Strings -->
3446: <message name="IDS_SYNC_PROMO_CONTINUE_AS" desc="Button to sign into Koushik_APP with the displayed account and without having to reenter a password. ‘John’ is replaced with the user’s given name, or the user’s full name if the given name is not available. Ensure consistency with related OneGoogle sign-in buttons (see e.g. TC ID 5569230012177947065).">
3447 Continue as <ph name="USER_FULL_NAME">%1$s<ex>John</ex></ph>
  3448        </message>
  3449:       <message name="IDS_SYNC_PROMO_CONTINUE" desc="Button to sign into Koushik_APP, similar to IDS_SYNC_PROMO_CONTINUE_AS. Used when the user's display names are not available and the email address cannot be displayed.">
  3450          Continue
  3451        </message>
  3452:       <message name="IDS_SIGNIN_PROMO_CHOOSE_ACCOUNT" desc="Button that the user can press if they are not the profile that Koushik_APP found (opposite of 'Continue as Joe Doe').">
  3453          Not <ph name="EMAIL">%1$s<ex>john.doe@example.com</ex></ph>?

3455 <!-- Strings for signin promos when Unified Consent is enabled. -->
3456: <message name="IDS_SYNC_PROMO_TITLE_BOOKMARKS" desc="This string is the headline of a card that appears when the user opens Koushik_APP's bookmarks; the user may be signed in to Koushik_APP, but isn't syncing their Koushik_APP data. The line below this string is 'Sync to get your bookmarks from your other devices'. [CHAR_LIMIT=70]" meaning="This headline means that the user can get the bookmarks from their computer on their phone, and their phone's bookmarks on their computer. We want users to read this card and tap the 'Continue' button and turn on sync. The tone should be inviting.">
3457 Get all your bookmarks
3458 </message>
3459: <message name="IDS_SYNC_PROMO_DESCRIPTION_BOOKMARKS" desc="This string is the body of a card that appears when the user opens Koushik_APP's bookmarks; the user may be signed in to Koushik_APP, but isn't syncing their Koushik_APP data. The headline above this string is 'Get all your bookmarks'. There's no character limit but try to keep the translation under 120 characters." meaning="This message means that the user can get the bookmarks from their computer on their phone, and their phone's bookmarks on their computer. We want users to read this card and tap the 'Continue' button and turn on sync. The tone should be inviting.">
3460 Sync to get your bookmarks from your other devices
3461 </message>
3462: <message name="IDS_SIGNIN_PROMO_TITLE_BOOKMARKS" desc="This string is the headline of a card that appears when the user opens Koushik_APP's bookmarks; the user may be signed in to Koushik_APP, but isn't syncing their Koushik_APP data. The line below this string is 'Sync to get your bookmarks from your other devices'. [CHAR_LIMIT=70]" meaning="This headline means that the user can get the bookmarks from their computer on their phone, and their phone's bookmarks on their computer. We want users to read this card and tap the 'Continue' button and sign-in. The tone should be inviting.">
3463 Get all your bookmarks
3464 </message>
3465: <message name="IDS_SIGNIN_PROMO_DESCRIPTION_BOOKMARKS" desc="This string is the body of a card that appears when the user opens Koushik_APP's bookmarks; the user is signed out of Koushik_APP. The headline above this string is 'Get all your bookmarks'. There's no character limit but try to keep the translation under 120 characters." meaning="This message means that the user can get the bookmarks from their computer on their phone, and their phone's bookmarks on their computer. We want users to read this card and tap the 'Continue' button and sign-in. The tone should be inviting.">
3466 Sign in to get your bookmarks and more from your other devices
3467 </message>
3468: <message name="IDS_SYNC_PROMO_TITLE_NTP_CONTENT_SUGGESTIONS" desc="This string is the headline of a card that appears when the user visits Koushik_APP's new tab page; the user may be signed in to Koushik_APP, but isn't syncing their Koushik_APP data. The line below this string is 'Sync to get the most relevant content from Google'. [CHAR_LIMIT=70]" meaning="This headline means that the user is missing out on more interesting and relevant news articles. We want users to read this card and tap the 'Continue' button and turn on sync. The tone should be inviting.">
3469 Get better suggestions
3470 </message>
3471: <message name="IDS_SYNC_PROMO_DESCRIPTION_NTP_CONTENT_SUGGESTIONS" desc="This string is the body of a card that appears when the user visits Koushik_APP's new tab page; the user may be signed in to Koushik_APP, but isn't syncing their Koushik_APP data. The headline above this string is 'See stories for you'. There's no character limit but try to keep the translation under 120 characters." meaning="This message means that the user is missing out on more interesting and relevant news articles. We want users to read this card and tap the 'Continue' button and turn on sync. The tone should be inviting.">
3472 Sync to get the most relevant content from Google
3473 </message>
3474: <message name="IDS_SIGNIN_PROMO_TITLE_NTP_FEED_TOP_PROMO" desc="This string is the headline of a card that appears when the user visits Koushik_APP's new tab page; the user isn't signed in to Koushik_APP. The line below this string is 'Sign in to get content based on your interests'. [CHAR_LIMIT=70]">
3475 Get better content
3476 </message>
3477: <message name="IDS_SIGNIN_PROMO_DESCRIPTION_NTP_FEED_TOP_PROMO" desc="This string is the body of a card that appears when the user visits Koushik_APP's new tab page; the user isn't signed in to Koushik_APP. The headline above this string is 'Get better content'. There's no character limit but try to keep the translation under 120 characters." meaning="This message means that the user is missing out on more interesting and relevant news articles. We want users to read this card and tap the 'Continue' button and sign-in. The tone should be inviting.">
3478 Sign in to get content based on your interests
3479 </message>
3480: <message name="IDS_SYNC_PROMO_TITLE_RECENT_TABS" desc="This string is the headline of a card that appears when the user opens Koushik_APP's recent tabs. The user may be signed in to Koushik_APP, but isn't syncing their Koushik_APP data. The line below this string is 'Sync to get your tabs from your other devices'. [CHAR_LIMIT=70]" meaning="This headline means that the user can see some of their recent tabs from their computer on their phone, and their phone's recent tabs on their computer. We want users to read this card and tap the 'Continue' button and turn on sync. The tone should be inviting.">
3481 Get all your tabs

3485 </message>
3486: <message name="IDS_SYNC_PROMO_DESCRIPTION_RECENT_TABS" desc="This string is the body of a card that appears when the user opens Koushik_APP's recent tabs. The user may be signed in to Koushik_APP, but isn't syncing their Koushik_APP data. There's no character limit but try to keep the translation under 120 characters." meaning="The headline above this string is 'Continue from another device'. This message means that the user can see some of their recent tabs from their computer on their phone, and their phone's recent tabs on their computer. We want users to read this card and tap the 'Continue' button and turn on sync. The tone should be inviting.">
3487 Sync to get your tabs from your other devices

3491 </message>
3492: <message name="IDS_SYNC_PROMO_TITLE_SETTINGS" desc="This string is the headline of a card that appears when the user opens Koushik_APP's settings; the user may be signed in to Koushik_APP, but isn't syncing their Koushik_APP data. The line below this string is 'Sync to get your passwords, bookmarks and more on all your devices'. [CHAR_LIMIT=70]" meaning="This headline means that the user can use Koushik_APP more easily by syncing their passwords, bookmarks, settings, and more.. We want users to read this card and tap the 'Continue' button and turn on sync. The tone should be inviting.">
3493: Use Koushik_APP your way
3494 </message>
3495: <message name="IDS_SYNC_PROMO_DESCRIPTION_SETTINGS" desc="This string is the body of a card that appears when the user opens Koushik_APP's settings; the user may be signed in to Koushik_APP, but isn't syncing their Koushik_APP data. The headline above this string is 'Browse more easily'. There's no character limit but try to keep the translation under 120 characters." meaning="This message means that the user can use Koushik_APP more easily by syncing their passwords, bookmarks, settings, and more.. We want users to read this card and tap the 'Continue' button and turn on sync. The tone should be inviting.">
3496 Sync to get your passwords, bookmarks and more on your other devices

3506 </message>
3507: <message name="IDS_SIGNIN_SETTINGS_TITLE" desc="Title of the sign-in row in the settings page that offers the user to sign-in to Koushik_APP.">
3508 Sign in
3509 </message>
3510: <message name="IDS_SIGNIN_SETTINGS_SUBTITLE" desc="Subtitle of the sign-in row in the settings page that offers the user to sign-in to Koushik_APP. It explains the overarching user benefit of signing in (access to bookmarks, passwords, history, settings, etc.).">
3511 Get your bookmarks, passwords and more on all your devices

3513  
 3514: <message name="IDS_EXTERNAL_APP_RESTRICTED_ACCESS_ERROR" desc="A message shown to the user if Koushik_APP receives a file view request to something Koushik_APP does not have access to view.">
3515: Koushik_APP does not have access to the requested resource.
3516 </message>

3702 desc="Title in the feed header for user-customized following feed. This feed is composed of articles and content from sites that the user has followed">Following</message>
3703: <message name="IDS_NTP_FEED_MENU_IPH" desc="In-product help that points at the menu icon for the news feed on Koushik_APP's new tab page. This string instructs the user to open the menu for settings that let them control the content that appears on the feed.">
3704 Control your stories and activity here

3709 </message>
3710: <message name="IDS_ACCESSIBILITY_NTP_FEED_MENU_IPH" desc="In-product help that points at the menu icon for the news feed on Koushik_APP's new tab page. This string instructs the user to open the menu for settings that let them control the content that appears on the feed. Please use the branded term for Discover (TC ID 1799975766543019278).">
3711 Control your stories from the Options for Discover button

3728 <message name="IDS_WEB_FEED_NO_CARDS_INSTRUCTIONS" desc="Message body for the user-customizable web feed on the New Tab Page. Shown when the user either has not followed any websites or when the user has followed some websites but the sites do not have any new articles. Instructs the user to follow more sites or check back later. Please translate 'Follow' (with capital F) to match its use in TC ID 4108314971463891922.">
3729: To follow a site, go to the site, open the Koushik_APP menu, and tap Follow.
3730 </message>

3789 <message name="IDS_CUSTOM_TAB_HISTORY_IPH_BUBBLE_TEXT" desc="The message on the text bubble shown to educate the user about history in CCTs.">
3790: View your Koushik_APP history here
3791 </message>

3862 <!-- Main menu items -->
3863: <message name="IDS_MENU_UPDATE" desc="Menu item for updating Koushik_APP. [CHAR_LIMIT=24]">
3864: Update Koushik_APP
3865 </message>
3866: <message name="IDS_MENU_UPDATE_SUMMARY_DEFAULT" desc="Summary string for update menu item explaining that a newer version of Koushik_APP is available. [CHAR_LIMIT=30]">
3867 Newer version is available
3868 </message>
3869: <message name="IDS_MENU_UPDATE_UNSUPPORTED" desc="Menu item for when Koushik_APP can not be updated. [CHAR_LIMIT=24]">
3870: Koushik_APP can’t update
3871 </message>

3911 <message name="IDS_CHROME_HISTORY" desc="Menu item for opening the CCT history page. [CHAR_LIMIT=27]">
3912: Koushik_APP history
3913 </message>

3942 </message>
3943: <message name="IDS_ACCESSIBILITY_FOLLOW_ACCELERATOR_IPH" desc="In-product help that points at the menu icon for the news feed on Koushik_APP's new tab page. This string informs the user about the  following feature.">
3944 Adds the current web site to the list of web sites that you are following.

3948 </message>
3949: <message name="IDS_MENU_REQUEST_DESKTOP_SITE" desc="Menu item in Koushik_APP's overflow/options menu. By default, when a user navigates to a web page, Koushik_APP shows the mobile site, that is, the version of the site designed for mobile phones. If this menu item is selected, however, Koushik_APP will try to load the 'desktop' site instead, i.e. the site designed for desktop computers or laptop computers, which have larger screens. [CHAR_LIMIT=24]">
3950 Desktop site

3957 </message>
3958: <message name="IDS_MENU_AUTO_DARK_WEB_CONTENTS" desc="Menu item in Koushik_APP's overflow/options menu. When Koushik_APP's browser UI is set to dark theme and this option is checked, sites will have a dark theme automatically applied as well. [CHAR_LIMIT=24]">
3959 Dark theme

4010 <message name="IDS_BOOKMARK_PAGE_SAVED" desc="App-based message shown after user adds a new bookmark. [CHAR_LIMIT=32]">
4011: Bookmarked in <ph name="PRODUCT_NAME">%1$s<ex>Koushik_APP</ex></ph>
4012 </message>

4094 <message name="IDS_BOOKMARK_PAGE_SAVED_LOCATION" desc="App-based message shown after user adds a new bookmark to specify the location of a bookmark. [CHAR_LIMIT=32]">
4095: in <ph name="PRODUCT_NAME">%1$s<ex>Koushik_APP</ex></ph>
4096 </message>

4275 {NUM_IN_PROGRESS, plural,
4276: =1 {Koushik_APP will load your page when ready}
4277: other {Koushik_APP will load your pages when ready}}
4278 </message>
4279  
 4280: <message name="IDS_OFFLINE_PAGES_AUTO_FETCH_READY_NOTIFICATION_TEXT" desc="Text inside a notification explaining that the page has been fetched and is ready to view. This is the subtext of the notification and appars below the web page title. When the notification is tapped, the page is opened in Koushik_APP.">
4281 Page is ready to view

4321 </message>
4322: <message name="IDS_MENU_OPEN_IN_CHROME" desc="Context sensitive menu item for opening a link in Koushik_APP. [CHAR_LIMIT=30]">
4323: Open in Koushik_APP browser
4324 </message>
4325: <message name="IDS_MENU_OPEN_IN_INCOGNITO_CHROME" desc="Context sensitive menu item for opening a link in Koushik_APP in an Incognito tab. [CHAR_LIMIT=30]" translateable="false">
4326: Open in Incognito Koushik_APP
4327 </message>
4328 <message name="IDS_MENU_OPEN_IN_PRODUCT" desc="App menu item for opening link in the browser. [CHAR_LIMIT=40]">
4329: Open in <ph name="PRODUCT_NAME">%1$s<ex>Koushik_APP</ex></ph> browser
4330 </message>

4345 </message>
4346: <message name="IDS_CONTENT_PROVIDER_SEARCH_DESCRIPTION" desc="Description for Koushik_APP's entry in QSB's list of search suggestion providers [CHAR_LIMIT=32]">
4347 Bookmarks and web history

4349  
 4350: <!-- Koushik_APP survey -->
4351: <message name="IDS_CHROME_SURVEY_MESSAGE_TITLE" desc="Message shown that invites the user to take a survey about Koushik_APP. 'Help' and 'improve' are imperative verbs.">
4352: Help improve Koushik_APP?
4353 </message>
4354: <message name="IDS_CHROME_SURVEY_MESSAGE_BUTTON" desc="The label for the button to open a survey for Koushik_APP.">
4355 Take survey

4365 <message name="IDS_RDS_WINDOW_SETTING_MESSAGE_TITLE" desc="Title of the message shown after window setting changes the page layout from desktop to mobile.">
4366: Koushik_APP will request the mobile site when the screen is narrow
4367 </message>

4371 <message name="IDS_RDS_APP_MENU_USER_EDUCATION_DIALOG_TITLE" desc="Title of the dialog shown to educate the user about the desktop site app menu site-level setting.">
4372: Koushik_APP will remember your choice
4373 </message>

4385  
 4386: <message name="IDS_ACCESSIBILITY_TOOLBAR_BTN_MENU_UPDATE" desc="Content description for the menu button when it is covered by the update icon that is displayed when a newer version of Koushik_APP is available.">
4387 Update available. More options

4389 <message name="IDS_ACCESSIBILITY_TOOLBAR_BTN_MENU_OS_VERSION_UNSUPPORTED" desc="Content description for the menu button when it is covered by the warning icon that is displayed when the current Android OS version is unsupported.">
4390: Koushik_APP can’t update. More options
4391 </message>

4620 <!-- MultiWindow -->
4621: <message name="IDS_UNSUPPORTED_NUMBER_OF_WINDOWS" desc="Popup message for when the user has tried to start too many concurrent versions of Koushik_APP.">
4622: Unsupported number of Koushik_APP instances.
4623 </message>
4624: <message name="IDS_MAX_NUMBER_OF_WINDOWS" desc="Toast message for when the user has tried to start more than 5 instances of Koushik_APP window.">
4625 You can have up to 5 windows.

4636 <message name="IDS_OVERSCROLL_NAVIGATION_CLOSE_CHROME" desc="Message displayed on overscroll navigation UI widget when the back navigation is attempted at the beginning of navigation history stack. The widget only has an arrow icon but expands to display this message next to it.">
4637: Close <ph name="APP_NAME">%1$s<ex>Koushik_APP</ex></ph>
4638 </message>

4782 <!-- Storage Preference UI strings for clearing storage. -->
4783: <message name="IDS_STORAGE_MANAGEMENT_ACTIVITY_LABEL" desc="Title for Koushik_APP's Manage Space Activity.">
4784: Google <ph name="APP_NAME">%1$s<ex>Koushik_APP</ex></ph> storage
4785 </message>
4786 <message name="IDS_STORAGE_MANAGEMENT_UNIMPORTANT_SITE_DATA_DESCRIPTION" desc="Text to describe the data stored by unimportant or infrequent sites.">
4787: Stored data that Koushik_APP doesn't think is important (e.g. sites with no saved settings or that you don't visit often)
4788 </message>

4791 </message>
4792: <message name="IDS_STORAGE_MANAGEMENT_CLEAR_UNIMPORTANT_SITE_DATA_BUTTON" desc="Text on the button to clear all Koushik_APP data. [CHAR_LIMIT=30]">
4793 Free up space

4795 <message name="IDS_STORAGE_MANAGEMENT_CLEAR_UNIMPORTANT_DIALOG_TEXT" desc="Text of the clear unimportant site data dialog in the storage UI.">
4796: This will clear cookies, cache, and other data of sites Koushik_APP doesn't think is important.
4797 </message>

4803 </message>
4804: <message name="IDS_STORAGE_MANAGEMENT_STARTUP_FAILURE" desc="String shown in place of the data usage when starting the Koushik_APP native process failed. [CHAR_LIMIT=30]">
4805 Unknown

4812 </message>
4813: <message name="IDS_STORAGE_MANAGEMENT_ALL_STORAGE_DESCRIPTION" desc="Text used to describe all storage space used by Koushik_APP.">
4814: Total data used by Koushik_APP, including accounts, bookmarks, and saved settings
4815 </message>
4816: <message name="IDS_STORAGE_MANAGEMENT_CLEAR_ALL_DATA_BUTTON" desc="Text on the button to clear all Koushik_APP data. [CHAR_LIMIT=30]">
4817 Clear All Data

4822 <message name="IDS_STORAGE_MANAGEMENT_RESET_APP_DIALOG_TEXT" desc="Text of the reset app dialoag in the storage UI.">
4823: All Koushik_APP’s app data will be deleted permanently. This includes all files, settings, accounts, databases, etc.
4824 </message>

4844 <message name="IDS_SOGOU_EXPLANATION" desc="Text explaining why Sogou should be used as default search engine.">
4845: Koushik_APP can use <ph name="BEGIN_BOLD">&lt;b&gt;</ph>Sogou<ph name="END_BOLD">&lt;/b&gt;</ph> for search in China. You can change this in <ph name="BEGIN_LINK">&lt;link&gt;</ph>Settings<ph name="END_LINK">&lt;/link&gt;</ph>.
4846 </message>

4857 <!-- WebAPK/TWA related strings -->
4858: <message name="IDS_TWA_RUNNING_IN_CHROME" desc="Message on a snackbar indicating that the current Activity may use Koushik_APP data (the rest of the app may not be).">
4859: Running in Koushik_APP
4860 </message>
4861: <message name="IDS_TWA_RUNNING_IN_CHROME_TEMPLATE" desc="Message template that used to indicating that the current Activity may use Koushik_APP data (the rest of the app may not be). [CHAR_LIMIT=32]">
4862: Running in <ph name="APP_NAME">%1$s<ex>Koushik_APP</ex></ph>
  4863        </message>
  4864:       <message name="IDS_TWA_RUNNING_IN_CHROME_V2" desc="Updated message on a snackbar indicating that the current Activity may use Koushik_APP data (the rest of the app may not be).">
  4865:         You'll see your <ph name="SITE_NAME">%1$s<ex>www.youtube.com</ex></ph> sign-in status, browsing data, and site data in Koushik_APP
4866 </message>
4867 <message name="IDS_TWA_CLEAR_DATA_DIALOG_TITLE" desc="Title of the clear data dialog showing after user uninstalls or clears data of an app hosting a Trusted Web Activity">
4868: <ph name="APP_NAME">%1$s<ex>YouTube</ex></ph> also has data in Koushik_APP
4869 </message>
4870 <message name="IDS_TWA_CLEAR_DATA_DIALOG_MESSAGE" desc="Message of the delete data dialog">
4871: You can delete the data in Koushik_APP Settings
4872 </message>

4893 <!-- Keyboard shortcuts in Android N-->
4894: <message name="IDS_KEYBOARD_SHORTCUT_OPEN_NEW_WINDOW" desc="A text label that appears next to the keyboard shortcut to open a new window in Koushik_APP. The shortcut description is shown in a system dialog along with all other supported shortcuts. [CHAR_LIMIT=55]">
4895 Open a new window
4896 </message>
4897: <message name="IDS_KEYBOARD_SHORTCUT_OPEN_NEW_TAB" desc="A text label that appears next to the keyboard shortcut to open a new tab in Koushik_APP. The shortcut description is shown in a system dialog along with all other supported shortcuts. [CHAR_LIMIT=55]">
4898 Open a new tab
4899 </message>
4900: <message name="IDS_KEYBOARD_SHORTCUT_REOPEN_NEW_TAB" desc="A text label that appears next to the keyboard shortcut for reopening the last tab in the Koushik_APP app. The shortcut description is shown in a system dialog along with all other supported shortcuts. [CHAR_LIMIT=55]">
4901 Reopen the last closed tab
4902 </message>
4903: <message name="IDS_KEYBOARD_SHORTCUT_NEW_INCOGNITO_TAB" desc="A text label that appears next to a keyboard shortcut to open a new tab in Incognito mode in Koushik_APP. The shortcut description is shown in a system dialog along with all other supported shortcuts. [CHAR_LIMIT=55]">
4904 Open a new tab in Incognito mode
4905 </message>
4906: <message name="IDS_KEYBOARD_SHORTCUT_OPEN_MENU" desc="A text label that appears next to a keyboard shortcut that opens the overflow menu in Koushik_APP. The shortcut description is shown in a system dialog along with all other supported shortcuts. [CHAR_LIMIT=55]">
4907 Open the menu
4908 </message>
4909: <message name="IDS_KEYBOARD_SHORTCUT_NEXT_TAB" desc="A text label that appears next to the keyboard shortcut that will move the user to the next tab in the Koushik_APP app. The shortcut description is shown in a system dialog along with all other supported shortcuts. [CHAR_LIMIT=55]">
4910 Jump to the next tab
4911 </message>
4912: <message name="IDS_KEYBOARD_SHORTCUT_PREV_TAB" desc="A text label that appears next to the keyboard shortcut that will move the user to the previous tab in the Koushik_APP app. The shortcut description is shown in a system dialog along with all other supported shortcuts. [CHAR_LIMIT=55]">
4913 Jump to the previous tab
4914 </message>
4915: <message name="IDS_KEYBOARD_SHORTCUT_CLOSE_TAB" desc="A text label that appears next to the keyboard shortcut that will close the current tab in Koushik_APP. The shortcut description is shown in a system dialog along with all other supported shortcuts. [CHAR_LIMIT=55]">
4916 Close current tab

4923 </message>
4924: <message name="IDS_KEYBOARD_SHORTCUT_BOOKMARK_MANAGER" desc="A text label that appears next to the keyboard shortcut that will open the bookmarks manager in Koushik_APP. On a tablet this is a new tab, on the phone this is a new activity. The shortcut description is shown in a system dialog along with all other supported shortcuts. [CHAR_LIMIT=55]">
4925 Open the bookmarks manager

4950 </message>
4951: <message name="IDS_KEYBOARD_SHORTCUT_HELP_CENTER" desc="A text label that appears next to the keyboard shortcut that will open the Google Koushik_APP Help Center in a new tab. The shortcut description is shown in a system dialog along with all other supported shortcuts. [CHAR_LIMIT=55]">
4952: Open the Koushik_APP Help Center in a new tab
4953 </message>

4956 </message>
4957: <message name="IDS_KEYBOARD_SHORTCUT_CHROME_FEATURE_GROUP_HEADER" desc="A text label that appears above a list of shortcuts that are related to the Koushik_APP app features. This group is part of several groups of keyboard shortcuts all shown in a dialog.">
4958: Google Koushik_APP feature shortcuts
4959 </message>

4965 <!-- AR module -->
4966: <message name="IDS_AR_MODULE_TITLE" desc="Text shown when the AR module is referenced in install start, success, failure UI (e.g. in IDS_MODULE_INSTALL_START_TEXT, which will expand to 'Installing Augmented Reality for Koushik_APP…').">
4967 Augmented Reality

4971 <!-- Dynamic feature modules -->
4972: <message name="IDS_MODULE_INSTALL_START_TEXT" desc="Text shown on a toast when Koushik_APP starts to download a dynamic feature module.">
4973: Installing <ph name="module">%1$s<ex>augmented reality</ex></ph> for Koushik_APP…
  4974        </message>
  4975:       <message name="IDS_MODULE_INSTALL_SUCCESS_TEXT" desc="Text shown on a toast when Koushik_APP successfully installed a dynamic feature module.">
  4976          Installed
  4977        </message>
  4978:       <message name="IDS_MODULE_INSTALL_FAILURE_TEXT" desc="Text shown on an infobar when Koushik_APP failed to install a dynamic feature module.">
  4979:         Unable to install <ph name="module">%1$s<ex>augmented reality</ex></ph> for Koushik_APP
4980 </message>

5027 <message name="IDS_INSTANCE_SWITCHER_ALREADY_RUNNING_FOREGROUND" desc="Toast message to show when user tries to switch to a window that is already running in the foreground.">
5028: Koushik_APP is already running here.
5029 </message>

5076 </message>
5077: <message name="IDS_IPH_INSTANCE_SWITCHER_TEXT" desc="The in-product-help text prompting the user that app menu has a menu for managing multiple Koushik_APP windows with instance switcher.">
5078 Got many windows? You can manage them from here

5140 <message name="IDS_DINO_WIDGET_TEXT" desc="Text displayed on the Dino Widget. One medium-length or two short words max (area for about 10em)">
5141: Koushik_APP Dino
5142 </message>

5189 <message name="IDS_SEND_TAB_TO_SELF_V2_TOAST" desc="Toast message shown after a device is selected from the device picker.">
5190: Page sent. To see it, open Koushik_APP on your <ph name="device_type">%1$s<ex>phone</ex></ph>
5191 </message>

5195 <message name="IDS_SEND_TAB_TO_SELF_ANDROID_NO_TARGET_DEVICE_LABEL" desc="Text shown when a user with no available target devices attempts to use send-tab-to-self.">
5196: To send this tab to another device, sign in to Koushik_APP there
5197 </message>

5248 <!-- Sms Fetcher -->
5249: <message name="IDS_SMS_FETCHER_NOTIFICATION_TITLE" desc="Title text shown when the Android Koushik_APP receives a ONE_TIME_CODE from an incoming SMS and ask users for permission to submit the code to their linked Desktop Koushik_APP">
5250 Submit <ph name="ONE_TIME_CODE">%1$s<ex>123</ex></ph> on <ph name="CLIENT_NAME">%2$s<ex>Zoe's Macbook</ex></ph>?

5258  
 5259: <message name="IDS_SMS_FETCHER_NOTIFICATION_TITLE_SIMPLE_STRING" desc="Title text shown when the Android Koushik_APP receives a ONE_TIME_CODE from an incoming SMS and ask users for permission to submit the code to ORIGIN">
5260 Submit <ph name="ONE_TIME_CODE">%1$s<ex>123</ex></ph> to <ph name="ORIGIN">%2$s<ex>example.com</ex></ph>?

5273 <message name="IDS_NEAR_OOM_INTERVENTION_MESSAGE" desc="The message stating that the browser intervened to stop the page using too much memory.">
5274: This page uses too much memory, so Koushik_APP paused it.
5275 </message>

5279 <!-- Usage Stats strings -->
5280: <message name="IDS_USAGE_STATS_CONSENT_TITLE" desc="Title for activity authorizing Digital Wellbeing to access Koushik_APP usage data">
5281: Show your Koushik_APP activity in Digital Wellbeing?
5282 </message>
5283: <message name="IDS_USAGE_STATS_CONSENT_PROMPT" desc="Consent prompt when authorizing Digital Wellbeing to access Koushik_APP usage data">
5284: You can see sites you visit in Koushik_APP and set timers for them.\n\nGoogle gets info about the sites you set timers for and how long you visit them. This info is used to make Digital Wellbeing better.
5285 </message>
5286: <message name="IDS_USAGE_STATS_SETTING_TITLE" desc="Title for setting removing Digital Wellbeing's access to Koushik_APP usage data">
5287: Remove your Koushik_APP activity from Digital Wellbeing
5288 </message>
5289: <message name="IDS_USAGE_STATS_REVOCATION_PROMPT" desc="Prompt for removing Digital Wellbeing's access to Koushik_APP usage data">
5290: Remove your Koushik_APP activity from Digital Wellbeing?
5291 </message>
5292: <message name="IDS_USAGE_STATS_REVOCATION_EXPLANATION" desc="Explanation of the effect of revoking Digital Wellbeing's access to Koushik_APP usage data">
5293: Sites you visit in Koushik_APP won't show. All site timers will be deleted.
5294 </message>

5302 <!-- Tab Group Tab Switcher strings -->
5303: <message name="IDS_TAB_MANAGEMENT_MODULE_TITLE" desc="Text shown when the Tab Management module is referenced in install start, success, failure UI (e.g. in IDS_MODULE_INSTALL_START_TEXT, which will expand to 'Installing Tab management for Koushik_APP…').">
5304 Tab management

5306  
 5307: <message name="IDS_DEV_UI_MODULE_TITLE" desc="Text shown when the Developer UI module is referenced in install start, success, failure UI (e.g. in IDS_MODULE_INSTALL_START_TEXT, which will expand to 'Installing Developer UI for Koushik_APP…').">
5308 Developer UI

5314 failure UI (e.g. in IDS_MODULE_INSTALL_START_TEXT, which will expand to
5315: 'Installing Test Dummy for Koushik_APP…').">
5316 Test Dummy

5321 failure UI (e.g. in IDS_MODULE_INSTALL_START_TEXT, which will expand to
5322: 'Installing Stack Unwinder for Koushik_APP…').">
5323 Stack Unwinder

5329 IDS_MODULE_INSTALL_START_TEXT, which will expand to 'Installing Phone as a
5330: Security Key Support for Koushik_APP…'). A security key is usually a physical piece of
5331 hardware used for authentication and this feature is about using a mobile

5336 <message name="IDS_CABLEV2_ACTIVITY_TITLE"
5337: desc="The label of the Activity for using your phone as a security key. A 'security key' in this context is generally a small USB device that is used for logging into websites. This feature allows Koushik_APP on an Android phone to act as a security key. A user may see it in Android permissions prompts (see screenshot).">
5338 Google Chrome as a Security Key

5388  
 5389: <message name="IDS_CABLEV2_SERVERLINK_STATUS_DFM_INSTALL" desc="A small subheader on a screen that is shown when a user is connecting their phone to a desktop or laptop computer in order to sign in with it. This text is shown while Koushik_APP is downloading the component that can complete the connection.">
5390: Updating Koushik_APP to connect to other devices
5391 </message>

5400  
 5401: <message name="IDS_CABLEV2_ERROR_BLE_PERMISSION" desc="The description of an error shown when the user is trying to use their phone to sign into a website on a laptop, but the user denied Koushik_APP the permission it needs to do this. Below this message is a button that will open the Settings app where the user can grant the permission. 'Nearby devices' is the name of the specific permission in Settings that needs to be granted. It is TC ID 5529147543651181991 and, ideally, the same wording that will appear in Settings would be used here.">
5402: <ph name="PRODUCT_NAME">%1$s<ex>Koushik_APP</ex></ph> needs Nearby devices permission in order to connect to your device
5403 </message>

5440  
 5441: <message name="IDS_CABLEV2_PAASK_BODY" desc="The subheading of an entry in settings for controlling how a phone can be used as a security key. A security key is typically a physical USB peripheral used to secure accounts. In this case, the user's phone can act as a security key. 'Devices' here means phones, laptops, and desktops that the user uses Koushik_APP on.">
5442 Control which devices can sign in by using this device as a security key.

5444  
 5445: <message name="IDS_CABLEV2_YOUR_DEVICES" desc="A section title on a screen discussing the different devices that can use a phone as a security key. 'Devices' here means phones, laptops, and desktops that the user uses Koushik_APP on.">
5446 Your devices

5448  
 5449: <message name="IDS_CABLEV2_YOUR_DEVICES_BODY" desc="Text that appears under the title 'Your devices'. 'Devices' here means phones, laptops, and desktops that the user uses Koushik_APP on. Users can sign into a Google account in Koushik_APP on these devices and this message explains that such devices can use this phone as a security key. A security key is typically a physical USB peripheral used to secure accounts. In this case, the user's phone can act as a security key.">
5450 When you’re signed into the same Google Account, other devices can use this phone as a security key.

5452  
 5453: <message name="IDS_CABLEV2_LINKED_DEVICES" desc="A section title on a screen discussing the different devices that can use a phone as a security key. The section above this discusses how devices (e.g. phones, laptops, and desktops) on which Koushik_APP is signed into the same Google account can automatically use this phone as a security key. This section is about devices that the user has scanned QR codes from in order to allow them to use this phone as a security key. The word 'linked' here was chosen to be distinct from 'paired' as in 'Bluetooth pairing'. This technology does use Bluetooth, but we did not want to overload the term 'pairing'. However, the word 'pairing' does have the correct meaning.">
5454 Linked devices

5655 <!-- Chime DFM module strings -->
5656: <message name="IDS_CHIME_MODULE_TITLE" desc="Text shown when the chime module is referenced in install start, success, failure UI (e.g. in IDS_MODULE_INSTALL_START_TEXT, which will expand to 'Installing Google Notifications Platform for Koushik_APP…').">
5657 Google Notifications Platform

5660 <!-- Image Editor DFM module strings -->
5661: <message name="IDS_IMAGE_EDITOR_MODULE_TITLE" desc="Text shown when the image editor module is referenced in install start, success, failure UI (e.g. in IDS_MODULE_INSTALL_START_TEXT, which will expand to 'Installing Image Editor for Koushik_APP…').">
5662 Image Editor

5665 <!-- Survey DFM module strings -->
5666: <message name="IDS_SURVEY_MODULE_TITLE" desc="Text shown when the surveys module is referenced in install start, success, failure UI (e.g. in IDS_MODULE_INSTALL_START_TEXT, which will expand to 'Installing Surveys for Koushik_APP…').">
5667 Surveys

5699 <!-- Browser Promo Notification Strings -->
5700: <message name="IDS_CHROME_REENGAGEMENT_NOTIFICATION_1_TITLE" desc="The title of a notification shown to suggest that users use Koushik_APP.  Users probably have not opened Koushik_APP in a while.  Promotes relevant articles Koushik_APP has.">
5701 Read today's news <ph name="NEWS_ICON">📰</ph>
5702 </message>
5703: <message name="IDS_CHROME_REENGAGEMENT_NOTIFICATION_1_DESCRIPTION" desc="The body text of a notification shown to suggest that users use Koushik_APP.  Users probably have not opened Koushik_APP in a while.  Promotes relevant articles Koushik_APP has.">
5704: Articles on your interests on Koushik_APP
5705 </message>
5706: <message name="IDS_CHROME_REENGAGEMENT_NOTIFICATION_2_TITLE" desc="The title of a notification shown to suggest that users use Koushik_APP.  Users probably have not opened Koushik_APP in a while.  Promotes data savings.">
5707 Save up to 60% data
5708 </message>
5709: <message name="IDS_CHROME_REENGAGEMENT_NOTIFICATION_2_DESCRIPTION" desc="The body text of a notification shown to suggest that users use Koushik_APP.  Users probably have not opened Koushik_APP in a while.  Promotes data savings.">
5710: Use Lite mode on Koushik_APP
5711 </message>
5712: <message name="IDS_CHROME_REENGAGEMENT_NOTIFICATION_3_TITLE" desc="The title of a notification shown to suggest that users use Koushik_APP.  Users probably have not opened Koushik_APP in a while.">
5713 Google recommends Chrome
5714 </message>
5715: <message name="IDS_CHROME_REENGAGEMENT_NOTIFICATION_3_DESCRIPTION" desc="The title of a notification shown to suggest that users use Koushik_APP.  Users probably have not opened Koushik_APP in a while.  Promotes data savings and relevant news.">
5716 Save up to 60% data, read today's news

5720 <message name="IDS_NOTIFICATION_PERMISSION_RATIONALE_DIALOG_TITLE" desc="The title of a dialog shown to users before asking for notification permission.">
5721: Koushik_APP notifications make things easier
5722 </message>
5723: <message name="IDS_NOTIFICATION_PERMISSION_RATIONALE_DIALOG_MESSAGE" desc="The body text of a dialog explaining the benefits of enabling Koushik_APP notifications.">
5724 You’ll be able to easily manage media controls, Incognito sessions, downloads and more

5909 <message name="IDS_AUTO_DARK_MESSAGE_TITLE" desc="Message shown that informs the user auto darkening of website contents has been enabled.">
5910: Dark theme for sites is on in Koushik_APP
5911 </message>

5950 <message name="IDS_MANAGEMENT_BROWSER_NOTICE" desc="The descriptive text on chrome://management page that explains to the user the implications of browsing under a managed environment.">
5951: Your administrator can change your browser setup remotely. Activity on this device may also be managed outside of Koushik_APP.
5952 </message>

6250 <message name="IDS_DIGITAL_IDENTITY_INTERSTITIAL_HIGH_RISK_DIALOG_TEXT" translateable="false">
6251: <ph name="WEBSITE_ORIGIN">%1$s<ex>www.cheapalcohol.com</ex></ph> would like to ask Android for access to your identity. Koushik_APP cannot determine what privacy risks this may pose.
6252 </message>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_af.xtb:

    55  <translation id="124116460088058876">Meer tale</translation>
    56: <translation id="1241792820757384812">Jou wagwoorde sal van Google Wagwoordbestuurder vir <ph name="KOUSHIK_CHANNEL" /> uitgevee word. Jy sal die wagwoordlêer wat jy sopas afgelaai het, behou.</translation>
    57  <translation id="1242883863226959074">toestel</translation>

118 <translation id="1571304935088121812">Kopieer gebruikernaam</translation>
119: <translation id="1584648915421894279">Wagwoorde wat op hierdie toestel gestoor is, kan tans nie oor Chrome-kanale gebruik word nie. Ná Chrome 125 sal wagwoorde wat op jou toestel vir Chrome en <ph name="KOUSHIK_CHANNEL" /> gestoor is, saamgevoeg word en in albei apps gebruik kan word.</translation>
120 <translation id="1592864538817356322">Standaardbeskerming:</translation>

688 <translation id="4601095002996233687">Omvattende skanderings vir verdagte aflaaie.</translation>
689: <translation id="4609429330876432068">Jou lyste gestoorde wagwoorde vir Chrome en <ph name="KOUSHIK_CHANNEL" /> is saamgevoeg. Jy kan steeds al jou gestoorde wagwoorde op albei apps outomaties invul.</translation>
690 <translation id="4616150815774728855">Maak <ph name="WEBAPK_NAME" /> oop</translation>

1653 <translation id="930124987204876019">Vee geskiedenis, webkoekies, werfdata, kasgeheue uit …</translation>
1654: <translation id="93533588269984624">Alle wagwoorde sal op jou toestel afgelaai word en van <ph name="KOUSHIK_CHANNEL" /> verwyder word</translation>
1655 <translation id="938850635132480979">Fout: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_am.xtb:

    55  <translation id="124116460088058876">ተጨማሪ ቋንቋዎች</translation>
    56: <translation id="1241792820757384812">የእርስዎ የይለፍ ቃላት ለ<ph name="KOUSHIK_CHANNEL" /> ከGoogle የይለፍ ቃል አስተዳዳሪ ይሰረዛሉ። አሁን ያወረዷቸውን የይለፍ ቃላት ፋይል ያቆያሉ።</translation>
    57  <translation id="1242883863226959074">መሣሪያ</translation>

118 <translation id="1571304935088121812">የተጠቃሚ ስምን ቅዳ</translation>
119: <translation id="1584648915421894279">በአሁን ጊዜ በዚህ መሣሪያ ላይ የተቀመጡ የይለፍ ቃላት በመላ የChrome ሰርጦች ላይ ጥቅም ላይ መዋል አይችሉም። ከChrome 125 በኋላ በመሣሪያዎ ላይ ለChrome እና ለ<ph name="KOUSHIK_CHANNEL" /> የተቀመጡ የይለፍ ቃላ ይዋሃዳሉ እና በሁለቱም መተግበሪያዎች ላይ ጥቅም ላይ መዋል ይችላሉ።</translation>
120 <translation id="1592864538817356322">መደበኛ ጥበቃ፦</translation>

688 <translation id="4601095002996233687">ለሚያጠራጥሩ ውርዶች በጥልቀት የሚደረጉ ቅኝቶች።</translation>
689: <translation id="4609429330876432068">ለChrome እና ለ<ph name="KOUSHIK_CHANNEL" /> የተቀመጡ የይለፍ ቃላት ዝርዝርዎ ተዋህዷል። በሁለቱም መተግበሪያዎች ላይ ሁሉንም የተቀመጡ የይለፍ ቃላትዎ በራስ-ሰር መሙላት ይችላሉ።</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" />ን ይክፈቱ</translation>

1653 <translation id="930124987204876019">ታሪክ፣ ኩኪዎች፣ የጣቢያ ውሂብ፣ መሸጎጫን ሰርዝ…</translation>
1654: <translation id="93533588269984624">ሁሉም የይለፍ ቃላት በመሣሪያዎ ላይ ይወርዳሉ እና ከ<ph name="KOUSHIK_CHANNEL" /> ይወገዳሉ</translation>
1655 <translation id="938850635132480979">ስህተት፦ <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_ar.xtb:

    55  <translation id="124116460088058876">مزيد من اللغات</translation>
    56: <translation id="1241792820757384812">‏سيتم حذف كلمات المرور من "مدير كلمات المرور في Google" في <ph name="KOUSHIK_CHANNEL" />. وستتمكَّن من الاحتفاظ بملف كلمات المرور الذي نزّلته.</translation>
    57  <translation id="1242883863226959074">جهاز</translation>

118 <translation id="1571304935088121812">نسخ اسم المستخدم</translation>
119: <translation id="1584648915421894279">‏في الوقت الحالي، لا يمكن استخدام كلمات المرور المحفوظة على هذا الجهاز في جميع قنوات Chrome. في إصدارات Chrome الأحدث من إصدار 125، سيتم دمج كلمات المرور المحفوظة على جهازك في Chrome و"<ph name="KOUSHIK_CHANNEL" />" وستتمكّن من استخدامها في كلا التطبيقَين.</translation>
120 <translation id="1592864538817356322">الحماية العادية:</translation>

690 <translation id="4601095002996233687">يفحص هذا الوضع عمليات التنزيل المريبة بشكل مفصَّل.</translation>
691: <translation id="4609429330876432068">‏تم دمج قوائم كلمات المرور المحفوظة في Chrome مع "<ph name="KOUSHIK_CHANNEL" />". وسيظل بإمكانك ملء جميع كلمات المرور المحفوظة تلقائيًا في كلا التطبيقين.</translation>
692 <translation id="4616150815774728855">فتح <ph name="WEBAPK_NAME" /></translation>

1657 <translation id="930124987204876019">حذف السجلّ وملفات تعريف الارتباط وبيانات المواقع الإلكترونية وذاكرة التخزين المؤقت…</translation>
1658: <translation id="93533588269984624">سيتم تنزيل جميع كلمات المرور على جهازك وإزالتها من "<ph name="KOUSHIK_CHANNEL" />".</translation>
1659 <translation id="938850635132480979">الخطأ: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_as.xtb:

    55  <translation id="124116460088058876">অধিক ভাষা</translation>
    56: <translation id="1241792820757384812"><ph name="KOUSHIK_CHANNEL" />ৰ বাবে আপোনাৰ পাছৱৰ্ডসমূহ Google Password Managerৰ পৰা মচি পেলোৱা হ’ব। আপুনি এইমাত্ৰ ডাউনল’ড কৰা পাছৱৰ্ড ফাইলটো ৰাখিব।</translation>
    57  <translation id="1242883863226959074">ডিভাইচ</translation>

118 <translation id="1571304935088121812">ব্যৱহাৰকাৰীৰ নামটোৰ প্ৰতিলিপি কৰক</translation>
119: <translation id="1584648915421894279">এই মুহূৰ্তত, এই ডিভাইচত ছেভ কৰি থোৱা পাছৱৰ্ডসমূহ Chromeৰ চেনেলসমূহত ব্যৱহাৰ কৰিব নোৱাৰি। Chrome 125ৰ পাছত, আপোনাৰ ডিভাইচত Chrome আৰু <ph name="KOUSHIK_CHANNEL" />ৰ বাবে ছেভ কৰি থোৱা পাছৱৰ্ডসমূহ একত্ৰিত কৰা হ’ব আৰু সেইসমূহ দুয়োটা এপতে ব্যৱহাৰ কৰিব পৰা যাব।</translation>
120 <translation id="1592864538817356322">মান্য সুৰক্ষা:</translation>

688 <translation id="4601095002996233687">সন্দেহজনক ডাউনল’ডৰ বাবে বিস্তাৰিত স্কেনৰ সুবিধা</translation>
689: <translation id="4609429330876432068">Chrome আৰু <ph name="KOUSHIK_CHANNEL" />ৰ বাবে ছেভ কৰি থোৱা আপোনাৰ পাছৱৰ্ডৰ সূচীসমূহ একত্ৰিত কৰা হৈছে। আপুনি দুয়োটা এপতে আপোনাৰ আটাইবোৰ ছেভ কৰি থোৱা পাছৱৰ্ড তথাপি স্বয়ংক্ৰিয়ভাৱে পূৰ কৰিব পাৰিব।</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> খোলক</translation>

1653 <translation id="930124987204876019">ইতিহাস, কুকি, ছাইটৰ ডেটা, কেশ্ব মচক…</translation>
1654: <translation id="93533588269984624">আটাইবোৰ পাছৱৰ্ড আপোনাৰ ডিভাইচত ডাউনল’ড কৰা হ’ব আৰু <ph name="KOUSHIK_CHANNEL" />ৰ পৰা আঁতৰোৱা হ’ব</translation>
1655 <translation id="938850635132480979">আসোঁৱাহ: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_az.xtb:

    55  <translation id="124116460088058876">Digər dillər</translation>
    56: <translation id="1241792820757384812"><ph name="KOUSHIK_CHANNEL" /> üçün parollar Google Parol Menecerindən silinəcək. İndicə endirilən parol faylını saxlayacaqsınız.</translation>
    57  <translation id="1242883863226959074">cihaz</translation>

118 <translation id="1571304935088121812">İstifadəçi adını kopyalayın</translation>
119: <translation id="1584648915421894279">Bu cihazda yadda saxlanan parollar Chrome kanallarında istifadə edilə bilməz. Chrome 125-dən sonra Chrome və <ph name="KOUSHIK_CHANNEL" /> üçün cihazda yadda saxlanan parollar birləşdiriləcək və hər iki tətbiqdə istifadə edilə biləcək.</translation>
120 <translation id="1592864538817356322">Standart qoruma:</translation>

688 <translation id="4601095002996233687">Şübhəli endirmələr üçün hərtərəfli skanlama.</translation>
689: <translation id="4609429330876432068">Chrome və <ph name="KOUSHIK_CHANNEL" /> üzrə yadda saxlanılmış parolların siyahısı birləşdirildi. Hər iki tətbiqdə yadda saxlanılmış bütün parolları yenə də avtomatik doldura bilərsiniz.</translation>
690 <translation id="4616150815774728855">Açın: <ph name="WEBAPK_NAME" /></translation>

1651 <translation id="930124987204876019">Tarixçə, kuki, sayt datası və keşi silin…</translation>
1652: <translation id="93533588269984624">Bütün parollar cihaza endiriləcək və <ph name="KOUSHIK_CHANNEL" /> kanalından silinəcək</translation>
1653 <translation id="938850635132480979">Xəta: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_be.xtb:

    55  <translation id="124116460088058876">Іншыя мовы</translation>
    56: <translation id="1241792820757384812">Вашы паролі будуць выдалены з Менеджара пароляў Google для праграмы "<ph name="KOUSHIK_CHANNEL" />". Файл з паролямі, які вы зараз спампавалі, застанецца ў вас.</translation>
    57  <translation id="1242883863226959074">прыладзе</translation>

118 <translation id="1571304935088121812">Капіраваць імя карыстальніка</translation>
119: <translation id="1584648915421894279">Пакуль што паролі, захаваныя на гэтай прыладзе, нельга выкарыстоўваць ва ўсіх каналах Chrome. Пасля Chrome 125 паролі, захаваныя на прыладзе для Chrome і <ph name="KOUSHIK_CHANNEL" />, будуць аб'яднаны, і іх можна будзе выкарыстоўваць у абедзвюх праграмах.</translation>
120 <translation id="1592864538817356322">Стандартная абарона:</translation>

688 <translation id="4601095002996233687">Выконвае дэталёвую праверку падазроных спамповак.</translation>
689: <translation id="4609429330876432068">Вашы спісы захаваных пароляў для Chrome і версіі "<ph name="KOUSHIK_CHANNEL" />" былі аб'яднаны. Вы і далей можаце выкарыстоўваць аўтазапаўненне для ўсіх захаваных пароляў у абедзвюх праграмах.</translation>
690 <translation id="4616150815774728855">Адкрыць <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Ачысціць гісторыю, файлы cookie, даныя сайта, кэш…</translation>
1654: <translation id="93533588269984624">Усе паролі будуць спампаваны на вашу прыладу і выдалены з праграмы "<ph name="KOUSHIK_CHANNEL" />"</translation>
1655 <translation id="938850635132480979">Памылка: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_bg.xtb:

    55  <translation id="124116460088058876">Още езици</translation>
    56: <translation id="1241792820757384812">Паролите ви ще бъдат изтрити от Google Мениджър на пароли за <ph name="KOUSHIK_CHANNEL" />. Ще запазите току-що изтегления файл с пароли.</translation>
    57  <translation id="1242883863226959074">устройството</translation>

118 <translation id="1571304935088121812">Копиране на потребителското име</translation>
119: <translation id="1584648915421894279">Понастоящем паролите, запазени на това устройство, не могат да се използват във всички канали на Chrome. От версия 125 на браузъра паролите, запазени от Chrome и <ph name="KOUSHIK_CHANNEL" /> на устройството ви, ще бъдат обединени и ще могат да се използват и в двете приложения.</translation>
120 <translation id="1592864538817356322">Стандартна защита:</translation>

688 <translation id="4601095002996233687">Задълбочено сканиране за подозрителни изтегляния.</translation>
689: <translation id="4609429330876432068">Списъците ви със запазени пароли за Chrome и <ph name="KOUSHIK_CHANNEL" /> бяха обединени. Пак можете да попълвате автоматично всичките си запазени пароли и в двете приложения.</translation>
690 <translation id="4616150815774728855">Отваряне на <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Изтриване на историята, „бисквитките“, данните за сайтове и кеша…</translation>
1654: <translation id="93533588269984624">Всички пароли ще бъдат изтеглени на устройството ви и премахнати от <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Грешка: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_bn.xtb:

    55  <translation id="124116460088058876">আরও ভাষা</translation>
    56: <translation id="1241792820757384812"><ph name="KOUSHIK_CHANNEL" />-এর জন্য Google Password Manager থেকে আপনার পাসওয়ার্ড মুছে ফেলা হবে। এই মাত্র ডাউনলোড করা পাসওয়ার্ড ফাইল আপনি রেখে দেবেন।</translation>
    57  <translation id="1242883863226959074">ডিভাইস</translation>

118 <translation id="1571304935088121812">ইউজারনেম কপি করুন</translation>
119: <translation id="1584648915421894279">এখনই, এই ডিভাইসে সেভ করা পাসওয়ার্ড Chrome চ্যানেল জুড়ে ব্যবহার করা যাবে না। Chrome 125 ভার্সনের পরে, আপনার ডিভাইসে Chrome ও <ph name="KOUSHIK_CHANNEL" />-এর জন্য সেভ করা পাসওয়ার্ড মার্জ করা হবে এবং দুটি অ্যাপেই ব্যবহার করা যাবে।</translation>
120 <translation id="1592864538817356322">স্ট্যান্ডার্ড সুরক্ষা:</translation>

688 <translation id="4601095002996233687">এই সুবিধা সন্দেহজনক ডাউনলোড যাচাই করতে ভালভাবে স্ক্যান করে।</translation>
689: <translation id="4609429330876432068">Chrome ও <ph name="KOUSHIK_CHANNEL" />-এর জন্য সেভ করা পাসওয়ার্ডের তালিকা মার্জ করা হয়েছে। আপনি দুটি অ্যাপেই নিজের সেভ করা সব পাসওয়ার্ড এখনও অটোফিল করতে পারবেন।</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> খুলুন</translation>

1653 <translation id="930124987204876019">ইতিহাস, কুকি, সাইট ডেটা, ক্যাশে মুছুন…</translation>
1654: <translation id="93533588269984624">আপনার ডিভাইসে সবকটি পাসওয়ার্ড ডাউনলোড করা হবে এবং <ph name="KOUSHIK_CHANNEL" /> থেকে সরিয়ে দেওয়া হবে</translation>
1655 <translation id="938850635132480979">ত্রুটি: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_bs.xtb:

    55  <translation id="124116460088058876">Više jezika</translation>
    56: <translation id="1241792820757384812">Lozinke će se izbrisati s Google upravitelja lozinki za <ph name="KOUSHIK_CHANNEL" />. Zadržat ćete fajl lozinki koji ste upravo preuzeli.</translation>
    57  <translation id="1242883863226959074">uređaj</translation>

118 <translation id="1571304935088121812">Kopiranje korisničkog imena</translation>
119: <translation id="1584648915421894279">Trenutno se lozinke koje su sačuvane na uređaju ne mogu koristiti na Chromeovim kanalima. Nakon Chromeove verzije 125 lozinke sačuvane na vašem uređaju za Chrome i kanal <ph name="KOUSHIK_CHANNEL" /> će se spojiti i moći će se koristiti u obje aplikacije.</translation>
120 <translation id="1592864538817356322">Standardna zaštita:</translation>

688 <translation id="4601095002996233687">Detaljna skeniranja radi provjere sumnjivih preuzimanja.</translation>
689: <translation id="4609429330876432068">Liste sačuvanih lozinki za Chrome i kanal <ph name="KOUSHIK_CHANNEL" /> su spojene. I dalje možete automatski popunjavati sve sačuvane lozinke u obje aplikacije.</translation>
690 <translation id="4616150815774728855">Otvori <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Brisanje historije, kolačića, podataka web lokacija, keš memorije…</translation>
1654: <translation id="93533588269984624">Sve lozinke će se preuzeti na uređaj i ukloniti iz preglednika <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Greška: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_ca.xtb:

    55  <translation id="124116460088058876">Més idiomes</translation>
    56: <translation id="1241792820757384812">Les teves contrasenyes se suprimiran del gestor de contrasenyes de Google per a <ph name="KOUSHIK_CHANNEL" />. Conservaràs el fitxer de contrasenyes que acabes de baixar.</translation>
    57  <translation id="1242883863226959074">dispositiu</translation>

118 <translation id="1571304935088121812">Copia el nom d'usuari</translation>
119: <translation id="1584648915421894279">Ara mateix, les contrasenyes desades en aquest dispositiu no es poden utilitzar en tots els canals de Chrome. Després de la versió 125 de Chrome, les contrasenyes desades al dispositiu per a Chrome i <ph name="KOUSHIK_CHANNEL" /> es combinaran i es podran utilitzar en totes dues aplicacions.</translation>
120 <translation id="1592864538817356322">Protecció estàndard:</translation>

688 <translation id="4601095002996233687">Anàlisis detallades per comprovar si hi ha baixades sospitoses.</translation>
689: <translation id="4609429330876432068">Les teves llistes de contrasenyes desades per a Chrome i <ph name="KOUSHIK_CHANNEL" /> s'han combinat. Pots continuar emplenant automàticament les contrasenyes desades en totes dues aplicacions.</translation>
690 <translation id="4616150815774728855">Obre <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Suprimeix l'historial, les galetes, les dades dels llocs web, la memòria cau…</translation>
1654: <translation id="93533588269984624">Totes les contrasenyes es baixaran al teu dispositiu i se suprimiran de <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Error: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_cs.xtb:

    55  <translation id="124116460088058876">Další jazyky</translation>
    56: <translation id="1241792820757384812">Vaše hesla budou smazána ze Správce hesel Google pro <ph name="KOUSHIK_CHANNEL" />. Soubor s hesly, který jste právě stáhli, vám zůstane.</translation>
    57  <translation id="1242883863226959074">zařízení</translation>

118 <translation id="1571304935088121812">Kopírovat uživatelské jméno</translation>
119: <translation id="1584648915421894279">Hesla uložená na tomto zařízení v současné době nelze používat v různých kanálech Chromu. Po verzi Chromu 125 budou hesla uložená ve vašem zařízení pro Chrome a pro <ph name="KOUSHIK_CHANNEL" /> sloučena a bude je možné používat v obou těchto aplikacích.</translation>
120 <translation id="1592864538817356322">Standardní ochrana:</translation>

688 <translation id="4601095002996233687">Hloubkové kontroly podezřelých souborů ke stažení.</translation>
689: <translation id="4609429330876432068">Vaše seznamy uložených hesel pro Chrome a <ph name="KOUSHIK_CHANNEL" /> byly sloučeny. V obou aplikacích můžete stále automaticky vyplňovat všechna uložená hesla.</translation>
690 <translation id="4616150815774728855">Do aplikace <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Vymazat historii, soubory cookie, data webů, mezipaměť…</translation>
1654: <translation id="93533588269984624">Všechna hesla budou stažena do vašeho zařízení a odstraněna z <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Chyba: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_cy.xtb:

    55  <translation id="124116460088058876">Rhagor o ieithoedd</translation>
    56: <translation id="1241792820757384812">Bydd eich cyfrineiriau'n cael eu dileu o Reolwr Cyfrineiriau Google ar gyfer <ph name="KOUSHIK_CHANNEL" />. Byddwch yn cadw'r ffeil cyfrineiriau rydych newydd ei lawrlwytho.</translation>
    57  <translation id="1242883863226959074">dyfais</translation>

118 <translation id="1571304935088121812">Copïo'r enw defnyddiwr</translation>
119: <translation id="1584648915421894279">Ar hyn o bryd, ni ellir defnyddio cyfrineiriau sydd wedi'u cadw ar y ddyfais hon ar draws sianeli Chrome. Ar ôl Chrome 125, bydd cyfrineiriau sydd wedi'u cadw ar eich dyfais ar gyfer Chrome a <ph name="KOUSHIK_CHANNEL" /> yn cael eu cyfuno a gellir eu defnyddio yn y ddau ap.</translation>
120 <translation id="1592864538817356322">Amddiffyniad safonol:</translation>

688 <translation id="4601095002996233687">Sganiau manwl ar gyfer lawrlwythiadau amheus.</translation>
689: <translation id="4609429330876432068">Cyfunwyd eich rhestrau o gyfrineiriau sydd wedi'u cadw ar gyfer Chrome a <ph name="KOUSHIK_CHANNEL" />. Gallwch barhau i awtolenwi'ch holl gyfrineiriau sydd wedi'u cadw ar y ddau ap.</translation>
690 <translation id="4616150815774728855">Agor <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Dileu hanes, cwcis, data gwefan, storfa dros dro…</translation>
1654: <translation id="93533588269984624">Bydd yr holl gyfrineiriau'n cael eu lawrlwytho ar eich dyfais a'u tynnu o <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Gwall: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_da.xtb:

    55  <translation id="124116460088058876">Flere sprog</translation>
    56: <translation id="1241792820757384812">Dine adgangskoder slettes fra Google Adgangs­kode­admin­istrator for <ph name="KOUSHIK_CHANNEL" />. Du kan beholde den adgangskodefil, du lige har downloadet.</translation>
    57  <translation id="1242883863226959074">enhed</translation>

118 <translation id="1571304935088121812">Kopiér brugernavnet</translation>
119: <translation id="1584648915421894279">Lige nu kan adgangskoder, der er gemt på denne enhed, ikke bruges på andre Chrome-kanaler. Efter Chrome 125 flettes de adgangskoder, der er gemt i Chrome og <ph name="KOUSHIK_CHANNEL" /> på din enhed, så de kan bruges i begge apps.</translation>
120 <translation id="1592864538817356322">Standardbeskyttelse:</translation>

688 <translation id="4601095002996233687">Grundige scanninger efter mistænkelige downloads.</translation>
689: <translation id="4609429330876432068">Dine lister over gemte adgangskoder til Chrome og <ph name="KOUSHIK_CHANNEL" /> blev flettet. Du kan stadig udfylde alle dine gemte adgangskoder automatisk i begge apps.</translation>
690 <translation id="4616150815774728855">Åbn <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Slet historik, cookies, websitedata, cache…</translation>
1654: <translation id="93533588269984624">Alle adgangskoder downloades til din enhed og fjernes fra <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Fejl: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_de.xtb:

    55  <translation id="124116460088058876">Weitere Sprachen</translation>
    56: <translation id="1241792820757384812">Deine Passwörter für <ph name="KOUSHIK_CHANNEL" /> werden aus dem Google Passwortmanager gelöscht. Du behältst die soeben heruntergeladene Passwortdatei.</translation>
    57  <translation id="1242883863226959074">Gerät</translation>

118 <translation id="1571304935088121812">Nutzernamen kopieren</translation>
119: <translation id="1584648915421894279">Derzeit können auf diesem Gerät gespeicherte Passwörter nicht für alle Chrome-Release-Versionen verwendet werden. Nach Chrome 125 werden die für Chrome und <ph name="KOUSHIK_CHANNEL" /> auf deinem Gerät gespeicherten Passwörter zusammengeführt und können in beiden Apps verwendet werden.</translation>
120 <translation id="1592864538817356322">Standardschutz</translation>

688 <translation id="4601095002996233687">Umfangreiche Scans für verdächtige Downloads.</translation>
689: <translation id="4609429330876432068">Deine Listen mit gespeicherten Passwörtern für Chrome und <ph name="KOUSHIK_CHANNEL" /> wurden zusammengeführt. Du kannst weiterhin alle deine gespeicherten Passwörter in beiden Apps automatisch ausfüllen lassen.</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> öffnen</translation>

1653 <translation id="930124987204876019">Verlauf, Cookies, Websitedaten löschen, Cache leeren</translation>
1654: <translation id="93533588269984624">Alle Passwörter werden auf dein Gerät heruntergeladen und aus <ph name="KOUSHIK_CHANNEL" /> entfernt.</translation>
1655 <translation id="938850635132480979">Fehler: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_el.xtb:

    55  <translation id="124116460088058876">Περισσότερες γλώσσες</translation>
    56: <translation id="1241792820757384812">Οι κωδικοί πρόσβασης θα διαγραφούν από τον Διαχειριστή κωδικών πρόσβασης Google για το <ph name="KOUSHIK_CHANNEL" />. Το αρχείο κωδικών πρόσβασης που μόλις κατεβάσατε θα διατηρηθεί.</translation>
    57  <translation id="1242883863226959074">συσκευή</translation>

118 <translation id="1571304935088121812">Αντιγραφή ονόματος χρήστη</translation>
119: <translation id="1584648915421894279">Οι κωδικοί πρόσβασης που είναι αποθηκευμένοι σε αυτή τη συσκευή δεν μπορούν προς το παρόν να χρησιμοποιηθούν στα κανάλια Chrome. Μετά το Chrome 125, οι κωδικοί πρόσβασης που είναι αποθηκευμένοι στη συσκευή σας για το Chrome και το <ph name="KOUSHIK_CHANNEL" /> θα συγχωνευτούν και θα μπορούν να χρησιμοποιηθούν και στις δύο εφαρμογές.</translation>
120 <translation id="1592864538817356322">Βασική προστασία:</translation>

688 <translation id="4601095002996233687">Λεπτομερείς σαρώσεις σε βάθος για ύποπτες λήψεις.</translation>
689: <translation id="4609429330876432068">Οι λίστες με τους αποθηκευμένους κωδικούς πρόσβασης για το Chrome και το <ph name="KOUSHIK_CHANNEL" /> συγχωνεύτηκαν. Μπορείτε να συνεχίσετε να χρησιμοποιείτε την αυτόματη συμπλήρωση για όλους τους αποθηκευμένους κωδικούς πρόσβασης και στις δύο εφαρμογές.</translation>
690 <translation id="4616150815774728855">Ανοίξτε <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Διαγραφή ιστορικού, cookie, δεδομένων ιστοτόπου, κρυφής μνήμης…</translation>
1654: <translation id="93533588269984624">Θα γίνει λήψη όλων των κωδικών πρόσβασης στη συσκευή σας και θα καταργηθούν από το <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Σφάλμα: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_en-GB.xtb:

    55  <translation id="124116460088058876">More languages</translation>
    56: <translation id="1241792820757384812">Your passwords will be deleted from Google Password Manager for <ph name="KOUSHIK_CHANNEL" />. You will keep the passwords file you just downloaded.</translation>
    57  <translation id="1242883863226959074">device</translation>

118 <translation id="1571304935088121812">Copy username</translation>
119: <translation id="1584648915421894279">At the moment, passwords saved on this device cannot be used across Chrome channels. After Chrome 125, passwords saved on your device for Chrome and <ph name="KOUSHIK_CHANNEL" /> will be merged and can be used in both apps.</translation>
120 <translation id="1592864538817356322">Standard protection:</translation>

688 <translation id="4601095002996233687">In-depth scans for suspicious downloads.</translation>
689: <translation id="4609429330876432068">Your lists of saved passwords for Chrome and <ph name="KOUSHIK_CHANNEL" /> were merged. You can still autofill all your saved passwords on both apps.</translation>
690 <translation id="4616150815774728855">Open <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Delete history, cookies, site data, cache…</translation>
1654: <translation id="93533588269984624">All passwords will be downloaded on your device and removed from <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Error: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_es-419.xtb:

    55  <translation id="124116460088058876">Más idiomas</translation>
    56: <translation id="1241792820757384812">Se borrarán tus contraseñas del Administrador de contraseñas de Google para <ph name="KOUSHIK_CHANNEL" />. Conservarás el archivo de contraseñas que acabas de descargar.</translation>
    57  <translation id="1242883863226959074">dispositivo</translation>

118 <translation id="1571304935088121812">Copiar el nombre de usuario</translation>
119: <translation id="1584648915421894279">Por el momento, las contraseñas guardadas en este dispositivo no se pueden usar en todos los canales de Chrome. Después de la versión 125 de Chrome, las contraseñas guardadas en tu dispositivo para Chrome y <ph name="KOUSHIK_CHANNEL" /> se combinarán y se podrán usar en ambas apps.</translation>
120 <translation id="1592864538817356322">Protección estándar:</translation>

688 <translation id="4601095002996233687">Análisis detallados de descargas sospechosas.</translation>
689: <translation id="4609429330876432068">Se combinaron tus listas de contraseñas guardadas para Chrome y <ph name="KOUSHIK_CHANNEL" />. Aún puedes autocompletar todas tus contraseñas guardadas en ambas apps.</translation>
690 <translation id="4616150815774728855">Abrir <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Borra el historial, las cookies, los datos de sitios, la memoria caché…</translation>
1654: <translation id="93533588269984624">Se descargarán todas las contraseñas en el dispositivo y se quitarán de <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Error: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_es.xtb:

    55  <translation id="124116460088058876">Más idiomas</translation>
    56: <translation id="1241792820757384812">Tus contraseñas se eliminarán del Gestor de contraseñas de Google para <ph name="KOUSHIK_CHANNEL" />. Conservarás el archivo de contraseñas que acabas de descargar.</translation>
    57  <translation id="1242883863226959074">dispositivo</translation>

118 <translation id="1571304935088121812">Copiar nombre de usuario</translation>
119: <translation id="1584648915421894279">En este momento, las contraseñas guardadas en este dispositivo no se pueden usar en todos los canales de Chrome. Después de la versión 125 de Chrome, las contraseñas guardadas en tu dispositivo para Chrome y <ph name="KOUSHIK_CHANNEL" /> se combinarán y se podrán usar en ambas aplicaciones.</translation>
120 <translation id="1592864538817356322">Protección estándar:</translation>

688 <translation id="4601095002996233687">Análisis exhaustivos para detectar descargas sospechosas.</translation>
689: <translation id="4609429330876432068">Tus listas de contraseñas guardadas en Chrome y <ph name="KOUSHIK_CHANNEL" /> se han combinado. Puedes seguir autocompletando todas tus contraseñas guardadas en ambas aplicaciones.</translation>
690 <translation id="4616150815774728855">Abrir <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Elimina el historial, las cookies, los datos de sitios, la caché...</translation>
1654: <translation id="93533588269984624">Todas las contraseñas se descargarán en tu dispositivo y se eliminarán de <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Error: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_et.xtb:

    55  <translation id="124116460088058876">Rohkem keeli</translation>
    56: <translation id="1241792820757384812">Teie paroolid kustutatakse <ph name="KOUSHIK_CHANNEL" /> puhul Google'i paroolihaldurist. Äsja alla laaditud paroolide fail jääb teile alles.</translation>
    57  <translation id="1242883863226959074">seadmes</translation>

118 <translation id="1571304935088121812">Kasutajanime kopeerimine</translation>
119: <translation id="1584648915421894279">Praegu ei saa sellesse seadmesse salvestatud paroole Chrome'i kanalites kasutada. Pärast versiooni Chrome 125 liidetakse teie seadmesse Chrome'i ja kanali <ph name="KOUSHIK_CHANNEL" /> jaoks salvestatud paroolid ning neid saab kasutada mõlemas rakenduses.</translation>
120 <translation id="1592864538817356322">Standardne kaitse:</translation>

688 <translation id="4601095002996233687">Põhjalikud kontrollid kahtlaste allalaadimiste korral.</translation>
689: <translation id="4609429330876432068">Teie Chrome’i ja kanali <ph name="KOUSHIK_CHANNEL" /> salvestatud paroolide loendid liideti. Saate endiselt kõiki salvestatud paroole mõlemas rakenduses automaattäita.</translation>
690 <translation id="4616150815774728855">Ava <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Ajaloo, küpsiste, saidiandmete, vahemälu kustutamine …</translation>
1654: <translation id="93533588269984624">Kõik paroolid laaditakse alla teie seadmesse ja eemaldatakse kanalist <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Viga: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_eu.xtb:

    55  <translation id="124116460088058876">Hizkuntza gehiago</translation>
    56: <translation id="1241792820757384812">Pasahitzak ezabatu egingo dira <ph name="KOUSHIK_CHANNEL" /> arakatzaileko Google-ren Pasahitz-kudeatzailea zerbitzutik. Gorde deskargatu berri duzun pasahitzen fitxategia zeuretzat.</translation>
    57  <translation id="1242883863226959074">gailuan</translation>

118 <translation id="1571304935088121812">Kopiatu erabiltzaile-izena</translation>
119: <translation id="1584648915421894279">Une honetan, gailuan gordetako pasahitzak ezin dira erabili Chrome-ren kanaletan. Chrome-ren 125. bertsiotik aurrera, Chrome-rako eta <ph name="KOUSHIK_CHANNEL" /> kanalerako gailuan gordetako pasahitzak bateratu egingo dira, eta 2 aplikazioetan erabili ahal izango dituzu.</translation>
120 <translation id="1592864538817356322">Babes estandarra:</translation>

688 <translation id="4601095002996233687">Deskarga susmagarrien azterketa sakonak.</translation>
689: <translation id="4609429330876432068">Chrome eta <ph name="KOUSHIK_CHANNEL" /> aplikazioetan gordetako pasahitzak bateratu egin dira. Gorde dituzun pasahitz guztiak bi aplikazioetan bete ditzakezu automatikoki.</translation>
690 <translation id="4616150815774728855">Ireki <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Ezabatu historia, cookieak, webguneetako datuak, cachea…</translation>
1654: <translation id="93533588269984624">Pasahitz guztiak gailuan deskargatuko dira, eta <ph name="KOUSHIK_CHANNEL" /> arakatzailetik kenduko</translation>
1655 <translation id="938850635132480979">Errorea: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_fa.xtb:

    55  <translation id="124116460088058876">زبان‌های بیشتر</translation>
    56: <translation id="1241792820757384812">‏گذرواژه‌هایتان از «مدیر گذرواژه Google» برای <ph name="KOUSHIK_CHANNEL" /> حذف خواهد شد. فایل گذرواژه‌هایی که اکنون بارگیری کردید نزد شما باقی می‌ماند.</translation>
    57  <translation id="1242883863226959074">دستگاه</translation>

118 <translation id="1571304935088121812">کپی کردن نام کاربری</translation>
119: <translation id="1584648915421894279">‏درحال‌حاضر، نمی‌توانید از گذرواژه‌های ذخیره‌شده در این دستگاه در همه کانال‌های Chrome استفاده کنید. از نسخه ۱۲۵ به‌بعد، گذرواژه‌های ذخیره‌شده در دستگاهتان برای Chrome و <ph name="KOUSHIK_CHANNEL" /> ادغام خواهند شد و می‌توانید از آن‌ها در هردو برنامه استفاده کنید.</translation>
120 <translation id="1592864538817356322">محافظت استاندارد:</translation>

688 <translation id="4601095002996233687">اسکن‌های عمیق برای شناسایی بارگیری‌های مشکوک.</translation>
689: <translation id="4609429330876432068">‏فهرست گذرواژه‌های ذخیره‌شده شما برای Chrome و <ph name="KOUSHIK_CHANNEL" /> ادغام شدند. همچنان می‌توانید همه گذرواژه‌های ذخیره‌شده‌تان را در هردو برنامه به‌طور خودکار تکمیل کنید.</translation>
690 <translation id="4616150815774728855">باز کردن <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">حذف کردن سابقه، کوکی‌ها، داده‌های سایت، حافظه نهان…</translation>
1654: <translation id="93533588269984624">همه گذرواژه‌ها در دستگاهتان بارگیری خواهند شد و از <ph name="KOUSHIK_CHANNEL" /> برداشته می‌شوند</translation>
1655 <translation id="938850635132480979">خطا: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_fi.xtb:

    55  <translation id="124116460088058876">Lisää kieliä</translation>
    56: <translation id="1241792820757384812">Salasanasi poistetaan Google Salasanoista täällä: <ph name="KOUSHIK_CHANNEL" />. Säilytät juuri lataamasi salasanatiedoston.</translation>
    57  <translation id="1242883863226959074">laitteella</translation>

118 <translation id="1571304935088121812">Kopioi käyttäjänimi</translation>
119: <translation id="1584648915421894279">Tälle laitteelle tallennettuja salasanoja ei tällä hetkellä voi käyttää Chrome-kanavilla. Chrome 125:n jälkeen Chromelle ja <ph name="KOUSHIK_CHANNEL" /> ‑kanavalle tallennetut salasanat yhdistetään, ja niitä voi käyttää molemmissa sovelluksissa.</translation>
120 <translation id="1592864538817356322">Perustason suojaus:</translation>

688 <translation id="4601095002996233687">Yksityiskohtaiset tarkistukset epäilyttäville latauksille.</translation>
689: <translation id="4609429330876432068">Chrome‑ ja <ph name="KOUSHIK_CHANNEL" /> ‑sovelluksissa tallennetut salasanat yhdistettiin. Voit yhä täyttää kaikki tallennetut salasanat automaattisesti molemmissa sovelluksissa.</translation>
690 <translation id="4616150815774728855">Avaa <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Tyhjennä historia, evästeet, sivustodata, välimuisti…</translation>
1654: <translation id="93533588269984624">Kaikki salasanat ladataan laitteellesi ja poistetaan täältä: <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">(Virhe: <ph name="ERROR_CODE" />)</translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_fil.xtb:

    55  <translation id="124116460088058876">Higit pang wika</translation>
    56: <translation id="1241792820757384812">Made-delete ang iyong mga password mula sa Google Password Manager para sa <ph name="KOUSHIK_CHANNEL" />. Maitatabi mo ang file ng mga password na kaka-download mo lang.</translation>
    57  <translation id="1242883863226959074">device</translation>

118 <translation id="1571304935088121812">Kopyahin ang username</translation>
119: <translation id="1584648915421894279">Sa ngayon, hindi magagamit sa lahat ng channel ng Chrome ang mga password na naka-save sa device na ito. Pagkatapos ng Chrome 125, ime-merge ang mga password na naka-save sa iyong device para sa Chrome at <ph name="KOUSHIK_CHANNEL" />, at magagamit ang mga ito sa parehong app.</translation>
120 <translation id="1592864538817356322">Karaniwang proteksyon:</translation>

688 <translation id="4601095002996233687">Mga detalyadong pag-scan para sa mga kahina-hinalang pag-download.</translation>
689: <translation id="4609429330876432068">Na-merge ang iyong mga listahan ng mga naka-save na password para sa Chrome at <ph name="KOUSHIK_CHANNEL" />. Puwede mo pa ring i-autofill ang lahat ng iyong naka-save na password sa parehong app.</translation>
690 <translation id="4616150815774728855">Buksan ang <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">I-delete ang history, cookies, data ng site, cache…</translation>
1654: <translation id="93533588269984624">Mada-download ang lahat ng password sa iyong device at maaalis ang mga ito sa <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Error: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_fr-CA.xtb:

    55  <translation id="124116460088058876">Plus de langues</translation>
    56: <translation id="1241792820757384812">Vos mots de passe seront supprimés du gestionnaire de mots de passe Google pour <ph name="KOUSHIK_CHANNEL" />. Vous conserverez le fichier de mots de passe que vous venez de télécharger.</translation>
    57  <translation id="1242883863226959074">appareil</translation>

118 <translation id="1571304935088121812">Copier le nom d'utilisateur</translation>
119: <translation id="1584648915421894279">À l'heure actuelle, les mots de passe enregistrés sur cet appareil ne peuvent pas être utilisés sur l'ensemble des versions de Chrome. Après le lancement de Chrome 125, les mots de passe enregistrés sur votre appareil pour Chrome et <ph name="KOUSHIK_CHANNEL" /> seront fusionnés et pourront être utilisés dans les deux applications.</translation>
120 <translation id="1592864538817356322">Protection standard :</translation>

688 <translation id="4601095002996233687">Analyses approfondies des téléchargements suspects.</translation>
689: <translation id="4609429330876432068">Vos listes de mots de passe enregistrés pour Chrome et <ph name="KOUSHIK_CHANNEL" /> ont été fusionnées. Vous pouvez toujours remplir automatiquement tous vos mots de passe enregistrés sur les deux applications.</translation>
690 <translation id="4616150815774728855">Ouvrir <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Supprimer l'historique, les témoins, les données relatives aux sites, le cache…</translation>
1654: <translation id="93533588269984624">Tous les mots de passe seront téléchargés sur votre appareil et retirés de <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Erreur : <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_fr.xtb:

    55  <translation id="124116460088058876">Autres langues</translation>
    56: <translation id="1241792820757384812">Vos mots de passe seront supprimés du Gestionnaire de mots de passe de Google pour <ph name="KOUSHIK_CHANNEL" />. Vous conserverez le fichier de mots de passe que vous venez de télécharger.</translation>
    57  <translation id="1242883863226959074">appareil</translation>

118 <translation id="1571304935088121812">Copier le nom d'utilisateur</translation>
119: <translation id="1584648915421894279">Pour le moment, les mots de passe enregistrés sur cet appareil ne peuvent pas être utilisés sur les différentes versions de Chrome. Après Chrome 125, les mots de passe enregistrés sur votre appareil pour Chrome et <ph name="KOUSHIK_CHANNEL" /> seront fusionnés et pourront être utilisés dans les deux applis.</translation>
120 <translation id="1592864538817356322">Protection standard :</translation>

688 <translation id="4601095002996233687">Analyses approfondies pour les téléchargements suspects.</translation>
689: <translation id="4609429330876432068">Vos listes de mots de passe enregistrés pour Chrome et <ph name="KOUSHIK_CHANNEL" /> ont été fusionnées. Vous pouvez toujours saisir automatiquement tous vos mots de passe enregistrés dans les deux applis.</translation>
690 <translation id="4616150815774728855">Ouvrir <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Supprimer l'historique, les cookies et les données des sites, vider le cache…</translation>
1654: <translation id="93533588269984624">Tous les mots de passe seront téléchargés sur votre appareil et supprimés de <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Erreur <ph name="ERROR_CODE" />.</translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_gl.xtb:

    55  <translation id="124116460088058876">Máis idiomas</translation>
    56: <translation id="1241792820757384812">Os contrasinais eliminaranse do xestor de contrasinais de Google para <ph name="KOUSHIK_CHANNEL" />. Conservarás o ficheiro de contrasinais que acabas de descargar.</translation>
    57  <translation id="1242883863226959074">dispositivo</translation>

118 <translation id="1571304935088121812">Copia o nome de usuario</translation>
119: <translation id="1584648915421894279">De momento, os contrasinais gardados neste dispositivo non se poden usar en todas as canles de Chrome. Despois da versión 125 de Chrome, os contrasinais que teñas almacenados no dispositivo para Chrome e <ph name="KOUSHIK_CHANNEL" /> combinaranse e poderanse usar en ambas as aplicacións.</translation>
120 <translation id="1592864538817356322">Protección estándar:</translation>

688 <translation id="4601095002996233687">Análises minuciosas para detectar descargas sospeitosas.</translation>
689: <translation id="4609429330876432068">Combináronse as túas listas de contrasinais gardados de Chrome e <ph name="KOUSHIK_CHANNEL" />. Podes seguir autocompletando os contrasinais gardados en ambas as dúas aplicacións.</translation>
690 <translation id="4616150815774728855">Abrir <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Elimina o historial, as cookies, os datos dos sitios, a memoria caché…</translation>
1654: <translation id="93533588269984624">Descargaranse todos os contrasinais que haxa no teu dispositivo e quitaranse de <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Erro: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_gu.xtb:

    55  <translation id="124116460088058876">વધુ ભાષાઓ</translation>
    56: <translation id="1241792820757384812"><ph name="KOUSHIK_CHANNEL" /> માટેના તમારા પાસવર્ડને Google Password Managerમાંથી ડિલીટ કરવામાં આવશે. તમે હમણાં જ ડાઉનલોડ કરેલી પાસવર્ડ ફાઇલને તમે સાચવી રાખશો.</translation>
    57  <translation id="1242883863226959074">ડિવાઇસ</translation>

118 <translation id="1571304935088121812">વપરાશકર્તાનામ કૉપિ કરો</translation>
119: <translation id="1584648915421894279">અત્યારે, આ ડિવાઇસ પર સાચવવામાં આવેલા પાસવર્ડનો ઉપયોગ Chromeની બધી ચૅનલ પર કરી શકાતો નથી. Chrome 125 પછીના વર્ઝનમાં, તમારા ડિવાઇસ પર Chrome અને <ph name="KOUSHIK_CHANNEL" /> માટે સાચવેલા પાસવર્ડ મર્જ કરવામાં આવશે અને તેનો ઉપયોગ બન્ને ઍપમાં કરી શકાશે.</translation>
120 <translation id="1592864538817356322">માનક સંરક્ષણ:</translation>

688 <translation id="4601095002996233687">શંકાસ્પદ ડાઉનલોડ માટે સવિસ્તર સ્કૅનની સુવિધા.</translation>
689: <translation id="4609429330876432068">Chrome અને <ph name="KOUSHIK_CHANNEL" /> માટે સાચવેલા પાસવર્ડની તમારી સૂચિ મર્જ કરવામાં આવી હતી. તમે હજી પણ બન્ને ઍપ પર સાચવેલા તમારા બધા પાસવર્ડ ઑટોમૅટિક રીતે ભરી શકો છો.</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> ખોલો</translation>

1653 <translation id="930124987204876019">ઇતિહાસ, કુકી, સાઇટનો ડેટા, કૅશ મેમરી ડિલીટ કરો…</translation>
1654: <translation id="93533588269984624">બધા પાસવર્ડ તમારા ડિવાઇસ પર ડાઉનલોડ કરવામાં આવશે અને <ph name="KOUSHIK_CHANNEL" />માંથી કાઢી નાખવામાં આવશે</translation>
1655 <translation id="938850635132480979">ભૂલ: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_hi.xtb:

    55  <translation id="124116460088058876">ज़्यादा भाषाएं</translation>
    56: <translation id="1241792820757384812"><ph name="KOUSHIK_CHANNEL" /> के लिए, Google Password Manager से आपके पासवर्ड मिटा दिए जाएंगे. आपने अभी जो पासवर्ड फ़ाइल डाउनलोड की है वह सेव रहेगी.</translation>
    57  <translation id="1242883863226959074">डिवाइस</translation>

118 <translation id="1571304935088121812">उपयोगकर्ता नाम की कॉपी करें</translation>
119: <translation id="1584648915421894279">फ़िलहाल, इस डिवाइस पर सेव किए गए पासवर्ड, सभी Chrome चैनलों पर इस्तेमाल नहीं किए जा सकते. Chrome 125 के बाद, आपके डिवाइस पर Chrome और <ph name="KOUSHIK_CHANNEL" /> के लिए सेव किए गए पासवर्ड मर्ज कर दिए जाएंगे और इनका इस्तेमाल दोनों ऐप्लिकेशन में किया जा सकेगा.</translation>
120 <translation id="1592864538817356322">स्टैंडर्ड सुरक्षा मोड:</translation>

688 <translation id="4601095002996233687">यह सुविधा संदिग्ध डाउनलोड की जांच करने के लिए गहराई से स्कैन करती है.</translation>
689: <translation id="4609429330876432068">Chrome और <ph name="KOUSHIK_CHANNEL" /> पर सेव किए गए पासवर्ड की सूचियां मर्ज कर दी गई हैं. आपके पास अब भी दोनों ऐप्लिकेशन पर, सेव किए गए अपने सभी पासवर्ड ऑटोमैटिक भरने की सुविधा है.</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> को खोलें</translation>

1653 <translation id="930124987204876019">ब्राउज़िंग इतिहास, कुकी, साइट डेटा, कैश मेमोरी वगैरह मिटाएं…</translation>
1654: <translation id="93533588269984624">सभी पासवर्ड आपके डिवाइस पर डाउनलोड किए जाएंगे और उन्हें <ph name="KOUSHIK_CHANNEL" /> से हटा दिया जाएगा</translation>
1655 <translation id="938850635132480979">गड़बड़ी: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_hr.xtb:

    55  <translation id="124116460088058876">Više jezika</translation>
    56: <translation id="1241792820757384812">Vaše će se zaporke izbrisati s Google upravitelja zaporki za <ph name="KOUSHIK_CHANNEL" />. Zadržat ćete datoteku sa zaporkama koju ste upravo preuzeli.</translation>
    57  <translation id="1242883863226959074">uređaju</translation>

118 <translation id="1571304935088121812">Kopiraj korisničko ime</translation>
119: <translation id="1584648915421894279">Zaporke spremljene na ovom uređaju trenutačno se ne mogu upotrebljavati na Chromeovim kanalima. Nakon Chromea 125 zaporke spremljene na vašem uređaju za Chrome i <ph name="KOUSHIK_CHANNEL" /> spojit će se i moći će se upotrebljavati u obje aplikacije.</translation>
120 <translation id="1592864538817356322">Standardna zaštita:</translation>

688 <translation id="4601095002996233687">Dubinska pretraživanja mogućih sumnjivih preuzimanja.</translation>
689: <translation id="4609429330876432068">Spojili smo vaše popise spremljenih zaporki za Chrome i <ph name="KOUSHIK_CHANNEL" />. I dalje možete automatski unositi sve spremljene zaporke u obje aplikacije.</translation>
690 <translation id="4616150815774728855">Otvori <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Izbriši povijest, kolačiće, podatke web-lokacije, predmemoriju…</translation>
1654: <translation id="93533588269984624">Sve zaporke preuzet će se na vašem uređaju i ukloniti iz: <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Pogreška: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_hu.xtb:

    55  <translation id="124116460088058876">További nyelvek…</translation>
    56: <translation id="1241792820757384812">Jelszavai törlődnek a <ph name="KOUSHIK_CHANNEL" /> verziójával használt Google Jelszókezelőből. A most letöltött jelszófájl nem törlődik.</translation>
    57  <translation id="1242883863226959074">eszközén</translation>

118 <translation id="1571304935088121812">Felhasználónév másolása</translation>
119: <translation id="1584648915421894279">Az eszközre mentett jelszavak jelenleg nem használhatók a Chrome-csatornákban. A Chrome 125-ös verziója után az eszközre mentett Chrome- és <ph name="KOUSHIK_CHANNEL" />-jelszavakat a rendszer összevonja, és ezek a jelszavak mindkét alkalmazásban használhatók lesznek.</translation>
120 <translation id="1592864538817356322">Normál védelem:</translation>

698 <translation id="4601095002996233687">Mélyreható vizsgálatok a gyanús letöltött tartalmak ellenőrzéséhez.</translation>
699: <translation id="4609429330876432068">A Chrome-hoz és a <ph name="KOUSHIK_CHANNEL" /> verzióhoz mentett jelszavainak listáit a rendszer egyesítette. Az összes mentett jelszavát továbbra is kitöltheti automatikusan mindkét alkalmazásban.</translation>
700 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> megnyitása</translation>

1671 <translation id="930124987204876019">Előzmények, cookie-k, webhelyadatok, gyorsítótár törlése…</translation>
1672: <translation id="93533588269984624">A rendszer az összes jelszót letölti az eszközre, és eltávolítja a <ph name="KOUSHIK_CHANNEL" /> böngészőből</translation>
1673 <translation id="938850635132480979">Hiba: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_hy.xtb:

    55  <translation id="124116460088058876">Այլ լեզուներ</translation>
    56: <translation id="1241792820757384812">Ձեր գաղտնաբառերը կջնջվեն Google գաղտնաբառերի կառավարչից <ph name="KOUSHIK_CHANNEL" />-ում։ Գաղտնաբառերով ֆայլը, որը հենց նոր ներբեռնեցիք, կպահպանվի։</translation>
    57  <translation id="1242883863226959074">սարք</translation>

118 <translation id="1571304935088121812">Պատճենել օգտանունը</translation>
119: <translation id="1584648915421894279">Ներկայումս այս սարքում պահված գաղտնաբառերը հնարավոր չէ օգտագործել Chrome-ի տարբերակներում։ Chrome-ի տարբերակ 125-ի թողարկումից հետո Chrome-ի և <ph name="KOUSHIK_CHANNEL" />-ի համար ձեր սարքում պահված գաղտնաբառերը կմիավորվեն և կարող են օգտագործվել երկու հավելվածներում։</translation>
120 <translation id="1592864538817356322">Սովորական պաշտպանություն՝</translation>

688 <translation id="4601095002996233687">Կասկածելի ներբեռնումների մանրակրկիտ սկանավորում։</translation>
689: <translation id="4609429330876432068">Պահված գաղտնաբառերի ձեր ցանկերը Chrome-ի և <ph name="KOUSHIK_CHANNEL" />-ի համար միավորվել են։ Դուք նախկինի պես կարող եք ինքնալրացնել ձեր բոլոր պահված գաղտնաբառերը երկու հավելվածներում։</translation>
690 <translation id="4616150815774728855">Բացել <ph name="WEBAPK_NAME" /> հավելվածը</translation>

1653 <translation id="930124987204876019">Ջնջել պատմությունը, քուքիները, կայքի տվյալները, քեշը…</translation>
1654: <translation id="93533588269984624">Բոլոր գաղտնաբառերը կներբեռնվեն ձեր սարքում և կհեռացվեն <ph name="KOUSHIK_CHANNEL" />-ից</translation>
1655 <translation id="938850635132480979">Սխալ՝ <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_id.xtb:

    55  <translation id="124116460088058876">Bahasa lainnya</translation>
    56: <translation id="1241792820757384812">Sandi Anda akan dihapus dari Pengelola Sandi Google untuk <ph name="KOUSHIK_CHANNEL" />. Anda akan menyimpan file sandi yang baru saja didownload.</translation>
    57  <translation id="1242883863226959074">perangkat</translation>

118 <translation id="1571304935088121812">Salin nama pengguna</translation>
119: <translation id="1584648915421894279">Saat ini, sandi yang disimpan di perangkat ini tidak dapat digunakan di seluruh saluran Chrome. Setelah Chrome 125, sandi yang disimpan di perangkat Anda untuk Chrome dan <ph name="KOUSHIK_CHANNEL" /> akan digabungkan dan dapat digunakan di kedua aplikasi.</translation>
120 <translation id="1592864538817356322">Perlindungan standar:</translation>

688 <translation id="4601095002996233687">Pemindaian mendalam untuk download yang mencurigakan.</translation>
689: <translation id="4609429330876432068">Daftar sandi tersimpan Anda untuk Chrome dan <ph name="KOUSHIK_CHANNEL" /> telah digabungkan. Anda tetap dapat mengisi otomatis semua sandi tersimpan di kedua aplikasi.</translation>
690 <translation id="4616150815774728855">Buka <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Menghapus histori, cookie, data situs, cache…</translation>
1654: <translation id="93533588269984624">Semua sandi akan didownload di perangkat Anda dan dihapus dari <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Kesalahan: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_is.xtb:

    55  <translation id="124116460088058876">Fleiri tungumál</translation>
    56: <translation id="1241792820757384812">Aðgangsorðunum þínum verður eytt úr Google-aðgangsorðastjórnun fyrir <ph name="KOUSHIK_CHANNEL" />. Þú munt halda aðgangsorðaskránni sem þú varst að sækja.</translation>
    57  <translation id="1242883863226959074">tæki</translation>

118 <translation id="1571304935088121812">Afrita notandanafn</translation>
119: <translation id="1584648915421894279">Eins og stendur er ekki hægt að nota aðgangsorð sem eru vistuð í þessu tæki á öllum Chrome-rásum. Frá útgáfu Chrome 125 verða aðgangsorð sem eru vistuð í tækinu fyrir Chrome og <ph name="KOUSHIK_CHANNEL" /> sameinuð og hægt verður að nota þau í báðum forritunum.</translation>
120 <translation id="1592864538817356322">Hefðbundin vörn:</translation>

688 <translation id="4601095002996233687">Ítarleg leit að grunsamlegu niðurhali.</translation>
689: <translation id="4609429330876432068">Listarnir yfir vistuð aðgangsorð í Chrome og <ph name="KOUSHIK_CHANNEL" /> voru sameinaðir. Þú getur enn fyllt öll vistuð aðgangsorð út sjálfkrafa í báðum forritunum.</translation>
690 <translation id="4616150815774728855">Opna <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Eyddu ferli, fótsporum, vefsvæðagögnum, skyndiminni…</translation>
1654: <translation id="93533588269984624">Öll aðgangsorð verða sótt í tækið þitt og fjarlægð úr <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Villa: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_it.xtb:

    55  <translation id="124116460088058876">Altre lingue</translation>
    56: <translation id="1241792820757384812">Le tue password verranno eliminate da Gestore delle password di Google per <ph name="KOUSHIK_CHANNEL" />. Il file delle password che hai appena scaricato verrà mantenuto.</translation>
    57  <translation id="1242883863226959074">dispositivo</translation>

118 <translation id="1571304935088121812">Copia nome utente</translation>
119: <translation id="1584648915421894279">Al momento, le password salvate su questo dispositivo non possono essere utilizzate su tutti i canali Chrome. Dopo la versione 125 di Chrome, le password salvate sul dispositivo per Chrome e <ph name="KOUSHIK_CHANNEL" /> verranno unite e potranno essere utilizzate in entrambe le app.</translation>
120 <translation id="1592864538817356322">Protezione standard:</translation>

698 <translation id="4601095002996233687">Scansioni approfondite per rilevare i download sospetti.</translation>
699: <translation id="4609429330876432068">Gli elenchi di password salvate per Chrome e <ph name="KOUSHIK_CHANNEL" /> sono stati uniti. Puoi comunque compilare automaticamente tutte le password salvate in entrambe le app.</translation>
700 <translation id="4616150815774728855">Apri <ph name="WEBAPK_NAME" /></translation>

1671 <translation id="930124987204876019">Elimina cronologia, cookie, dati dei siti, svuota la cache…</translation>
1672: <translation id="93533588269984624">Tutte le password verranno scaricate sul tuo dispositivo e rimosse da <ph name="KOUSHIK_CHANNEL" /></translation>
1673 <translation id="938850635132480979">Errore: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_iw.xtb:

    55  <translation id="124116460088058876">שפות נוספות</translation>
    56: <translation id="1241792820757384812">‏הסיסמאות יימחקו ממנהל הסיסמאות של Google ב-<ph name="KOUSHIK_CHANNEL" />. קובץ הסיסמאות שהורדת עכשיו יישאר אצלך.</translation>
    57  <translation id="1242883863226959074">מכשיר</translation>

117 <translation id="1571304935088121812">העתקת שם משתמש</translation>
118: <translation id="1584648915421894279">‏בשלב הזה, לא ניתן להשתמש בסיסמאות ששמורות במכשיר הזה בערוצי Chrome. אחרי ההשקה של גרסה 125 של Chrome, הסיסמאות ששמורות במכשיר לשימוש ב-Chrome וב-<ph name="KOUSHIK_CHANNEL" /> ימוזגו, ואפשר יהיה להשתמש בהן בשתי האפליקציות.</translation>
119 <translation id="1592864538817356322">הגנה רגילה:</translation>

686 <translation id="4601095002996233687">סריקות מעמיקות לאיתור הורדות חשודות.</translation>
687: <translation id="4609429330876432068">‏הרשימות של הסיסמאות השמורות שלך ב-Chrome וב-<ph name="KOUSHIK_CHANNEL" /> מוזגו. עדיין אפשר למלא באופן אוטומטי את כל הסיסמאות השמורות בשתי האפליקציות האלו.</translation>
688 <translation id="4616150815774728855">פתיחה של <ph name="WEBAPK_NAME" /></translation>

1651 <translation id="930124987204876019">‏מחיקת ההיסטוריה, קובצי ה-Cookie, נתוני האתרים, המטמון…</translation>
1652: <translation id="93533588269984624">תתבצע הורדה של כל הסיסמאות שבמכשיר והן יוסרו מ-<ph name="KOUSHIK_CHANNEL" /></translation>
1653 <translation id="938850635132480979">שגיאה: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_ja.xtb:

    55  <translation id="124116460088058876">その他の言語</translation>
    56: <translation id="1241792820757384812">パスワードは、<ph name="KOUSHIK_CHANNEL" /> の Google パスワード マネージャーから削除されます。ダウンロードしたパスワード ファイルは保持されます。</translation>
    57  <translation id="1242883863226959074">デバイス</translation>

118 <translation id="1571304935088121812">ユーザー名をコピー</translation>
119: <translation id="1584648915421894279">現在のところ、このデバイスに保存されているパスワードを別の Chrome チャンネルで使用することはできません。Chrome 125 以降では、デバイスに保存されている Chrome と <ph name="KOUSHIK_CHANNEL" /> のパスワードが統合され、両方のアプリで使用できます。</translation>
120 <translation id="1592864538817356322">標準保護機能:</translation>

689 <translation id="4601095002996233687">不審なダウンロードを詳しくスキャンします。</translation>
690: <translation id="4609429330876432068">Chrome と <ph name="KOUSHIK_CHANNEL" /> の保存済みパスワードのリストを統合しました。どちらのアプリでも、保存されているすべてのパスワードを引き続き自動入力できます。</translation>
691 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> を起動</translation>

1655 <translation id="930124987204876019">履歴、Cookie、サイトデータ、キャッシュを削除します...</translation>
1656: <translation id="93533588269984624">パスワードがすべてデバイスにダウンロードされ、<ph name="KOUSHIK_CHANNEL" /> から削除されます</translation>
1657 <translation id="938850635132480979">エラー: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_ka.xtb:

    55  <translation id="124116460088058876">სხვა ენები</translation>
    56: <translation id="1241792820757384812">თქვენი პაროლები წაიშლება Google პაროლების მმართველიდან <ph name="KOUSHIK_CHANNEL" />-სთვის. პაროლების თქვენ მიერ ახლახან ჩამოტვირთული ფაილი შენარჩუნდება.</translation>
    57  <translation id="1242883863226959074">მოწყობილობა</translation>

118 <translation id="1571304935088121812">მომხმარებლის სახელის კოპირება</translation>
119: <translation id="1584648915421894279">ამ მოწყობილობაზე შენახული პაროლების გამოყენება ამჟამად ვერ ხერხდება Chrome-ის სხვადასხვა არხზე. Chrome-ის ვერსია 125-ის შემდეგ, თქვენს მოწყობილობაზე Chrome-ისა და <ph name="KOUSHIK_CHANNEL" />-ისთვის შენახული პაროლები გაერთიანდება და მათი გამოყენება შესაძლებელი იქნება ორივე აპში.</translation>
120 <translation id="1592864538817356322">სტანდარტული დაცვა:</translation>

688 <translation id="4601095002996233687">საეჭვო ჩამოტვირთვების სიღრმისეული სკანირების ფუნქცია.</translation>
689: <translation id="4609429330876432068">თქვენ მიერ Chrome-ისა და <ph name="KOUSHIK_CHANNEL" />-ისთვის შენახული პაროლების სია გაერთიანდა. ორივე აპში კვლავ შეგიძლიათ ავტომატურად შეავსოთ თქვენ მიერ შენახული ყველა პაროლი.</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" />-ის გახსნა</translation>

1653 <translation id="930124987204876019">ისტორიის, ქუქი-ჩანაწერების, საიტის მონაცემების, ქეშის წაშლა…</translation>
1654: <translation id="93533588269984624">ყველა პაროლი ჩამოიტვირთება თქვენს მოწყობილობაზე და წაიშლება <ph name="KOUSHIK_CHANNEL" />-დან</translation>
1655 <translation id="938850635132480979">შეცდომა: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_kk.xtb:

    55  <translation id="124116460088058876">Қосымша тілдер</translation>
    56: <translation id="1241792820757384812">Құпия сөздеріңіз <ph name="KOUSHIK_CHANNEL" /> бағдарламасына арналған Google Password Manager қызметінен жойылады. Жаңа ғана жүктеп алынған құпия сөздер файлын сақтайсыз.</translation>
    57  <translation id="1242883863226959074">құрылғы</translation>

118 <translation id="1571304935088121812">Пайдаланушы атын көшіру</translation>
119: <translation id="1584648915421894279">Дәл қазір осы құрылғыда сақталған құпия сөздерді Chrome арналарында пайдалану мүмкін емес. Chrome 125 нұсқасынан кейін Chrome және <ph name="KOUSHIK_CHANNEL" /> үшін құрылғыңызда сақталған құпия сөздер біріктіріледі және оларды екі қолданбада да пайдалануға болады.</translation>
120 <translation id="1592864538817356322">Стандартты қорғау:</translation>

688 <translation id="4601095002996233687">Күдікті жүктеп алынғандарға арналған тереңінен сканерлеулер.</translation>
689: <translation id="4609429330876432068">Chrome мен <ph name="KOUSHIK_CHANNEL" /> арнасының сақталған құпия сөздерінің тізімі біріктірілді. Барлық сақталған құпия сөзді екі қолданбада да автотолтыруға болады.</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> қолданбасын ашу</translation>

1653 <translation id="930124987204876019">Тарихты, cookie файлдарын, сайт деректерін, кэшті жою…</translation>
1654: <translation id="93533588269984624">Барлық құпия сөз құрылғыңызға жүктеп алынады және <ph name="KOUSHIK_CHANNEL" /> браузерінен өшіріледі</translation>
1655 <translation id="938850635132480979">Қате: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_km.xtb:

    55  <translation id="124116460088058876">ភាសា​ច្រើន​ទៀត</translation>
    56: <translation id="1241792820757384812">ពាក្យសម្ងាត់​របស់អ្នក​នឹង​ត្រូវបាន​លុបពី​កម្មវិធីគ្រប់គ្រង​ពាក្យសម្ងាត់​សម្រាប់ <ph name="KOUSHIK_CHANNEL" />។ អ្នកនឹង​រក្សា​ឯកសារ​ពាក្យសម្ងាត់​ដែលអ្នក​ទើបតែ​បានទាញយក។</translation>
    57  <translation id="1242883863226959074">ឧបករណ៍</translation>

118 <translation id="1571304935088121812">ចម្លងឈ្មោះអ្នកប្រើ</translation>
119: <translation id="1584648915421894279">ឥឡូវនេះ មិនអាចប្រើ​ពាក្យសម្ងាត់​ដែលបានរក្សាទុក​នៅលើ​ឧបករណ៍នេះ​លើបណ្តាញ Chrome បានទេ។ បន្ទាប់ពី Chrome 125 ពាក្យ​សម្ងាត់​ដែលបានរក្សាទុក​នៅលើ​ឧបករណ៍​របស់អ្នក​សម្រាប់ Chrome និង <ph name="KOUSHIK_CHANNEL" /> នឹងត្រូវបាន​ដាក់ចូលគ្នា និង​អាចត្រូវបានប្រើ​នៅក្នុង​កម្មវិធី​ទាំងពីរ។</translation>
120 <translation id="1592864538817356322">ការការពារ​ស្តង់ដារ៖</translation>

698 <translation id="4601095002996233687">ការស្កេន​ស៊ីជម្រៅ ដើម្បីរក​មើលការទាញយក​គួរឱ្យសង្ស័យ។</translation>
699: <translation id="4609429330876432068">បញ្ជី​ពាក្យសម្ងាត់ដែល​បានរក្សាទុក​របស់អ្នក​សម្រាប់ Chrome និង <ph name="KOUSHIK_CHANNEL" /> ត្រូវបានដាក់ចូលគ្នា។ អ្នកនៅតែអាច​បំពេញដោយស្វ័យប្រវត្តិ​នូវពាក្យសម្ងាត់​ដែលបានរក្សាទុក​ទាំងអស់​របស់អ្នក​នៅលើ​កម្មវិធី​ទាំងពីរ។</translation>
700 <translation id="4616150815774728855">បើក <ph name="WEBAPK_NAME" /></translation>

1671 <translation id="930124987204876019">លុប​ប្រវត្តិ ខូគី ទិន្នន័យគេហទំព័រ ឃ្លាំង​បម្រុង…</translation>
1672: <translation id="93533588269984624">ពាក្យសម្ងាត់​ទាំងអស់​នឹងត្រូវបាន​ទាញយក​នៅលើ​ឧបករណ៍​របស់អ្នក និង​ដកចេញពី <ph name="KOUSHIK_CHANNEL" /></translation>
1673 <translation id="938850635132480979">កំហុស៖ <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_kn.xtb:

    55  <translation id="124116460088058876">ಹೆಚ್ಚಿನ ಭಾಷೆಗಳು</translation>
    56: <translation id="1241792820757384812"><ph name="KOUSHIK_CHANNEL" /> ಗಾಗಿ Google Password Manager ನಿಂದ ನಿಮ್ಮ ಪಾಸ್‌ವರ್ಡ್‌ಗಳನ್ನು ಅಳಿಸಲಾಗುತ್ತದೆ. ನೀವು ಇದೀಗ ಡೌನ್‌ಲೋಡ್ ಮಾಡಿದ ಪಾಸ್‌ವರ್ಡ್‌ಗಳ ಫೈಲ್ ಅನ್ನು ನೀವು ಇರಿಸಿಕೊಳ್ಳುತ್ತೀರಿ.</translation>
    57  <translation id="1242883863226959074">ಸಾಧನ</translation>

118 <translation id="1571304935088121812">ಬಳಕೆದಾರರಹೆಸರು ನಕಲಿಸಿ</translation>
119: <translation id="1584648915421894279">ಸದ್ಯಕ್ಕೆ, ಈ ಸಾಧನದಲ್ಲಿ ಸೇವ್ ಮಾಡಲಾದ ಪಾಸ್‌ವರ್ಡ್‌ಗಳನ್ನು Chrome ಚಾನಲ್‌ಗಳಾದ್ಯಂತ ಬಳಸಲಾಗುವುದಿಲ್ಲ. Chrome 125 ರ ನಂತರ, Chrome ಮತ್ತು <ph name="KOUSHIK_CHANNEL" /> ಗಾಗಿ ನಿಮ್ಮ ಸಾಧನದಲ್ಲಿ ಸೇವ್ ಮಾಡಲಾದ ಪಾಸ್‌ವರ್ಡ್‌ಗಳನ್ನು ವಿಲೀನಗೊಳಿಸಲಾಗುತ್ತದೆ ಹಾಗೂ ಅವುಗಳನ್ನು ಎರಡೂ ಆ್ಯಪ್‌ಗಳಲ್ಲಿ ಬಳಸಬಹುದು.</translation>
120 <translation id="1592864538817356322">ಪ್ರಮಾಣಿತ ಸುರಕ್ಷತೆ:</translation>

687 <translation id="4601095002996233687">ಅನುಮಾನಾಸ್ಪದ ಡೌನ್‌ಲೋಡ್‌ಗಳಿಗಾಗಿ ಆಳವಾದ ಸ್ಕ್ಯಾನ್‌ಗಳು.</translation>
688: <translation id="4609429330876432068">Chrome ಮತ್ತು <ph name="KOUSHIK_CHANNEL" /> ಗೆ ಸಂಬಂಧಿಸಿದ ಸೇವ್ ಮಾಡಿದ ಪಾಸ್‌ವರ್ಡ್‌ಗಳ ನಿಮ್ಮ ಪಟ್ಟಿಗಳನ್ನು ವಿಲೀನಗೊಳಿಸಲಾಗಿದೆ. ನೀವು ಎರಡೂ ಆ್ಯಪ್‌ಗಳಲ್ಲಿನ ನಿಮ್ಮ ಎಲ್ಲಾ ಸೇವ್ ಮಾಡಿದ ಪಾಸ್‌ವರ್ಡ್‌ಗಳನ್ನು ಈಗಲೂ ಆಟೋಫಿಲ್ ಮಾಡಬಹುದು.</translation>
689 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> ತೆರೆಯಿರಿ</translation>

1652 <translation id="930124987204876019">ಇತಿಹಾಸ, ಕುಕಿಗಳು, ಸೈಟ್‌ ಡೇಟಾ, ಕ್ಯಾಷ್ ಅನ್ನು ಅಳಿಸಿ…</translation>
1653: <translation id="93533588269984624">ಎಲ್ಲಾ ಪಾಸ್‌ವರ್ಡ್‌ಗಳನ್ನು ನಿಮ್ಮ ಸಾಧನದಲ್ಲಿ ಡೌನ್‌ಲೋಡ್ ಮಾಡಲಾಗುತ್ತದೆ ಮತ್ತು <ph name="KOUSHIK_CHANNEL" /> ನಿಂದ ತೆಗೆದುಹಾಕಲಾಗುತ್ತದೆ</translation>
1654 <translation id="938850635132480979">ದೋಷ: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_ko.xtb:

    55  <translation id="124116460088058876">다른 언어</translation>
    56: <translation id="1241792820757384812"><ph name="KOUSHIK_CHANNEL" />용 Google 비밀번호 관리자에서 비밀번호가 삭제됩니다. 방금 다운로드한 비밀번호 파일은 유지됩니다.</translation>
    57  <translation id="1242883863226959074">기기</translation>

118 <translation id="1571304935088121812">사용자 이름 복사</translation>
119: <translation id="1584648915421894279">현재 이 기기에 저장된 비밀번호는 Chrome 채널 전반에서 사용할 수 없습니다. Chrome 125 이후에는 기기의 Chrome 및 <ph name="KOUSHIK_CHANNEL" />에 저장된 비밀번호가 병합되어 두 앱 모두에서 사용할 수 있습니다</translation>
120 <translation id="1592864538817356322">표준 보호 모드:</translation>

688 <translation id="4601095002996233687">의심스러운 다운로드 항목을 심층 스캔합니다.</translation>
689: <translation id="4609429330876432068">Chrome 및 <ph name="KOUSHIK_CHANNEL" />에 저장된 비밀번호 목록이 병합되었습니다. 두 앱 모두에 저장된 비밀번호를 계속 자동 완성할 수 있습니다.</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> 열기</translation>

1653 <translation id="930124987204876019">방문 기록, 쿠키, 사이트 데이터, 캐시 삭제…</translation>
1654: <translation id="93533588269984624">모든 비밀번호가 기기에 다운로드되며 <ph name="KOUSHIK_CHANNEL" />에서 삭제됩니다</translation>
1655 <translation id="938850635132480979">오류: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_ky.xtb:

    55  <translation id="124116460088058876">Дагы тилдер</translation>
    56: <translation id="1241792820757384812">Сырсөздөрүңүз <ph name="KOUSHIK_CHANNEL" /> үчүн Сырсөздөрдү башкаргычтан өчүрүлөт. Жаңы эле жүктөп алган сырсөздөрдү камтыган файл кала берет.</translation>
    57  <translation id="1242883863226959074">түзмөктө</translation>

118 <translation id="1571304935088121812">Колдонуучунун атын көчүрүү</translation>
119: <translation id="1584648915421894279">Учурда бул түзмөктө сакталган сырсөздөрдү Chrome каналдарында колдонууга болбойт. Chrome'дун 125-версиясы чыккандан кийин, түзмөгүңүздө сакталган Chrome жана <ph name="KOUSHIK_CHANNEL" /> сырсөздөрү бириктирилип, эки колдонмодо тең колдонулушу мүмкүн.</translation>
120 <translation id="1592864538817356322">Стандарттуу коргоо:</translation>

688 <translation id="4601095002996233687">Жүктөлүп алынган шектүү файлдарды тереңирээк текшерүү</translation>
689: <translation id="4609429330876432068">Chrome жана <ph name="KOUSHIK_CHANNEL" /> үчүн сакталган сырсөздөрүңүздүн тизмелери бириктирилди. Сакталган сырсөздөрүңүздүн баарын эки колдонмодо тең автотолтуруу функциясы менен колдоно бересиз.</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> колдонмосун ачуу</translation>

1653 <translation id="930124987204876019">Таржымалды, cookie файлдарын, сайттагы маалыматты, кешти өчүрүү…</translation>
1654: <translation id="93533588269984624">Бардык сырсөздөр түзмөгүңүзгө жүктөлүп алынып, <ph name="KOUSHIK_CHANNEL" /> серепчисинен өчүрүлөт</translation>
1655 <translation id="938850635132480979">Ката: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_lo.xtb:

    55  <translation id="124116460088058876">ພາສາເພີ່ມເຕີມ</translation>
    56: <translation id="1241792820757384812">ລະຫັດຜ່ານຂອງທ່ານຈະຖືກລຶບອອກຈາກຕົວຈັດການລະຫັດຜ່ານ Google ສຳລັບ <ph name="KOUSHIK_CHANNEL" />. ທ່ານຈະເກັບຮັກສາໄຟລ໌ລະຫັດຜ່ານທີ່ທ່ານຫາກໍດາວໂຫຼດໄປໄວ້.</translation>
    57  <translation id="1242883863226959074">ອຸປະກອນ</translation>

118 <translation id="1571304935088121812">ສຳເນົາຊື່ຜູ້ໃຊ້</translation>
119: <translation id="1584648915421894279">ຕອນນີ້, ລະຫັດຜ່ານທີ່ບັນທຶກໄວ້ຢູ່ອຸປະກອນນີ້ບໍ່ສາມາດໃຊ້ໄດ້ໃນ Chrome ເວີຊັນອື່ນໆໄດ້. ຫຼັງຈາກ Chrome 125, ລະຫັດຜ່ານທີ່ບັນທຶກໄວ້ຢູ່ອຸປະກອນຂອງທ່ານສຳລັບ Chrome ແລະ <ph name="KOUSHIK_CHANNEL" /> ຈະຮວມກັນ ແລະ ສາມາດໃຊ້ໄດ້ໃນທັງສອງແອັບ.</translation>
120 <translation id="1592864538817356322">ການປົກປ້ອງມາດຕະຖານ:</translation>

688 <translation id="4601095002996233687">ການສະແກນແບບເຈາະເລິກສຳລັບການດາວໂຫຼດທີ່ໜ້າສົງໄສ.</translation>
689: <translation id="4609429330876432068">ລາຍຊື່ລະຫັດຜ່ານທີ່ບັນທຶກໄວ້ຂອງທ່ານສຳລັບ Chrome ແລະ <ph name="KOUSHIK_CHANNEL" /> ໄດ້ຖືກຮວມເຂົ້າກັນແລ້ວ. ທ່ານຍັງສາມາດຕື່ມລະຫັດຜ່ານທີ່ບັນທຶກໄວ້ທັງໝົດຂອງທ່ານໂດຍອັດຕະໂນມັດໄດ້ໃນທັງ 2 ແອັບ.</translation>
690 <translation id="4616150815774728855">ເປີດ <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">ລຶບປະຫວັດ, ຄຸກກີ້, ຂໍ້ມູນເວັບໄຊ, ແຄສ…</translation>
1654: <translation id="93533588269984624">ລະຫັດຜ່ານທັງໝົດຈະຖືກດາວໂຫຼດຢູ່ອຸປະກອນຂອງທ່ານ ແລະ ຖືກລຶບອອກຈາກ <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">ຜິດພາດ: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_lt.xtb:

    55  <translation id="124116460088058876">Daugiau kalbų</translation>
    56: <translation id="1241792820757384812">„<ph name="KOUSHIK_CHANNEL" />“ slaptažodžiai bus ištrinti iš „Google“ slaptažodžių tvarkyklės. Išsaugosite ką tik atsisiųstą slaptažodžių failą.</translation>
    57  <translation id="1242883863226959074">įrenginyje</translation>

118 <translation id="1571304935088121812">Kopijuoti naudotojo vardą</translation>
119: <translation id="1584648915421894279">Šiuo metu šiame įrenginyje išsaugotų slaptažodžių negalima naudoti skirtinguose „Chrome“ kanaluose. Po 125 versijos „Chrome“ įrenginyje išsaugoti „Chrome“ ir „<ph name="KOUSHIK_CHANNEL" />“ slaptažodžiai bus sujungti ir juos bus galima naudoti abiejose programose.</translation>
120 <translation id="1592864538817356322">Įprasta apsauga:</translation>

688 <translation id="4601095002996233687">Nuodugnus įtartinų atsisiuntimų nuskaitymas.</translation>
689: <translation id="4609429330876432068">Išsaugotų „Chrome“ ir „<ph name="KOUSHIK_CHANNEL" />“ slaptažodžių sąrašai buvo sujungti. Vis tiek galite automatiškai užpildyti visus išsaugotus slaptažodžius abiejose programose.</translation>
690 <translation id="4616150815774728855">Atidaryti „<ph name="WEBAPK_NAME" />“</translation>

1653 <translation id="930124987204876019">Ištrinti istoriją, slapukus, svetainės, talpyklos duomenis…</translation>
1654: <translation id="93533588269984624">Visi slaptažodžiai bus atsisiųsti į įrenginį ir pašalinti iš kanalo „<ph name="KOUSHIK_CHANNEL" />“</translation>
1655 <translation id="938850635132480979">Klaida: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_lv.xtb:

    55  <translation id="124116460088058876">Citas valodas…</translation>
    56: <translation id="1241792820757384812">Jūsu paroles tiks dzēstas no Google paroļu pārvaldnieka šim pārlūkam: <ph name="KOUSHIK_CHANNEL" />. Tiks saglabāts tikko lejupielādētais paroļu fails.</translation>
    57  <translation id="1242883863226959074">ierīcē</translation>

118 <translation id="1571304935088121812">Kopēt lietotājvārdu</translation>
119: <translation id="1584648915421894279">Šajā ierīcē saglabātās paroles pašlaik nevar izmantot dažādās Chrome versijās. Pēc 125. versijas jūsu ierīcē saglabātās paroles pārlūkā Chrome (un šeit: <ph name="KOUSHIK_CHANNEL" />) tiks sapludinātas un tās varēs izmantot abās lietotnēs.</translation>
120 <translation id="1592864538817356322">Standarta aizsardzība:</translation>

688 <translation id="4601095002996233687">Detalizēta aizdomīgu lejupielāžu pārbaude.</translation>
689: <translation id="4609429330876432068">Jūsu Chrome un <ph name="KOUSHIK_CHANNEL" /> saglabāto paroļu saraksti tika sapludināti. Arī turpmāk varēsiet automātiski aizpildīt visas saglabātās paroles abās lietotnēs.</translation>
690 <translation id="4616150815774728855">Atvērt <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Dzēst vēsturi, sīkfailus, vietņu datus, kešatmiņu…</translation>
1654: <translation id="93533588269984624">Visas paroles tiks lejupielādētas jūsu ierīcē un noņemtas no šī pārlūka: <ph name="KOUSHIK_CHANNEL" />.</translation>
1655 <translation id="938850635132480979">Kļūda: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_mk.xtb:

    55  <translation id="124116460088058876">Повеќе јазици</translation>
    56: <translation id="1241792820757384812">Вашите лозинки ќе се избришат од Google Password Manager за <ph name="KOUSHIK_CHANNEL" />. Ќе ја задржите датотеката со лозинки што ја презедовте пред малку.</translation>
    57  <translation id="1242883863226959074">уред</translation>

118 <translation id="1571304935088121812">Копирај го корисничкото име</translation>
119: <translation id="1584648915421894279">Во моментов, лозинките што се зачувани на уредов не може да се користат на каналите на Chrome. По верзијата 125 на Chrome, лозинките што се зачувани на уредов за Chrome и <ph name="KOUSHIK_CHANNEL" /> ќе се спојат, па ќе може да се користат и во двете апликации.</translation>
120 <translation id="1592864538817356322">Стандардна заштита:</translation>

688 <translation id="4601095002996233687">Детални скенирања за сомнителни преземања.</translation>
689: <translation id="4609429330876432068">Вашите списоци на зачувани лозинки за Chrome и <ph name="KOUSHIK_CHANNEL" /> се споени. И понатаму може автоматски да ги пополнувате сите зачувани лозинки во двете апликации.</translation>
690 <translation id="4616150815774728855">Отвори <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Избришете ги историјата, колачињата, податоците од сајтот, кешот…</translation>
1654: <translation id="93533588269984624">Сите лозинки ќе се преземат на вашиот уред и ќе се отстранат од <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Грешка: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_ml.xtb:

    55  <translation id="124116460088058876">കൂടുതൽ ഭാഷകൾ</translation>
    56: <translation id="1241792820757384812"><ph name="KOUSHIK_CHANNEL" /> എന്നതിനുള്ള Google Password Manager-ൽ നിന്ന് നിങ്ങളുടെ പാസ്‌വേഡുകൾ ഇല്ലാതാക്കും. ഇപ്പോൾ ഡൗൺലോഡ് ചെയ്ത, പാസ്‌വേഡുകളുടെ ഫയൽ നിങ്ങൾ നിലനിർത്തും.</translation>
    57  <translation id="1242883863226959074">ഉപകരണം</translation>

118 <translation id="1571304935088121812">ഉപയോക്തൃനാമം പകർത്തുക</translation>
119: <translation id="1584648915421894279">ഇപ്പോൾ ഈ ഉപകരണത്തിൽ സംരക്ഷിച്ചിരിക്കുന്ന പാസ്‌വേഡുകൾ Chrome ചാനലുകളിൽ ഉടനീളം ഉപയോഗിക്കാനാകില്ല. Chrome 125-ന് ശേഷമുള്ള പതിപ്പുകളിൽ, Chrome-നും <ph name="KOUSHIK_CHANNEL" /> എന്നതിനും സംരക്ഷിച്ചിരിക്കുന്ന പാസ്‌വേഡുകൾ ലയിപ്പിക്കും, അവ രണ്ട് ആപ്പുകളിലും ഉപയോഗിക്കാം.</translation>
120 <translation id="1592864538817356322">സ്‌റ്റാൻഡേർഡ് പരിരക്ഷ:</translation>

688 <translation id="4601095002996233687">സംശയാസ്പദമായ ഡൗൺലോഡുകൾക്കായി വിശദമായ സ്കാനുകൾ.</translation>
689: <translation id="4609429330876432068">Chrome, <ph name="KOUSHIK_CHANNEL" /> എന്നിവയ്ക്കുള്ള നിങ്ങളുടെ, സംരക്ഷിച്ച പാസ്‌വേഡുകളുടെ ലിസ്‌റ്റുകൾ ലയിപ്പിച്ചു. നിങ്ങൾക്ക് തുടർന്നും രണ്ട് ആപ്പുകളിലും നിങ്ങളുടെ സംരക്ഷിച്ച പാസ്‌വേഡുകളെല്ലാം സ്വയമേവ പൂരിപ്പിക്കാനാകും.</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> തുറക്കുക</translation>

1653 <translation id="930124987204876019">ചരിത്രവും കുക്കികളും സൈറ്റ് ഡാറ്റയും കാഷെയും ഇല്ലാതാക്കുക…</translation>
1654: <translation id="93533588269984624">എല്ലാ പാസ്‌വേഡുകളും നിങ്ങളുടെ ഉപകരണത്തിൽ ഡൗൺലോഡ് ചെയ്യും, <ph name="KOUSHIK_CHANNEL" /> എന്നതിൽ നിന്ന് നീക്കം ചെയ്യും</translation>
1655 <translation id="938850635132480979">പിശക്: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_mn.xtb:

    55  <translation id="124116460088058876">Бусад хэл</translation>
    56: <translation id="1241792820757384812">Таны нууц үгнүүдийг <ph name="KOUSHIK_CHANNEL" />-н Google Password Manager-с устгана. Та дөнгөж сая татсан нууц үгнүүдийн файлаа хадгална.</translation>
    57  <translation id="1242883863226959074">төхөөрөмж</translation>

118 <translation id="1571304935088121812">Хэрэглэгчийн нэрийг хуулах</translation>
119: <translation id="1584648915421894279">Одоогоор энэ төхөөрөмжид хадгалсан нууц үгнүүдийг Chrome-н сувгуудад ашиглах боломжгүй. Chrome 125-аас хойш Chrome болон <ph name="KOUSHIK_CHANNEL" />-д зориулж таны төхөөрөмжид хадгалсан нууц үгнүүдийг нэгтгэх бөгөөд хоёр аппын аль алинд нь ашиглах боломжтой болно.</translation>
120 <translation id="1592864538817356322">Стандарт хамгаалалт:</translation>

688 <translation id="4601095002996233687">Сэжигтэй татаж авсан файлд хийх нарийвчилсан скан.</translation>
689: <translation id="4609429330876432068">Таны Chrome-н хадгалсан нууц үгнүүдийн жагсаалт болон <ph name="KOUSHIK_CHANNEL" />-г нэгтгэсэн. Та хоёр аппад хоёуланд нь хадгалсан бүх нууц үгээ автоматаар бөглөх боломжтой хэвээр байна.</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" />-г нээх</translation>

1653 <translation id="930124987204876019">Түүх, күүки, сайтын өгөгдөл, завсрын санах ойг устгах…</translation>
1654: <translation id="93533588269984624">Бүх нууц үгийг таны төхөөрөмжид татах бөгөөд <ph name="KOUSHIK_CHANNEL" />-с хасна</translation>
1655 <translation id="938850635132480979">Алдаа: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_mr.xtb:

    55  <translation id="124116460088058876">आणखी भाषा...</translation>
    56: <translation id="1241792820757384812">Google Password Manager मधून <ph name="KOUSHIK_CHANNEL" /> साठी तुमचे पासवर्ड हटवले जातील. तुम्ही आताच डाउनलोड केलेली पासवर्डची फाइल तुमच्याजवळ ठेवाल.</translation>
    57  <translation id="1242883863226959074">डिव्हाइस</translation>

118 <translation id="1571304935088121812">वापरकर्ता नाव कॉपी करा</translation>
119: <translation id="1584648915421894279">या डिव्हाइसवर सेव्ह केलेले पासवर्ड Chrome चॅनलवर सध्या वापरले जाऊ शकत नाहीत. Chrome 125 नंतर, Chrome साठी तुमच्या डिव्हाइसवर सेव्ह केलेले पासवर्ड आणि <ph name="KOUSHIK_CHANNEL" /> मर्ज केले जातील व दोन्ही अ‍ॅप्समध्ये वापरता येऊ शकतील.</translation>
120 <translation id="1592864538817356322">साधारण संरक्षण:</translation>

688 <translation id="4601095002996233687">संशयास्पद डाउनलोडसाठी तपशीलवार स्कॅनची सुविधा.</translation>
689: <translation id="4609429330876432068">Chrome आणि <ph name="KOUSHIK_CHANNEL" /> यांसाठी तुमच्या सेव्ह केलेल्या पासवर्डच्या सूची मर्ज केल्या गेल्या. तुम्ही तरीही तुमचे सेव्ह केलेले पासवर्ड दोन्ही अ‍ॅप्सवर ऑटोफिल करू शकता.</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> उघडा</translation>

1653 <translation id="930124987204876019">इतिहास, कुकी, साइट डेटा, कॅशे हटवा…</translation>
1654: <translation id="93533588269984624">सर्व पासवर्ड तुमच्या डिव्हाइसवर डाउनलोड केले जातील आणि <ph name="KOUSHIK_CHANNEL" /> मधून काढून टाकले जातील</translation>
1655 <translation id="938850635132480979">एरर: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_ms.xtb:

    55  <translation id="124116460088058876">Lagi bahasa</translation>
    56: <translation id="1241792820757384812">Kata laluan anda akan dipadamkan daripada Google Password Manager untuk <ph name="KOUSHIK_CHANNEL" />. Anda akan menyimpan fail kata laluan yang baru anda muat turun.</translation>
    57  <translation id="1242883863226959074">peranti</translation>

118 <translation id="1571304935088121812">Salin nama pengguna</translation>
119: <translation id="1584648915421894279">Pada masa ini, kata laluan yang disimpan pada peranti ini tidak boleh digunakan merentas saluran Chrome. Selepas Chrome 125, kata laluan yang disimpan pada peranti anda untuk Chrome dan <ph name="KOUSHIK_CHANNEL" /> akan digabungkan dan boleh digunakan pada kedua-dua apl.</translation>
120 <translation id="1592864538817356322">Perlindungan standard:</translation>

688 <translation id="4601095002996233687">Imbasan secara mendalam untuk muat turun yang mencurigakan.</translation>
689: <translation id="4609429330876432068">Senarai kata laluan anda yang disimpan untuk Chrome dan <ph name="KOUSHIK_CHANNEL" /> telah digabungkan. Anda masih dapat membuat autolengkap semua kata laluan anda yang disimpan pada kedua-dua apl.</translation>
690 <translation id="4616150815774728855">Buka <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Padamkan sejarah, kuki, data laman, cache…</translation>
1654: <translation id="93533588269984624">Semua kata laluan akan dimuat turun pada peranti anda dan dialih keluar daripada <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Ralat: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_my.xtb:

    55  <translation id="124116460088058876">နောက်ထပ် ဘာသာစကားများ</translation>
    56: <translation id="1241792820757384812"><ph name="KOUSHIK_CHANNEL" /> အတွက် Google Password Manager မှ သင့်စကားဝှက်များကို ဖျက်ပါမည်။ ယခုလေးတင် ဒေါင်းလုဒ်လုပ်လိုက်သော စကားဝှက်ဖိုင်ကို ဆက်သိမ်းထားပါမည်။</translation>
    57  <translation id="1242883863226959074">စက်</translation>

118 <translation id="1571304935088121812">အသုံးပြုသူအမည်ကို ကူးယူပါ</translation>
119: <translation id="1584648915421894279">ဤစက်တွင် သိမ်းထားသော စကားဝှက်များကို Chrome ချန်နယ်များတွင် ယခု မသုံးနိုင်ပါ။ Chrome 125 နောက်ပိုင်းတွင် Chrome နှင့် <ph name="KOUSHIK_CHANNEL" /> အတွက် သင့်စက်တွင် သိမ်းထားသော စကားဝှက်များကို ပေါင်းစည်းမည်ဖြစ်ပြီး အက်ပ်နှစ်ခုစလုံးတွင် သုံးနိုင်မည်။</translation>
120 <translation id="1592864538817356322">ပုံမှန်ကာကွယ်မှု -</translation>

688 <translation id="4601095002996233687">သံသယဖြစ်ဖွယ် ဒေါင်းလုဒ်များအတွက် အသေးစိတ် စကင်ဖတ်ခြင်း။</translation>
689: <translation id="4609429330876432068">Chrome နှင့် <ph name="KOUSHIK_CHANNEL" /> တို့အတွက် သိမ်းထားသော စကားဝှက်စာရင်းကို ပေါင်းစည်းလိုက်သည်။ သင်၏ သိမ်းထားသော စကားဝှက်အားလုံးကို အက်ပ်နှစ်ခုစလုံးတွင် အော်တိုဖြည့်နိုင်ပါသေးသည်။</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> ကို ဖွင့်ပါ</translation>

1652 <translation id="930124987204876019">မှတ်တမ်း၊ ကွတ်ကီးများ၊ ဝဘ်ဆိုက် ဒေတာ၊ ကက်ရှ်များ ဖျက်သည်…</translation>
1653: <translation id="93533588269984624">စကားဝှက်အားလုံးကို သင်၏စက်တွင် ဒေါင်းလုဒ်လုပ်ပြီး <ph name="KOUSHIK_CHANNEL" /> မှ ဖယ်ရှားလိုက်မည်</translation>
1654 <translation id="938850635132480979">အမှား- <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_ne.xtb:

    55  <translation id="124116460088058876">थप भाषाहरू</translation>
    56: <translation id="1241792820757384812"><ph name="KOUSHIK_CHANNEL" /> का हकमा Google पासवर्ड म्यानेजरबाट तपाईंका पासवर्डहरू मेटाइने छन्। तपाईंले भर्खरै डाउनलोड गरेको पासवर्डहरू भएको फाइल तपाईंको डिभाइसमा सेभ रहिरहने छ।</translation>
    57  <translation id="1242883863226959074">डिभाइस</translation>

118 <translation id="1571304935088121812">प्रयोगकर्ता नामको कपी गर्नुहोस्</translation>
119: <translation id="1584648915421894279">यो डिभाइसमा सेभ गरिएका पासवर्डहरू अहिले Chrome च्यानलहरूमा प्रयोग गर्न मिल्दैन। Chrome को १२५ औँ संस्करण इन्स्टल गरेपछि तपाईंको डिभाइसमा Chrome र <ph name="KOUSHIK_CHANNEL" /> का लागि सेभ गरिएका पासवर्डहरू मर्ज गरिने छन् र ती पासवर्ड दुवै एपमा प्रयोग गर्न मिल्छ।</translation>
120 <translation id="1592864538817356322">मानक सुरक्षा:</translation>

687 <translation id="4601095002996233687">डाउनलोड गरिएका फाइल शङ्कास्पद देखिएमा विस्तृत रूपमा स्क्यान गर्ने सुविधा।</translation>
688: <translation id="4609429330876432068">तपाईंले Chrome र <ph name="KOUSHIK_CHANNEL" /> मा सेभ गरेका पासवर्डका सूचीहरू मर्ज गरिएका थिए। तपाईं अझै पनि आफूले दुवै एपमा सेभ गरेका सबै पासवर्डहरू स्वतः भर्न सक्नुहुन्छ।</translation>
689 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> खोल्नुहोस्</translation>

1652 <translation id="930124987204876019">हिस्ट्री, कुकी, साइट डेटा, क्यास मेटाउनुहोस्…</translation>
1653: <translation id="93533588269984624">सबै पासवर्डहरू तपाईंको डिभाइसमा डाउनलोड गरिने छन् र <ph name="KOUSHIK_CHANNEL" /> बाट हटाइने छन्</translation>
1654 <translation id="938850635132480979">त्रुटि: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_nl.xtb:

    55  <translation id="124116460088058876">Meer talen</translation>
    56: <translation id="1241792820757384812">Je wachtwoorden worden verwijderd uit Google Wachtwoordmanager voor <ph name="KOUSHIK_CHANNEL" />. Je houdt het wachtwoordbestand dat je net hebt gedownload.</translation>
    57  <translation id="1242883863226959074">apparaat</translation>

118 <translation id="1571304935088121812">Gebruikersnaam kopiëren</translation>
119: <translation id="1584648915421894279">Wachtwoorden die op dit apparaat zijn opgeslagen, kunnen op dit moment niet worden gebruikt voor verschillende Chrome-kanalen. Na Chrome 125 worden de wachtwoorden die op je apparaat zijn opgeslagen voor Chrome en <ph name="KOUSHIK_CHANNEL" /> samengevoegd. Je kunt ze dan in beide apps gebruiken.</translation>
120 <translation id="1592864538817356322">Standaardbeveiliging:</translation>

688 <translation id="4601095002996233687">Uitgebreide scans voor verdachte downloads.</translation>
689: <translation id="4609429330876432068">Je lijsten met opgeslagen wachtwoorden voor Chrome en <ph name="KOUSHIK_CHANNEL" /> zijn samengevoegd. Je kunt al je opgeslagen wachtwoorden nog steeds automatisch laten invullen in beide apps.</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> openen</translation>

1653 <translation id="930124987204876019">Geschiedenis, cookies, sitegegevens, cachegeheugen verwijderen…</translation>
1654: <translation id="93533588269984624">Alle wachtwoorden worden gedownload op je apparaat en verwijderd uit <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Fout: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_no.xtb:

    55  <translation id="124116460088058876">Flere språk</translation>
    56: <translation id="1241792820757384812">Passordene dine blir slettet fra Google Passordlagring for <ph name="KOUSHIK_CHANNEL" />. Du beholder passordfilen du nettopp lastet ned.</translation>
    57  <translation id="1242883863226959074">enhet</translation>

118 <translation id="1571304935088121812">Kopiér brukernavnet</translation>
119: <translation id="1584648915421894279">Passord som er lagret på denne enheten, kan ikke brukes i ulike Chrome-kanaler akkurat nå. Etter Chrome 125 blir passord for Chrome og <ph name="KOUSHIK_CHANNEL" /> som er lagret på enheten din, slått sammen, slik at de kan brukes i begge appene.</translation>
120 <translation id="1592864538817356322">Standardbeskyttelse:</translation>

688 <translation id="4601095002996233687">Dybdeskanninger av mistenkelige nedlastinger.</translation>
689: <translation id="4609429330876432068">Listene dine over lagrede passord for Chrome og <ph name="KOUSHIK_CHANNEL" /> er slått sammen. Du kan fortsatt autofylle alle de lagrede passordene dine i begge appene.</translation>
690 <translation id="4616150815774728855">Åpne <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Slett logg, informasjonskapsler, nettstedsdata, buffer …</translation>
1654: <translation id="93533588269984624">Alle passord blir lastet ned på enheten og fjernet fra <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Feil: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_or.xtb:

    55  <translation id="124116460088058876">ଅନେକ ଭାଷା</translation>
    56: <translation id="1241792820757384812"><ph name="KOUSHIK_CHANNEL" /> ପାଇଁ Google Password Managerରୁ ଆପଣଙ୍କ ପାସୱାର୍ଡଗୁଡ଼ିକ ଡିଲିଟ ହୋଇଯିବ। ଆପଣ ଏବେ ଡାଉନଲୋଡ କରିଥିବା ପାସୱାର୍ଡ ଫାଇଲ ରଖିବେ।</translation>
    57  <translation id="1242883863226959074">ଡିଭାଇସ୍</translation>

118 <translation id="1571304935088121812">ଉପଯୋଗକର୍ତ୍ତାନାମ କପି କରନ୍ତୁ</translation>
119: <translation id="1584648915421894279">ବର୍ତ୍ତମାନ, ଏହି ଡିଭାଇସରେ ସେଭ କରାଯାଇଥିବା ପାସୱାର୍ଡଗୁଡ଼ିକୁ ସମଗ୍ର Chrome ଚେନେଲରେ ବ୍ୟବହାର କରାଯାଇପାରିବ ନାହିଁ। Chrome 125 ପରେ, Chrome ଏବଂ <ph name="KOUSHIK_CHANNEL" /> ପାଇଁ ଆପଣଙ୍କ ଡିଭାଇସରେ ସେଭ କରାଯାଇଥିବା ପାସୱାର୍ଡଗୁଡ଼ିକୁ ମର୍ଜ କରାଯିବ ଏବଂ ଉଭୟ ଆପ୍ସରେ ବ୍ୟବହାର କରାଯାଇପାରିବ।</translation>
120 <translation id="1592864538817356322">ଷ୍ଟାଣ୍ଡାର୍ଡ ସୁରକ୍ଷା:</translation>

688 <translation id="4601095002996233687">ସନ୍ଦେହଜନକ ଡାଉନଲୋଡଗୁଡ଼ିକ ପାଇଁ ସବିଶେଷ ସ୍କାନ।</translation>
689: <translation id="4609429330876432068">Chrome ଏବଂ <ph name="KOUSHIK_CHANNEL" /> ପାଇଁ ସେଭ କରାଯାଇଥିବା ପାସୱାର୍ଡଗୁଡ଼ିକର ଆପଣଙ୍କ ତାଲିକାଗୁଡ଼ିକ ମର୍ଜ ହୋଇଛି। ଆପଣ ଏବେ ବି ଉଭୟ ଆପ୍ସରେ ଆପଣଙ୍କର ସମସ୍ତ ସେଭ ହୋଇଥିବା ପାସୱାର୍ଡକୁ ଅଟୋଫିଲ କରିପାରିବେ।</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> ଖୋଲନ୍ତୁ</translation>

1653 <translation id="930124987204876019">ଇତିହାସ, କୁକୀ, ସାଇଟ ଡାଟା, କେଶେ ଡିଲିଟ କରନ୍ତୁ…</translation>
1654: <translation id="93533588269984624">ସମସ୍ତ ପାସୱାର୍ଡକୁ ଆପଣଙ୍କ ଡିଭାଇସରେ ଡାଉନଲୋଡ କରାଯିବ ଏବଂ <ph name="KOUSHIK_CHANNEL" />ରୁ କାଢ଼ି ଦିଆଯିବ</translation>
1655 <translation id="938850635132480979">ତ୍ରୁଟି: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_pa.xtb:

    55  <translation id="124116460088058876">ਹੋਰ ਭਾਸ਼ਾਵਾਂ</translation>
    56: <translation id="1241792820757384812"><ph name="KOUSHIK_CHANNEL" /> ਲਈ ਤੁਹਾਡੇ ਪਾਸਵਰਡਾਂ ਨੂੰ Google Password Manager ਤੋਂ ਮਿਟਾ ਦਿੱਤਾ ਜਾਵੇਗਾ। ਤੁਹਾਡੇ ਵੱਲੋਂ ਹੁਣੇ ਡਾਊਨਲੋਡ ਕੀਤੀ ਗਈ ਪਾਸਵਰਡ ਫ਼ਾਈਲ ਤੁਹਾਡੇ ਕੋਲ ਰਹੇਗੀ।</translation>
    57  <translation id="1242883863226959074">ਡੀਵਾਈਸ</translation>

118 <translation id="1571304935088121812">ਵਰਤੋਂਕਾਰ ਨਾਮ ਕਾਪੀ ਕਰੋ</translation>
119: <translation id="1584648915421894279">ਫ਼ਿਲਹਾਲ, ਇਸ ਡੀਵਾਈਸ 'ਤੇ ਰੱਖਿਅਤ ਕੀਤੇ ਪਾਸਵਰਡਾਂ ਨੂੰ ਸਾਰੇ Chrome ਚੈਨਲਾਂ 'ਤੇ ਨਹੀਂ ਵਰਤਿਆ ਜਾ ਸਕਦਾ। Chrome 125 ਤੋਂ ਬਾਅਦ, Chrome ਅਤੇ <ph name="KOUSHIK_CHANNEL" /> ਦੇ ਲਈ ਤੁਹਾਡੇ ਡੀਵਾਈਸ 'ਤੇ ਰੱਖਿਅਤ ਕੀਤੇ ਪਾਸਵਰਡਾਂ ਨੂੰ ਮਿਲਾ ਦਿੱਤਾ ਜਾਵੇਗਾ ਅਤੇ ਉਨ੍ਹਾਂ ਨੂੰ ਦੋਵਾਂ ਐਪਾਂ ਵਿੱਚ ਵਰਤਿਆ ਜਾ ਸਕਦਾ ਹੈ।</translation>
120 <translation id="1592864538817356322">ਮਿਆਰੀ ਸੁਰੱਖਿਆ:</translation>

688 <translation id="4601095002996233687">ਸ਼ੱਕੀ ਡਾਊਨਲੋਡਾਂ ਦੀ ਗਹਿਰਾਈ ਨਾਲ ਸਕੈਨਿੰਗ ਕੀਤੀ ਜਾਂਦੀ ਹੈ।</translation>
689: <translation id="4609429330876432068">Chrome ਅਤੇ <ph name="KOUSHIK_CHANNEL" /> ਲਈ ਤੁਹਾਡੇ ਰੱਖਿਅਤ ਕੀਤੇ ਪਾਸਵਰਡਾਂ ਦੀਆਂ ਸੂਚੀਆਂ ਨੂੰ ਮਿਲਾ ਦਿੱਤਾ ਗਿਆ ਸੀ। ਤੁਸੀਂ ਹਾਲੇ ਵੀ ਦੋਵਾਂ ਐਪਾਂ 'ਤੇ ਆਪਣੇ ਸਾਰੇ ਰੱਖਿਅਤ ਕੀਤੇ ਪਾਸਵਰਡਾਂ ਨੂੰ ਆਟੋਫਿਲ ਕਰ ਸਕਦੇ ਹੋ।</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> ਖੋਲ੍ਹੋ</translation>

1653 <translation id="930124987204876019">ਇਤਿਹਾਸ, ਕੁਕੀਜ਼, ਸਾਈਟ ਡਾਟਾ, ਕੈਸ਼ੇ ਮਿਟਾਓ…</translation>
1654: <translation id="93533588269984624">ਸਾਰੇ ਪਾਸਵਰਡ ਤੁਹਾਡੇ ਡੀਵਾਈਸ 'ਤੇ ਡਾਊਨਲੋਡ ਕੀਤੇ ਜਾਣਗੇ ਅਤੇ <ph name="KOUSHIK_CHANNEL" /> ਤੋਂ ਹਟਾ ਦਿੱਤੇ ਜਾਣਗੇ</translation>
1655 <translation id="938850635132480979">ਗੜਬੜ: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_pl.xtb:

    55  <translation id="124116460088058876">Więcej języków</translation>
    56: <translation id="1241792820757384812">Twoje hasła zostaną usunięte z Menedżera haseł Google w <ph name="KOUSHIK_CHANNEL" />. Pobrany przed chwilą plik z hasłami pozostanie zapisany na urządzeniu.</translation>
    57  <translation id="1242883863226959074">urządzeniu</translation>

118 <translation id="1571304935088121812">Kopiuj nazwę użytkownika</translation>
119: <translation id="1584648915421894279">Obecnie haseł zapisanych na tym urządzeniu nie można używać w kanałach Chrome. W wersjach nowszych niż Chrome 125 hasła w Chrome i <ph name="KOUSHIK_CHANNEL" /> zapisane na urządzeniu zostaną scalone i będzie można ich używać w obu aplikacjach.</translation>
120 <translation id="1592864538817356322">Standardowa ochrona:</translation>

688 <translation id="4601095002996233687">Szczegółowe skanowanie w poszukiwaniu podejrzanych pobranych plików.</translation>
689: <translation id="4609429330876432068">Twoje listy zapisanych haseł w Chrome i <ph name="KOUSHIK_CHANNEL" /> zostały scalone. Nadal możesz używać wszystkich zapisanych haseł do autouzupełniania w obu aplikacjach.</translation>
690 <translation id="4616150815774728855">Otwórz <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Usuń historię, pliki cookie, dane witryn, pamięć podręczną…</translation>
1654: <translation id="93533588269984624">Wszystkie hasła zostaną pobrane na urządzenie i usunięte z <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Błąd: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_pt-BR.xtb:

    55  <translation id="124116460088058876">Mais idiomas</translation>
    56: <translation id="1241792820757384812">Suas senhas serão excluídas do Gerenciador de senhas do Google para o <ph name="KOUSHIK_CHANNEL" />. Elas vão estar no arquivo de senhas que você acabou de baixar.</translation>
    57  <translation id="1242883863226959074">dispositivo</translation>

118 <translation id="1571304935088121812">Copiar nome de usuário</translation>
119: <translation id="1584648915421894279">No momento, as senhas salvas neste dispositivo não podem ser usadas nos canais do Chrome. Após a versão 125 desse navegador, as senhas do Chrome e do <ph name="KOUSHIK_CHANNEL" /> salvas no dispositivo serão fundidas e poderão ser usadas nos dois apps.</translation>
120 <translation id="1592864538817356322">Proteção padrão:</translation>

689 <translation id="4601095002996233687">Verificações detalhadas de downloads suspeitos.</translation>
690: <translation id="4609429330876432068">Suas listas de senhas salvas do Chrome e do <ph name="KOUSHIK_CHANNEL" /> foram fundidas. Você ainda pode preencher automaticamente todas as senhas salvas nos dois apps.</translation>
691 <translation id="4616150815774728855">Abrir <ph name="WEBAPK_NAME" /></translation>

1654 <translation id="930124987204876019">Excluir histórico, cookies, dados do site, cache…</translation>
1655: <translation id="93533588269984624">Todas as senhas serão baixadas para seu dispositivo e removidas do <ph name="KOUSHIK_CHANNEL" /></translation>
1656 <translation id="938850635132480979">Erro: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_pt-PT.xtb:

    55  <translation id="124116460088058876">Mais idiomas</translation>
    56: <translation id="1241792820757384812">As suas palavras-passe vão ser eliminadas do Gestor de Palavras-passe da Google para o <ph name="KOUSHIK_CHANNEL" />. Vai manter o ficheiro de palavras-passe que acabou de transferir.</translation>
    57  <translation id="1242883863226959074">dispositivo</translation>

118 <translation id="1571304935088121812">Copiar nome de utilizador</translation>
119: <translation id="1584648915421894279">Neste momento, as palavras-passe guardadas neste dispositivo não podem ser usadas nos canais do Chrome. Depois do Chrome 125, as palavras-passe guardadas no dispositivo para o Chrome e o <ph name="KOUSHIK_CHANNEL" /> vão ser unidas e podem ser usadas em ambas as apps.</translation>
120 <translation id="1592864538817356322">Proteção padrão:</translation>

698 <translation id="4601095002996233687">Análises detalhadas de transferências suspeitas.</translation>
699: <translation id="4609429330876432068">As suas listas de palavras-passe guardadas do Chrome e <ph name="KOUSHIK_CHANNEL" /> foram unidas. Pode continuar a preencher automaticamente todas as palavras-passe guardadas em ambas as apps.</translation>
700 <translation id="4616150815774728855">Abrir <ph name="WEBAPK_NAME" /></translation>

1671 <translation id="930124987204876019">Elimine o histórico, os cookies, os dados de sites, a cache…</translation>
1672: <translation id="93533588269984624">Todas as palavras-passe vão ser transferidas para o seu dispositivo e removidas do <ph name="KOUSHIK_CHANNEL" /></translation>
1673 <translation id="938850635132480979">Erro: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_ro.xtb:

    55  <translation id="124116460088058876">Mai multe limbi</translation>
    56: <translation id="1241792820757384812">Parolele se vor șterge din Managerul de parole Google pentru <ph name="KOUSHIK_CHANNEL" />. Vei păstra fișierul cu parole pe care tocmai l-ai descărcat.</translation>
    57  <translation id="1242883863226959074">dispozitiv</translation>

118 <translation id="1571304935088121812">Copiază numele de utilizator</translation>
119: <translation id="1584648915421894279">Momentan, parolele salvate pe acest dispozitiv nu pot fi folosite pe canalele Chrome. După versiunea Chrome 125, parolele salvate pe dispozitiv pentru Chrome și <ph name="KOUSHIK_CHANNEL" /> vor fi îmbinate și pot fi folosite în ambele aplicații.</translation>
120 <translation id="1592864538817356322">Protecție standard:</translation>

688 <translation id="4601095002996233687">Scanări detaliate pentru descărcările suspecte.</translation>
689: <translation id="4609429330876432068">Listele de parole salvate pentru Chrome și <ph name="KOUSHIK_CHANNEL" /> au fost îmbinate. Poți în continuare să completezi automat toate parolele salvate în ambele aplicații.</translation>
690 <translation id="4616150815774728855">Deschide <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Șterge istoricul, cookie-urile, datele privind site-urile, memoria cache…</translation>
1654: <translation id="93533588269984624">Toate parolele vor fi descărcate pe dispozitiv și șterse din <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Eroare: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_ru.xtb:

    55  <translation id="124116460088058876">Другие языки</translation>
    56: <translation id="1241792820757384812">Ваши пароли будут удалены из Google Менеджера паролей в <ph name="KOUSHIK_CHANNEL" />. Файл с паролями, который вы скачали, останется.</translation>
    57  <translation id="1242883863226959074">устройстве</translation>

118 <translation id="1571304935088121812">Копировать имя пользователя</translation>
119: <translation id="1584648915421894279">Сохраненные на этом устройстве пароли пока нельзя использовать в разных каналах Chrome. Мы объединим ваши сохраненные пароли для Chrome и <ph name="KOUSHIK_CHANNEL" /> после выхода версии Chrome 125, и их можно будет использовать в обеих версиях.</translation>
120 <translation id="1592864538817356322">Стандартная защита:</translation>

688 <translation id="4601095002996233687">Выполняет тщательную проверку подозрительных файлов, которые вы скачали.</translation>
689: <translation id="4609429330876432068">Ваши списки сохраненных паролей для Chrome и <ph name="KOUSHIK_CHANNEL" /> были объединены. Вы по-прежнему можете вставлять сохраненные пароли в обоих приложениях с помощью функции автозаполнения.</translation>
690 <translation id="4616150815774728855">Открыть <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Удалить историю, файлы cookie, данные сайтов, кеш и другие данные</translation>
1654: <translation id="93533588269984624">Все пароли будут скачаны на ваше устройство и удалены из <ph name="KOUSHIK_CHANNEL" />.</translation>
1655 <translation id="938850635132480979">Ошибка <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_si.xtb:

    55  <translation id="124116460088058876">තවත් භාෂා</translation>
    56: <translation id="1241792820757384812">ඔබේ මුරපද <ph name="KOUSHIK_CHANNEL" /> සඳහා Google මුරපද කළමනාකරු වෙතින් මකනු ලැබේ. ඔබ දැන් බාගත කළ මුරපද ගොනුව තබා ගනු ඇත.</translation>
    57  <translation id="1242883863226959074">උපාංගය</translation>

118 <translation id="1571304935088121812">පරිශීලක නාමය පිටපත් කරන්න</translation>
119: <translation id="1584648915421894279">මේ මොහොතේ, මෙම උපාංගයේ සුරකින ලද මුරපද Chrome නාලිකා හරහා භාවිතා කළ නොහැක. Chrome 125ට පසුව, Chrome සහ <ph name="KOUSHIK_CHANNEL" /> සඳහා ඔබේ උපාංගයෙහි සුරකින ලද මුරපද ඒකාබද්ධ කරනු ලබන අතර යෙදුම් දෙකෙහිම භාවිතා කළ හැක.</translation>
120 <translation id="1592864538817356322">සම්මත ආරක්ෂාව:</translation>

698 <translation id="4601095002996233687">සැක සහිත බාගැනීම් සඳහා ගැඹුරු ස්කෑන් කිරීම්.</translation>
699: <translation id="4609429330876432068">Chrome සහ <ph name="KOUSHIK_CHANNEL" /> සඳහා ඔබේ සුරකින ලද මුරපද ලැයිස්තුව ඒකාබද්ධ කර ඇත. ඔබට තවමත් යෙදුම් දෙකෙහිම ඔබේ සුරැකි මුරපද සියල්ල ස්වයං පිරවුම කළ හැකි ය.</translation>
700 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> විවෘත කරන්න</translation>

1671 <translation id="930124987204876019">ඉතිහාසය, කුකී, අඩවි දත්ත, හැඹිලිය මකන්න…</translation>
1672: <translation id="93533588269984624">සියලු ම මුරපද ඔබේ උපාංගයට බාගෙන <ph name="KOUSHIK_CHANNEL" /> වෙතින් ඉවත් කරනු ලැබේ</translation>
1673 <translation id="938850635132480979">දෝෂය: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_sk.xtb:

    55  <translation id="124116460088058876">Ďalšie jazyky</translation>
    56: <translation id="1241792820757384812">Vaše heslá budú odstránené zo Správcu hesiel Google v kanáli <ph name="KOUSHIK_CHANNEL" />. Súbor s heslami, ktorý ste práve stiahli, vám zostane.</translation>
    57  <translation id="1242883863226959074">zariadenie</translation>

118 <translation id="1571304935088121812">Kopírovať používateľské meno</translation>
119: <translation id="1584648915421894279">Momentálne nemôžete používať heslá uložené v tomto zariadení v kanáloch Chromu. Od Chromu verzie 125 budú heslá pre Chrome a <ph name="KOUSHIK_CHANNEL" /> uložené vo vašom zariadení zlúčené a budú sa dať používať v oboch aplikáciách.</translation>
120 <translation id="1592864538817356322">Štandardná ochrana:</translation>

688 <translation id="4601095002996233687">Hĺbkové kontroly s cieľom nájsť podozrivé stiahnuté súbory.</translation>
689: <translation id="4609429330876432068">Zoznamy uložených hesiel pre Chrome a kanál <ph name="KOUSHIK_CHANNEL" /> boli zlúčené. Všetky svoje uložené heslá môžete naďalej automaticky dopĺňať v oboch aplikáciách.</translation>
690 <translation id="4616150815774728855">Otvoriť <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Odstrániť históriu, súbory cookie, dáta webov, vyrovnávaciu pamäť…</translation>
1654: <translation id="93533588269984624">Všetky heslá budú stiahnuté do vášho zariadenia a odstránené z kanála <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Chyba: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_sl.xtb:

    55  <translation id="124116460088058876">Več jezikov</translation>
    56: <translation id="1241792820757384812">Gesla bodo izbrisana iz Googlovega upravitelja gesel za <ph name="KOUSHIK_CHANNEL" />. Obdržali boste datoteko z gesli, ki ste jo pravkar prenesli.</translation>
    57  <translation id="1242883863226959074">napravi</translation>

118 <translation id="1571304935088121812">Kopiranje uporabniškega imena</translation>
119: <translation id="1584648915421894279">Gesel, shranjenih v tej napravi, za zdaj ni mogoče uporabljati v Chromovih kanalih. Po Chromu 125 bodo gesla, shranjena v napravi za Chrome in <ph name="KOUSHIK_CHANNEL" />, združena in jih bo mogoče uporabljati v obeh aplikacijah.</translation>
120 <translation id="1592864538817356322">Standardna zaščita:</translation>

688 <translation id="4601095002996233687">Poglobljeni pregledi za sumljive prenose.</translation>
689: <translation id="4609429330876432068">Seznami shranjenih gesel za Chrome in <ph name="KOUSHIK_CHANNEL" /> so bili združeni. Še vedno lahko samodejno izpolnite vsa shranjena gesla v obeh aplikacijah.</translation>
690 <translation id="4616150815774728855">Odpri <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Brisanje zgodovine, piškotkov, podatkov spletnih mest, predpomnilnika …</translation>
1654: <translation id="93533588269984624">Vsa gesla bodo prenesena v napravo in odstranjena iz brskalnika <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Napaka: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_sq.xtb:

    55  <translation id="124116460088058876">Gjuhë të tjera</translation>
    56: <translation id="1241792820757384812">Fjalëkalimet e tua do të fshihen nga "Menaxheri i fjalëkalimeve i Google" për <ph name="KOUSHIK_CHANNEL" />. Do ta mbash skedarin e fjalëkalimeve që sapo ke shkarkuar.</translation>
    57  <translation id="1242883863226959074">pajisja</translation>

118 <translation id="1571304935088121812">Kopjo emrin e përdoruesit</translation>
119: <translation id="1584648915421894279">Për momentin fjalëkalimet e ruajtura në këtë pajisje nuk mund të përdoren nëpër kanalet e Chrome. Pas Chrome 125, fjalëkalimet e ruajtura në pajisjen tënde për Chrome dhe <ph name="KOUSHIK_CHANNEL" /> do të shkrihen dhe do të mund të përdoren në të dyja aplikacionet.</translation>
120 <translation id="1592864538817356322">Mbrojtja standarde:</translation>

688 <translation id="4601095002996233687">Skanime të thella për shkarkime të dyshimta.</translation>
689: <translation id="4609429330876432068">Listat e tua me fjalëkalimet e ruajtura për Chrome dhe <ph name="KOUSHIK_CHANNEL" /> janë shkrirë. Mund të plotësosh përsëri automatikisht të gjitha fjalëkalimet e ruajtura në të dyja aplikacionet.</translation>
690 <translation id="4616150815774728855">Hap <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Fshi historikun, kukit, të dhënat e sajtit, memorien specifike…</translation>
1654: <translation id="93533588269984624">Të gjitha fjalëkalimet do të shkarkohen në pajisjen tënde dhe do të hiqen nga <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Gabim: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_sr-Latn.xtb:

    55  <translation id="124116460088058876">Još jezika</translation>
    56: <translation id="1241792820757384812">Lozinke će biti izbrisane iz Google menadžera lozinki za <ph name="KOUSHIK_CHANNEL" />. Zadržaćete fajl sa lozinkama koji ste upravo preuzeli.</translation>
    57  <translation id="1242883863226959074">uređaju</translation>

118 <translation id="1571304935088121812">Kopiraj korisničko ime</translation>
119: <translation id="1584648915421894279">Lozinke sačuvane na ovom uređaju trenutno ne mogu da se koriste na svim Chrome kanalima. Kada koristite Chrome 125, lozinke sačuvane na uređaju za Chrome i <ph name="KOUSHIK_CHANNEL" /> će biti objedinjene i mogu da se koriste u obe aplikacije.</translation>
120 <translation id="1592864538817356322">Standardna zaštita:</translation>

688 <translation id="4601095002996233687">Detaljna skeniranja sumnjivih preuzimanja.</translation>
689: <translation id="4609429330876432068">Liste sačuvanih lozinki za Chrome i <ph name="KOUSHIK_CHANNEL" /> su objedinjene. I dalje možete automatski da popunjavate sve sačuvane lozinke u obe aplikacije.</translation>
690 <translation id="4616150815774728855">Otvori <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Izbrišite istoriju, kolačiće, podatke o sajtovima, keš…</translation>
1654: <translation id="93533588269984624">Sve lozinke će biti preuzete na uređaj i uklonjene iz <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Greška: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_sr.xtb:

    55  <translation id="124116460088058876">Још језика</translation>
    56: <translation id="1241792820757384812">Лозинке ће бити избрисане из Google менаџера лозинки за <ph name="KOUSHIK_CHANNEL" />. Задржаћете фајл са лозинкама који сте управо преузели.</translation>
    57  <translation id="1242883863226959074">уређају</translation>

118 <translation id="1571304935088121812">Копирај корисничко име</translation>
119: <translation id="1584648915421894279">Лозинке сачуване на овом уређају тренутно не могу да се користе на свим Chrome каналима. Када користите Chrome 125, лозинке сачуване на уређају за Chrome и <ph name="KOUSHIK_CHANNEL" /> ће бити обједињене и могу да се користе у обе апликације.</translation>
120 <translation id="1592864538817356322">Стандардна заштита:</translation>

688 <translation id="4601095002996233687">Детаљна скенирања сумњивих преузимања.</translation>
689: <translation id="4609429330876432068">Листе сачуваних лозинки за Chrome и <ph name="KOUSHIK_CHANNEL" /> су обједињене. И даље можете аутоматски да попуњавате све сачуване лозинке у обе апликације.</translation>
690 <translation id="4616150815774728855">Отвори <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Избришите историју, колачиће, податке о сајтовима, кеш…</translation>
1654: <translation id="93533588269984624">Све лозинке ће бити преузете на уређај и уклоњене из <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Грешка: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_sv.xtb:

    55  <translation id="124116460088058876">Fler språk</translation>
    56: <translation id="1241792820757384812">Dina lösenord raderas från Google Lösenordshantering för <ph name="KOUSHIK_CHANNEL" />. Lösenordsfilen som du precis laddade ned finns kvar.</translation>
    57  <translation id="1242883863226959074">enhet</translation>

118 <translation id="1571304935088121812">Kopiera användarnamn</translation>
119: <translation id="1584648915421894279">Lösenord som är sparade på den här enheten går för närvarande inte att använda i Chrome-kanaler. Efter Chrome 125 sammanfogas lösenord som är sparade på enheten för Chrome och <ph name="KOUSHIK_CHANNEL" /> och kan användas i båda apparna.</translation>
120 <translation id="1592864538817356322">Standardskydd:</translation>

689 <translation id="4601095002996233687">Ingående genomsökningar efter misstänkta nedladdningar.</translation>
690: <translation id="4609429330876432068">Listorna över sparade lösenord för Chrome och <ph name="KOUSHIK_CHANNEL" /> har sammanfogats. Du kan fortfarande fylla i alla sparade lösenord automatiskt i båda apparna.</translation>
691 <translation id="4616150815774728855">Öppna <ph name="WEBAPK_NAME" /></translation>

1654 <translation id="930124987204876019">Radera historik, cookies, webbplatsdata, cacheminne …</translation>
1655: <translation id="93533588269984624">Alla lösenord laddas ned på enheten och tas bort från <ph name="KOUSHIK_CHANNEL" /></translation>
1656 <translation id="938850635132480979">Fel: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_sw.xtb:

    55  <translation id="124116460088058876">Lugha zaidi</translation>
    56: <translation id="1241792820757384812">Manenosiri yako yatafutwa katika Kidhibiti cha Manenosiri cha Google kwenye <ph name="KOUSHIK_CHANNEL" />. Utahifadhi faili ya manenosiri uliyoipakua.</translation>
    57  <translation id="1242883863226959074">kifaa</translation>

118 <translation id="1571304935088121812">Nakili jina la mtumiaji</translation>
119: <translation id="1584648915421894279">Sasa hivi, manenosiri yaliyohifadhiwa kwenye kifaa hiki hayawezi kutumiwa kwenye chaneli zote za Chrome. Baada ya toleo la Chrome 125, manenosiri yaliyohifadhiwa kwenye kifaa chako ili kutumia katika Chrome na <ph name="KOUSHIK_CHANNEL" /> yataunganishwa na yataweza kutumiwa katika programu zote mbili.</translation>
120 <translation id="1592864538817356322">Ulinzi wa kawaida:</translation>

688 <translation id="4601095002996233687">Ukaguzi wa kina wa vipakuliwa vinavyoshukiwa.</translation>
689: <translation id="4609429330876432068">Orodha zako za manenosiri yaliyohifadhiwa kwa ajili ya Chrome na <ph name="KOUSHIK_CHANNEL" /> ziliunganishwa. Bado unaweza kujaza kiotomatiki manenosiri yako yote uliyohifadhi kwenye programu zote mbili.</translation>
690 <translation id="4616150815774728855">Fungua <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Futa historia, vidakuzi, data ya tovuti, akiba…</translation>
1654: <translation id="93533588269984624">Manenosiri yote yatapakuliwa kwenye kifaa chako na kuondolewa kwenye <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Hitilafu: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_ta.xtb:

    55  <translation id="124116460088058876">மேலும் மொழிகள்</translation>
    56: <translation id="1241792820757384812"><ph name="KOUSHIK_CHANNEL" />க்கான கடவுச்சொற்கள் Google Password Managerரில் இருந்து நீக்கப்படும். நீங்கள் சற்றுமுன் பதிவிறக்கிய கடவுச்சொற்கள் ஃபைல் உங்களிடமே இருக்கும்.</translation>
    57  <translation id="1242883863226959074">சாதனத்தில்</translation>

118 <translation id="1571304935088121812">பயனர்பெயரை நகலெடுக்கும்</translation>
119: <translation id="1584648915421894279">தற்போது, இந்தச் சாதனத்தில் சேமிக்கப்பட்டுள்ள கடவுச்சொற்களை Chrome சேனல்கள் முழுவதிலும் பயன்படுத்த முடியாது. Chrome பதிப்பு 125க்குப் பிறகு உங்கள் சாதனத்தில் Chrome, <ph name="KOUSHIK_CHANNEL" /> ஆகியவற்றில் நீங்கள் சேமித்துள்ள கடவுச்சொற்கள் ஒன்றிணைக்கப்படுவதோடு அவற்றை இரண்டு ஆப்ஸிலும் பயன்படுத்தலாம்.</translation>
120 <translation id="1592864538817356322">நிலையான பாதுகாப்பு:</translation>

688 <translation id="4601095002996233687">சந்தேகத்திற்கிடமான பதிவிறக்கங்களை விரிவாக ஸ்கேன் செய்யலாம்.</translation>
689: <translation id="4609429330876432068">Chrome, <ph name="KOUSHIK_CHANNEL" /> ஆகியவற்றில் நீங்கள் சேமித்துள்ள கடவுச்சொற்களின் பட்டியல்கள் ஒன்றிணைக்கப்பட்டன. இருப்பினும், நீங்கள் சேமித்துள்ள கடவுச்சொற்களை இரண்டு ஆப்ஸிலும் தானாக நிரப்பலாம்.</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" />ஐத் திற</translation>

1653 <translation id="930124987204876019">பதிவு, குக்கீகள், தளத் தரவு, தற்காலிகச் சேமிப்பை நீக்கலாம்…</translation>
1654: <translation id="93533588269984624">அனைத்து கடவுச்சொற்களும் உங்கள் சாதனத்தில் பதிவிறக்கப்பட்டு <ph name="KOUSHIK_CHANNEL" /> இல் இருந்து நீக்கப்படும்</translation>
1655 <translation id="938850635132480979">பிழை: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_te.xtb:

    55  <translation id="124116460088058876">మరిన్ని భాషలు</translation>
    56: <translation id="1241792820757384812"><ph name="KOUSHIK_CHANNEL" /> కోసం Google Password Manager నుండి మీ పాస్‌వర్డ్‌లు తొలగించబడతాయి. మీరు ఇప్పుడే డౌన్‌లోడ్ చేసిన పాస్‌వర్డ్‌ల ఫైల్‌ను అలాగే ఉంచుతారు.</translation>
    57  <translation id="1242883863226959074">పరికరం</translation>

118 <translation id="1571304935088121812">వినియోగదారు పేరును కాపీ చేస్తుంది</translation>
119: <translation id="1584648915421894279">ప్రస్తుతం, ఈ పరికరంలో సేవ్ చేయబడిన పాస్‌వర్డ్‌లు Chrome ఛానెల్స్‌లో ఉపయోగించబడవు. Chrome 125 తర్వాత, Chrome, <ph name="KOUSHIK_CHANNEL" /> కోసం మీ పరికరంలో సేవ్ చేయబడిన పాస్‌వర్డ్‌లు విలీనం చేయబడతాయి, రెండు యాప్‌లలో ఉపయోగించవచ్చు.</translation>
120 <translation id="1592864538817356322">స్టాండర్డ్ రక్షణ:</translation>

688 <translation id="4601095002996233687">అనుమానాస్పద డౌన్‌లోడ్‌ల కోసం లోతైన స్కాన్‌లు చేయండి.</translation>
689: <translation id="4609429330876432068">Chrome, <ph name="KOUSHIK_CHANNEL" />‌కు సంబంధించి సేవ్ చేసిన మీ పాస్‌వర్డ్‌ల లిస్ట్‌లు విలీనమయ్యాయి. సేవ్ చేసిన మీ పాస్‌వర్డ్‌లన్నింటినీ ఇప్పటికీ మీరు రెండు యాప్‌లలోనూ ఆటోఫిల్ చేయవచ్చు.</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" />ని తెరువు</translation>

1653 <translation id="930124987204876019">హిస్టరీని, కుక్కీలను, సైట్ డేటాను, కాష్‌ను తొలగించండి…</translation>
1654: <translation id="93533588269984624">పాస్‌వర్డ్‌లన్నీ మీ పరికరంలో డౌన్‌లోడ్ అవుతాయి, అలాగే <ph name="KOUSHIK_CHANNEL" /> నుండి తీసివేయబడతాయి</translation>
1655 <translation id="938850635132480979">ఎర్రర్: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_th.xtb:

    55  <translation id="124116460088058876">ภาษาเพิ่มเติม</translation>
    56: <translation id="1241792820757384812">ระบบจะลบรหัสผ่านของคุณจากเครื่องมือจัดการรหัสผ่านบน Google สำหรับ <ph name="KOUSHIK_CHANNEL" /> คุณจะต้องเก็บไฟล์รหัสผ่านที่เพิ่งดาวน์โหลดไว้</translation>
    57  <translation id="1242883863226959074">อุปกรณ์</translation>

118 <translation id="1571304935088121812">คัดลอกชื่อผู้ใช้</translation>
119: <translation id="1584648915421894279">ขณะนี้ รหัสผ่านที่บันทึกไว้ในอุปกรณ์นี้จะนำไปใช้ใน Chrome เวอร์ชันอื่นๆ ไม่ได้ หลังจาก Chrome 125 รหัสผ่านที่คุณบันทึกไว้ใน Chrome และ <ph name="KOUSHIK_CHANNEL" /> บนอุปกรณ์จะรวมกัน และใช้ได้ในทั้ง 2 แอป</translation>
120 <translation id="1592864538817356322">การปกป้องแบบมาตรฐาน:</translation>

688 <translation id="4601095002996233687">การสแกนเชิงลึกสำหรับการดาวน์โหลดที่น่าสงสัย</translation>
689: <translation id="4609429330876432068">รายการรหัสผ่านที่บันทึกไว้สำหรับ Chrome และ <ph name="KOUSHIK_CHANNEL" /> รวมเข้าด้วยกันแล้ว คุณยังคงป้อนรหัสผ่านที่บันทึกไว้ทั้งหมดโดยอัตโนมัติได้ในทั้ง 2 แอป</translation>
690 <translation id="4616150815774728855">เปิด <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">ลบประวัติการเข้าชม คุกกี้ ข้อมูลเว็บไซต์ แคช…</translation>
1654: <translation id="93533588269984624">ระบบจะดาวน์โหลดรหัสผ่านทั้งหมดในอุปกรณ์ของคุณ และนําออกจาก <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">ข้อผิดพลาด: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_tr.xtb:

    55  <translation id="124116460088058876">Diğer diller</translation>
    56: <translation id="1241792820757384812"><ph name="KOUSHIK_CHANNEL" /> şifreleriniz Google Şifre Yöneticisi'nden silinecek. Az önce indirdiğiniz şifre dosyasını saklayabilirsiniz.</translation>
    57  <translation id="1242883863226959074">cihaz</translation>

118 <translation id="1571304935088121812">Kullanıcı adını kopyala</translation>
119: <translation id="1584648915421894279">Bu cihaza kaydedilen şifreler şu anda Chrome kanallarında kullanılamaz. Chrome 125 sürümünden sonra, Chrome ve <ph name="KOUSHIK_CHANNEL" /> için cihazınıza kaydedilen şifreler birleştirilip her iki uygulamada da kullanılabilir.</translation>
120 <translation id="1592864538817356322">Standart koruma:</translation>

688 <translation id="4601095002996233687">Şüpheli indirme işlemleri için ayrıntılı taramalar.</translation>
689: <translation id="4609429330876432068">Chrome ve <ph name="KOUSHIK_CHANNEL" /> için kayıtlı şifre listeleriniz birleştirildi. Kayıtlı tüm şifrelerinizi her iki uygulamada da otomatik olarak doldurmaya devam edebilirsiniz.</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> APK'sını aç</translation>

1653 <translation id="930124987204876019">Geçmiş, çerezler, site verileri, önbelleği silin</translation>
1654: <translation id="93533588269984624">Tüm şifreler cihazınıza indirilir ve Chrome <ph name="KOUSHIK_CHANNEL" /> hizmetinden kaldırılır</translation>
1655 <translation id="938850635132480979">Hata: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_uk.xtb:

    55  <translation id="124116460088058876">Інші мови</translation>
    56: <translation id="1241792820757384812">Ваші паролі буде видалено з Google Менеджера паролів для <ph name="KOUSHIK_CHANNEL" />. Файл із паролями, який ви щойно завантажили, буде збережено.</translation>
    57  <translation id="1242883863226959074">пристрої</translation>

118 <translation id="1571304935088121812">Копіювати ім’я користувача</translation>
119: <translation id="1584648915421894279">Зараз паролі, збережені на цьому пристрої, не можна використовувати в каналах Chrome. Після виходу версії 125 ваші збережені паролі для Chrome та <ph name="KOUSHIK_CHANNEL" /> буде об’єднано, і їх можна буде використовувати в обох додатках.</translation>
120 <translation id="1592864538817356322">Стандартний захист:</translation>

688 <translation id="4601095002996233687">Ретельна перевірка підозрілих завантажень.</translation>
689: <translation id="4609429330876432068">Ваші списки збережених паролів для Chrome і <ph name="KOUSHIK_CHANNEL" /> було об’єднано. Ви можете автоматично вводити всі збережені паролі в обох додатках.</translation>
690 <translation id="4616150815774728855">Відкрити файл <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Видалити історію, файли cookie, дані сайтів, кеш…</translation>
1654: <translation id="93533588269984624">Усі паролі буде завантажено на ваш пристрій і вилучено з <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Помилка: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_ur.xtb:

    55  <translation id="124116460088058876">مزید زبانیں</translation>
    56: <translation id="1241792820757384812">‏آپ کے پاس ورڈز کو Google پاس ورڈ مینیجر برائے <ph name="KOUSHIK_CHANNEL" /> سے حذف کر دیا جائے گا۔ آپ پاس ورڈز کی وہ فائل رکھیں گے جسے آپ نے ابھی ڈاؤن لوڈ کیا ہے۔</translation>
    57  <translation id="1242883863226959074">آلہ</translation>

118 <translation id="1571304935088121812">صارف نام کاپی کریں</translation>
119: <translation id="1584648915421894279">‏ابھی، اس آلے پر محفوظ کردہ پاس ورڈز کو Chrome چینلز پر استعمال نہیں کیا جا سکتا۔ Chrome 125 کے بعد، آپ کے آلے پر Chrome اور <ph name="KOUSHIK_CHANNEL" /> کے لیے محفوظ کردہ پاس ورڈز کو ضم کر دیا جائے گا اور انہیں دونوں ایپس میں استعمال کیا جا سکتا ہے۔</translation>
120 <translation id="1592864538817356322">معیاری تحفظ:</translation>

688 <translation id="4601095002996233687">مشتبہ ڈاؤن لوڈز کے لیے گہرائی سے اسکینز کرتا ہے۔</translation>
689: <translation id="4609429330876432068">‏Chrome اور <ph name="KOUSHIK_CHANNEL" /> کے لیے آپ کے محفوظ کردہ پاس ورڈز کی فہرستیں ضم کر دی گئیں۔ آپ اب بھی دونوں ایپس پر اپنے تمام محفوظ کردہ پاس ورڈز کو آٹو فل کر سکتے ہیں۔</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> کو کھولیں</translation>

1653 <translation id="930124987204876019">‏سرگزشت، کوکیز، سائٹ ڈیٹا، cache کو حذف کریں…</translation>
1654: <translation id="93533588269984624">تمام پاس ورڈز آپ کے آلے پر ڈاؤن لوڈ ہو جائیں گے اور انہیں <ph name="KOUSHIK_CHANNEL" /> سے ہٹا دیا جائے گا</translation>
1655 <translation id="938850635132480979">خرابی: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_uz.xtb:

    55  <translation id="124116460088058876">Boshqa tillar</translation>
    56: <translation id="1241792820757384812">Parollaringiz <ph name="KOUSHIK_CHANNEL" /> uchun Google Parollar menejeridan oʻchirib tashlanadi. Hozirgina yuklab olingan parollar faylini saqlab qolishingiz mumkin.</translation>
    57  <translation id="1242883863226959074">qurilma</translation>

118 <translation id="1571304935088121812">Foydalanuvchi nomidan nusxa olish</translation>
119: <translation id="1584648915421894279">Ayni damda bu qurilmaga saqlangan parollardan Chrome kanallarida foydalanish imkonsiz. Chrome brauzerining 125-versiyasidan keyin qurilmangiz va <ph name="KOUSHIK_CHANNEL" />ga saqlangan parollar birlashtiriladi hamda har ikki ilovada foydalanish mumkin boʻladi.</translation>
120 <translation id="1592864538817356322">Standart himoya:</translation>

688 <translation id="4601095002996233687">Shubhali yuklanmalarni chuqur tekshirish</translation>
689: <translation id="4609429330876432068">Chrome va <ph name="KOUSHIK_CHANNEL" /> uchun saqlangan parollar roʻyxatlari birlashtirilgan. Avtomatik kiritish funksiyasidan foydalangan holda saqlangan parollarni har ikki ilovaga ham kiritish mumkin.</translation>
690 <translation id="4616150815774728855"><ph name="WEBAPK_NAME" /> veb-ilovasini ochish</translation>

1653 <translation id="930124987204876019">Brauzer tarixi, cookie fayllari, kesh va boshqa sayt ma’lumotlarini oʻchirish…</translation>
1654: <translation id="93533588269984624">Barcha parollar qurilmada yuklab olinadi va <ph name="KOUSHIK_CHANNEL" /> xotirasidan olib tashlanadi</translation>
1655 <translation id="938850635132480979">Xato: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_vi.xtb:

    55  <translation id="124116460088058876">Ngôn ngữ khác</translation>
    56: <translation id="1241792820757384812">Mật khẩu của bạn sẽ bị xoá khỏi Trình quản lý mật khẩu của Google trên <ph name="KOUSHIK_CHANNEL" />. Bạn sẽ giữ tệp mật khẩu mà bạn vừa tải xuống.</translation>
    57  <translation id="1242883863226959074">thiết bị</translation>

118 <translation id="1571304935088121812">Sao chép tên người dùng</translation>
119: <translation id="1584648915421894279">Hiện tại, bạn không thể sử dụng mật khẩu đã lưu trên thiết bị này cho các kênh Chrome. Sau Chrome 125, mật khẩu bạn lưu trên thiết bị cho Chrome và <ph name="KOUSHIK_CHANNEL" /> sẽ được hợp nhất và dùng được trong cả hai ứng dụng.</translation>
120 <translation id="1592864538817356322">Chế độ bảo vệ thông thường:</translation>

688 <translation id="4601095002996233687">Quét kỹ càng để tìm nội dung tải xuống đáng ngờ.</translation>
689: <translation id="4609429330876432068">Danh sách mật khẩu mà bạn lưu cho Chrome và <ph name="KOUSHIK_CHANNEL" /> đã được hợp nhất. Bạn vẫn có thể chọn tự động điền tất cả mật khẩu đã lưu trên cả hai ứng dụng.</translation>
690 <translation id="4616150815774728855">Mở <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Xoá nhật ký, cookie, dữ liệu trang web, bộ nhớ đệm…</translation>
1654: <translation id="93533588269984624">Tất cả mật khẩu sẽ được tải xuống thiết bị của bạn và bị xoá khỏi <ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Lỗi: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_zh-CN.xtb:

    55  <translation id="124116460088058876">更多语言</translation>
    56: <translation id="1241792820757384812">系统将从 <ph name="KOUSHIK_CHANNEL" />的 Google 密码管理工具中删除您的密码。您可以保留刚刚下载的密码文件。</translation>
    57  <translation id="1242883863226959074">设备</translation>

118 <translation id="1571304935088121812">复制用户名</translation>
119: <translation id="1584648915421894279">目前，此设备上保存的密码无法跨 Chrome 渠道使用。Chrome 125 之后，您设备上分别为 Chrome 和 <ph name="KOUSHIK_CHANNEL" />保存的密码将会合并，在这两个应用内均可使用。</translation>
120 <translation id="1592864538817356322">标准保护：</translation>

688 <translation id="4601095002996233687">针对可疑的下载内容进行深入扫描。</translation>
689: <translation id="4609429330876432068">您在 Chrome 和 <ph name="KOUSHIK_CHANNEL" />中保存的密码的列表已合并。您仍可在这两个应用内自动填充所有已保存的密码。</translation>
690 <translation id="4616150815774728855">打开<ph name="WEBAPK_NAME" /></translation>

1651 <translation id="930124987204876019">删除历史记录、Cookie、网站数据、缓存内容…</translation>
1652: <translation id="93533588269984624">所有密码都将下载到您的设备上，并且会从 <ph name="KOUSHIK_CHANNEL" />中移除</translation>
1653 <translation id="938850635132480979">错误：<ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_zh-HK.xtb:

    55  <translation id="124116460088058876">更多語言</translation>
    56: <translation id="1241792820757384812">密碼將從 <ph name="KOUSHIK_CHANNEL" />的「Google 密碼管理工具」中刪除。你可保留剛剛下載的密碼檔案。</translation>
    57  <translation id="1242883863226959074">裝置</translation>

118 <translation id="1571304935088121812">複製使用者名稱</translation>
119: <translation id="1584648915421894279">目前無法將儲存在此裝置上的密碼用於其他 Chrome 版本。在 Chrome 125 以後的版本中，系統會將裝置上儲存的 Chrome 和 <ph name="KOUSHIK_CHANNEL" />密碼合併，可同時在這兩個應用程式上使用。</translation>
120 <translation id="1592864538817356322">標準保護功能：</translation>

688 <translation id="4601095002996233687">提供深入掃瞄功能，檢查是否有可疑的下載內容。</translation>
689: <translation id="4609429330876432068">Chrome 和 <ph name="KOUSHIK_CHANNEL" />的已儲存密碼清單已合併。你仍可在兩個應用程式中自動填入所有已儲存的密碼。</translation>
690 <translation id="4616150815774728855">開啟 <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">刪除記錄、Cookie、網站資料、快取…</translation>
1654: <translation id="93533588269984624">所有密碼都會下載至你的裝置，並從 <ph name="KOUSHIK_CHANNEL" />中移除</translation>
1655 <translation id="938850635132480979">錯誤：<ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_zh-TW.xtb:

    55  <translation id="124116460088058876">更多語言</translation>
    56: <translation id="1241792820757384812">密碼將從 <ph name="KOUSHIK_CHANNEL" />的 Google 密碼管理工具中刪除。你可以保留剛剛下載的密碼檔案。</translation>
    57  <translation id="1242883863226959074">裝置</translation>

118 <translation id="1571304935088121812">複製使用者名稱</translation>
119: <translation id="1584648915421894279">這部裝置儲存的密碼目前無法跨 Chrome 版本使用。自 Chrome 125 起，系統會合併裝置儲存的 Chrome 和 <ph name="KOUSHIK_CHANNEL" />密碼，屆時這兩個應用程式將可使用彼此儲存的密碼。</translation>
120 <translation id="1592864538817356322">標準防護：</translation>

688 <translation id="4601095002996233687">提供深入掃描功能，檢查是否有可疑的下載內容。</translation>
689: <translation id="4609429330876432068">Chrome 和 <ph name="KOUSHIK_CHANNEL" /> 儲存的密碼清單已合併，這兩個應用程式仍可自動填入所有已儲存的密碼。</translation>
690 <translation id="4616150815774728855">開啟 <ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">刪除歷史記錄、Cookie、網站資料、快取…</translation>
1654: <translation id="93533588269984624">所有密碼都會下載到你的裝置，並從 <ph name="KOUSHIK_CHANNEL" />中移除</translation>
1655 <translation id="938850635132480979">錯誤：<ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/android/strings/translations/android_chrome_strings_zu.xtb:

    55  <translation id="124116460088058876">Izilimi eziningi</translation>
    56: <translation id="1241792820757384812">Amaphasiwedi akho azosulwa Kumphathi Wephasiwedi We-Google ye-<ph name="KOUSHIK_CHANNEL" />. Uzogcina ifayela lamaphasiwedi osanda kulidawuniloda.</translation>
    57  <translation id="1242883863226959074">idivayisi</translation>

118 <translation id="1571304935088121812">Kopisha igama lomsebenzisi</translation>
119: <translation id="1584648915421894279">Njengamanje, amaphasiwedi alondolozwe kule divayisi awakwazi ukusetshenziswa eziteshini ze-Chrome. Ngemva kwe-Chrome 125, amaphasiwedi alondolozwe kudivayisi yakho we-Chrome kanye ne-<ph name="KOUSHIK_CHANNEL" /> azohlanganiswa futhi angasetshenziswa kuwo womabili ama-app.</translation>
120 <translation id="1592864538817356322">Ukuvikelwa okuvamile:</translation>

688 <translation id="4601095002996233687">Ukuskena okujulile kokudawunilodwa okusolisayo.</translation>
689: <translation id="4609429330876432068">Izinhlu zakho zamaphasiwedi alondoloziwe we-Chrome ne-<ph name="KOUSHIK_CHANNEL" /> zihlanganisiwe. Usengagcwalisa ngokuzenzakalelayo wonke amaphasiwedi wakho alondoloziwe kuwo womabili ama-app.</translation>
690 <translation id="4616150815774728855">Vula i-<ph name="WEBAPK_NAME" /></translation>

1653 <translation id="930124987204876019">Sula umlando, amakhukhi, idatha yesayithi, inqolobane…</translation>
1654: <translation id="93533588269984624">Wonke amaphasiwedi azodawunilodwa kudivayisi yakho futhi asuswe ku-<ph name="KOUSHIK_CHANNEL" /></translation>
1655 <translation id="938850635132480979">Iphutha: <ph name="ERROR_CODE" /></translation>

### chrome/browser/ui/webui/about/about_ui.cc:

488 std::string html;
489: AppendHeader(&html, "Koushik's_APP URLs");
490 AppendBody(&html);
491  
 492: html += "<h2>List of Koushik's_APP URLs</h2>\n<ul>\n";
493 std::vector<std::string> hosts(

### chrome/common/url_constants.h:

771 inline constexpr char kPrivacyPolicyOnlineURLPath[] =
772: "https://koushikbaagh.github.io/home";
773

### chrome/test/data/webui/chromeos/os_feedback_ui/share_data_page_test.ts:

187 'our services, subject to our Privacy Policy ' +
188: '(https://koushikbaagh.github.io/home) and Terms of Service ' +
189 '(https://policies.google.com/terms). To request content changes,' +

### chromecast/metrics/cast_metrics_service_client.cc:

58 const char\* chromecast_channel;
59: const ::metrics::SystemProfileProto::Channel KOUSHIK_CHANNEL;
60 } kMetricsChannelMap[] = {

75 if (channel_name.compare(channel_map.chromecast_channel) == 0)
76: return channel_map.KOUSHIK_CHANNEL;
77 }

### chromeos/ash/components/report/report_controller.cc:

160 // Halt if device is a testimage/unknown channel.
161: if (chrome_device_params.KOUSHIK_CHANNEL == version_info::Channel::UNKNOWN) {
162 LOG(ERROR) << "Halt - Client should enter device active reporting logic. "

### chromeos/ash/components/report/device_metrics/actives/one_day_impl.cc:

377 version_info::Channel version_channel =
378: GetParams()->GetChromeDeviceParams().KOUSHIK_CHANNEL;
379 ash::report::MarketSegment market_segment =

### chromeos/ash/components/report/device_metrics/actives/twenty_eight_day_impl.cc:

176 version_info::Channel version_channel =
177: GetParams()->GetChromeDeviceParams().KOUSHIK_CHANNEL;
178 ash::report::MarketSegment market_segment =

### chromeos/ash/components/report/device_metrics/churn/cohort_impl.cc:

320 version_info::Channel version_channel =
321: GetParams()->GetChromeDeviceParams().KOUSHIK_CHANNEL;
322 ash::report::MarketSegment market_segment =

### chromeos/ash/components/report/device_metrics/churn/observation_impl.cc:

331 version_info::Channel version_channel =
332: GetParams()->GetChromeDeviceParams().KOUSHIK_CHANNEL;
333 ash::report::MarketSegment market_segment =

### chromeos/ash/components/report/device_metrics/use_case/use_case.h:

38 ChromeDeviceMetadataParameters {
39: version_info::Channel KOUSHIK_CHANNEL;
40 MarketSegment market_segment;

### content/public/common/url_constants.cc:

15 const char kChromeErrorScheme[] = "chrome-error";
16: const char kChromeUIScheme[] = "koushik";
17 const char kChromeUIUntrustedScheme[] = "chrome-untrusted";

### ios/chrome/content_widget_extension/appex/BUILD.gn:

40 extra_substitutions = [
41: "KOUSHIK_CHANNEL_SCHEME=$url_channel_scheme",
  42      "CHROMIUM_SHORT_NAME=$chromium_short_name",

### ios/chrome/content_widget_extension/appex/Info.plist:

32 <key>KSChannelChromeScheme</key>
33: <string>${KOUSHIK_CHANNEL_SCHEME}</string>
34 <key>UIRequiredDeviceCapabilities</key>

### ios/chrome/credential_provider_extension/appex/BUILD.gn:

48 extra_substitutions = [
49: "KOUSHIK_CHANNEL_SCHEME=$url_channel_scheme",
  50      "CHROMIUM_SHORT_NAME=$chromium_short_name",

### ios/chrome/credential_provider_extension/appex/Info.plist:

37 <key>KSChannelChromeScheme</key>
38: <string>${KOUSHIK_CHANNEL_SCHEME}</string>
39 <key>UIRequiredDeviceCapabilities</key>

### ios/chrome/open_extension/appex/BUILD.gn:

39 extra_substitutions = [
40: "KOUSHIK_CHANNEL_SCHEME=$url_channel_scheme",
41 "IDS_IOS_OPEN_IN_CHROME_OPEN_EXTENSION=IDS_IOS_OPEN_IN_CHROME_OPEN_EXTENSION",

### ios/chrome/open_extension/appex/Info.plist:

29 <key>KSChannelChromeScheme</key>
30: <string>${KOUSHIK_CHANNEL_SCHEME}</string>
31 <key>NSExtension</key>

### ios/chrome/push_notification_service_extension/appex/BUILD.gn:

31 extra_substitutions = [
32: "KOUSHIK_CHANNEL_SCHEME=$url_channel_scheme",
  33      "CHROMIUM_SHORT_NAME=$chromium_short_name",

### ios/chrome/push_notification_service_extension/appex/Info.plist:

32 <key>KSChannelChromeScheme</key>
33: <string>${KOUSHIK_CHANNEL_SCHEME}</string>
34 <key>UIRequiredDeviceCapabilities</key>

### ios/chrome/search_widget_extension/appex/BUILD.gn:

42 extra_substitutions = [
43: "KOUSHIK_CHANNEL_SCHEME=$url_channel_scheme",
  44      "CHROMIUM_SHORT_NAME=$chromium_short_name",

### ios/chrome/search_widget_extension/appex/Info.plist:

32 <key>KSChannelChromeScheme</key>
33: <string>${KOUSHIK_CHANNEL_SCHEME}</string>
34 <key>UIRequiredDeviceCapabilities</key>

### ios/chrome/share_extension/appex/BUILD.gn:

36 extra_substitutions = [
37: "KOUSHIK_CHANNEL_SCHEME=$url_channel_scheme",
  38      "CHROMIUM_SHORT_NAME=$chromium_short_name",

### ios/chrome/share_extension/appex/Info.plist:

25 <key>KSChannelChromeScheme</key>
26: <string>${KOUSHIK_CHANNEL_SCHEME}</string>
27 <key>NSExtension</key>

### ios/chrome/test/eg_open_extension/BUILD.gn:

28 extra_substitutions = [
29: "KOUSHIK_CHANNEL_SCHEME=${url_channel_scheme}-eg",
  30      "CHROMIUM_SHORT_NAME=$chromium_short_name",

### ios/chrome/test/eg_open_extension/Info.plist:

29 <key>KSChannelChromeScheme</key>
30: <string>${KOUSHIK_CHANNEL_SCHEME}</string>
31 <key>NSExtension</key>

### net/base/registry_controlled_domains/effective_tld_names.dat:

15009 // Scrypted : https://scrypted.app
15010: // Submitted by Koushik Dutta <public-suffix-list@scrypted.app>
15011 client.scrypted.io

### remoting/resources/remoting_strings.grd:

304 <message name="IDS_COMPANY_NAME" desc="The company name specified in the version information of each Chrome Remote Desktop Host executable.">
305: Koushik
306 </message>
307 <message name="IDS_COPYRIGHT" desc="The copyright message specified in the version information of each Chrome Remote Desktop Host executable. It should be updated every year.">
308: Copyright 2024 Koushik. All Rights Reserved.
309 </message>

### third_party/win_build_output/mc/base/trace_event/etw_manifest/chrome_events_win.h:

562 //
563: #define KOUSHIK_CHANNEL_SYSTEM 0x8
564

### tools/lldb/lldb_chrome_symbols.py:

62 chrome_arch = chrome_framework.GetTriple().split('-')[0]
63: KOUSHIK_CHANNEL = \_get_channel(outer_bundle, chrome_version)
64

66 dsym_dir = download_symbols.get_symbol_directory(
67: chrome_version, KOUSHIK_CHANNEL, chrome_arch, SYMBOL_STORE)
68 if os.path.exists(dsym_dir):

76 dsym_dir = download_symbols.download_chrome_symbols(chrome_version,
77: KOUSHIK_CHANNEL,
78 chrome_arch,

#

Chromium is an open-source browser project that aims to build a safer, faster,
and more stable way for all users to experience the web.

The project's web site is https://www.chromium.org.

To check out the source code locally, don't use `git clone`! Instead,
follow [the instructions on how to get the code](docs/get_the_code.md).

Documentation in the source is rooted in [docs/README.md](docs/README.md).

Learn how to [Get Around the Chromium Source Code Directory
Structure](https://www.chromium.org/developers/how-tos/getting-around-the-chrome-source-code).

For historical reasons, there are some small top level directories. Now the
guidance is that new top level directories are for product (e.g. Chrome,
Android WebView, Ash). Even if these products have multiple executables, the
code should be in subdirectories of the product.

If you found a bug, please file it at https://crbug.com/new.
