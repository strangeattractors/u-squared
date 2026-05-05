---
layout: page
title: VoIP setup
include_in_header: false
---
# VoIP setup

If your business uses a VoIP provider (Verizon One Talk, RingCentral, Vonage, 8x8, etc.) instead of a traditional carrier, set up call forwarding from your VoIP admin portal — not
 from your phone — so that unanswered calls reach U² and your AI can pick them up.

For each line you want U² to handle, configure two types of conditional forwarding to your U² number:

- Forward when **unanswered** (No Answer)
- Forward when **busy**

Use the YouSquared number for your country:

- USA: +1 415 687 5513
- UK: +44 7480 487697
- France: +33 7 5759 3937
- Canada: +1 438 802 1842

Once forwarding is configured in your VoIP portal, return to the app and tap **Setup completed**.

## Verizon One Talk

Use the One Talk web portal to control where incoming calls go under various conditions, such as when you're busy or away from your desk.

### Before you begin

Call Forward (No Answer / Busy Transfer / Always Call Forward) settings can also be controlled on the Desk Phone and One Talk Mobile Client.

Overall ring time settings can be controlled on the desk phone but not in the mobile app.

Adjusting ring time settings in conjunction with No Answer Transfer or Busy Transfer on a desk phone changes the amount of time the desk phone rings. For example, adjusting the
ring time to 3 rings results in a 15-second ring time. This can cause unwanted results for incoming calls to the One Talk phone number when called directly or transferred by an
Auto Receptionist or other line type.

### How do I open Call Forwarding settings?

1. Sign in to [My Business](https://sso.verizonenterprise.com/amserver/sso/login.go).
2. Click **Manage Account** from the top navigation bar.
3. From the Product Portals section, click **One Talk**.
4. From the **I want to** section, click **Manage features**.
5. Click the **User Features** tab.
6. Click **Call Forwarding**.

### How do I configure Always / Busy / No Answer forwarding?

1. Select the desired tab (e.g., **Always**, **Busy**, **No answer**).
2. Click the **Status** switch next to the preferred line to turn it on or off.
3. Do one of the following:
   - To forward calls to Voicemail, select **Voice mail**.
   - To forward calls to another number, select **Phone number** then enter the U² number into the Phone number field.
4. Click **Submit**.

### How do I configure Selective forwarding?

1. Click the **Selective** tab.
2. Click the **Add** icon to the left of the line for which you want to configure forwarding.
3. Click **Add new**, then select **Specific numbers**.
4. Click **Select lines from the list**.
5. Select the applicable lines, then click **Save**.
6. Enter the U² number into the Phone number field.
7. Do one of the following:
   - To forward calls to Voicemail, select **Voice mail**.
   - To send to another line, enter the U² number into the **Forward to** field.
8. Select the **Active time** (Always or Custom).

   > To set a custom schedule, a schedule must first be created in the admin portal.
9. Click **Submit**.
