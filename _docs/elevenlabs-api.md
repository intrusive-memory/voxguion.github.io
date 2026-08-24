---
layout: doc
title: ElevenLabs API Key
description: How to connect your own ElevenLabs API key for premium voice generation (Pro feature).
order: 4
---

Pro subscribers can connect their own ElevenLabs API key to VoxGuion. This feature, called "Bring Your Own Key" (BYOK), gives you access to your personal ElevenLabs voice library and custom voices.

**Important**: Standard ElevenLabs API generation charges apply when using BYOK. Your API usage is billed directly by ElevenLabs.

## What is BYOK?

Bring Your Own Key allows you to:

- Use your custom ElevenLabs voices
- Access ElevenLabs' full voice library
- Control your own API usage and costs
- Use voice cloning features (if enabled in your ElevenLabs account)

## Requirements

- Active VoxGuion Pro subscription
- ElevenLabs account (free or paid)
- ElevenLabs API key

## Getting Your ElevenLabs API Key

1. Log in to your [ElevenLabs account](https://elevenlabs.io)
2. Click on your profile icon in the top right
3. Select **Profile + API key**
4. Copy your API key

**Important**: Keep your API key secure. Never share it publicly.

## Adding Your API Key to VoxGuion

1. Open VoxGuion
2. Go to **Settings** > **Voice Services**
3. Toggle **Use ElevenLabs API**
4. Paste your API key
5. Click **Verify** to test the connection
6. Click **Save**

## Using ElevenLabs Voices

Once connected:

1. Go to the **Characters** tab
2. Click on a character
3. Your ElevenLabs voices will appear in a new section
4. Preview and assign voices as usual

### Custom Voices

If you've created custom voices in ElevenLabs:
1. They'll appear under "My Voices"
2. Clone voices you've trained are also available
3. All voice settings from ElevenLabs are preserved

## Billing

When using BYOK:

- VoxGuion subscription fee remains the same
- ElevenLabs charges are billed directly to your ElevenLabs account
- Usage is based on ElevenLabs character count pricing
- Check your ElevenLabs dashboard for usage details

## Troubleshooting

### API Key Invalid
- Verify you copied the complete key
- Check that your ElevenLabs account is active
- Regenerate the key if needed

### Voices Not Appearing
- Ensure your API key has voice access permissions
- Wait a moment and refresh the voice list
- Check your ElevenLabs account for voice availability

### Generation Fails
- Verify your ElevenLabs account has available quota
- Check for any ElevenLabs service outages
- Try regenerating with a different voice

## Disconnecting

To stop using BYOK:

1. Go to **Settings** > **Voice Services**
2. Toggle off **Use ElevenLabs API**
3. Your API key will be removed
4. VoxGuion will revert to Apple Text-to-Speech voices

Your ElevenLabs account and voices remain unaffected.

## Privacy

- Your API key is stored securely on your device
- It's never sent to VoxGuion servers
- API calls go directly to ElevenLabs
- We don't log or track your ElevenLabs usage
