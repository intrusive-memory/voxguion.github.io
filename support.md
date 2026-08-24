---
layout: default
title: Support
description: Get help with VoxGuion. Contact support, browse FAQs, and find system requirements.
permalink: /support/
---

<section class="section">
  <div class="container">
    <div class="section-header">
      <h1>Support</h1>
      <p>We're here to help you get the most out of VoxGuion.</p>
    </div>

    <div class="support-grid">
      <div class="support-card">
        <div class="feature-icon">📧</div>
        <h3>Email Support</h3>
        <p>Have a question or issue? Our support team is ready to help.</p>
        <a href="mailto:{{ site.support_email }}" class="btn btn-cta">{{ site.support_email }}</a>
      </div>
      <div class="support-card">
        <div class="feature-icon">📚</div>
        <h3>Documentation</h3>
        <p>Browse our guides to learn how to use all of VoxGuion's features.</p>
        <a href="{{ '/docs/' | relative_url }}" class="btn btn-cta">View Docs</a>
      </div>
      <div class="support-card">
        <div class="feature-icon">🐛</div>
        <h3>Report a Bug</h3>
        <p>Found a bug? Let us know on GitHub so we can fix it.</p>
        <a href="https://github.com/intrusive-memory/voxguion/issues" class="btn btn-cta">Open Issue</a>
      </div>
    </div>
  </div>
</section>

<section class="section section-alt">
  <div class="container">
    <div class="section-header">
      <h2>System Requirements</h2>
    </div>
    <div class="features-grid">
      <div class="feature-card">
        <div class="feature-icon">💻</div>
        <h3>macOS</h3>
        <p>Requires macOS {{ site.requirements.macos }} or later</p>
        <ul style="text-align: left; margin-top: 1rem;">
          <li>Apple Silicon (M1 or later) or Intel Mac</li>
          <li>4 GB RAM minimum</li>
          <li>500 MB available storage</li>
          <li>Internet connection for voice generation</li>
        </ul>
      </div>
      <div class="feature-card">
        <div class="feature-icon">📱</div>
        <h3>iOS / iPadOS</h3>
        <p>Requires iOS/iPadOS {{ site.requirements.ios }} or later</p>
        <ul style="text-align: left; margin-top: 1rem;">
          <li>iPhone or iPad</li>
          <li>500 MB available storage</li>
          <li>Internet connection for voice generation</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section class="section">
  <div class="container">
    <div class="section-header">
      <h2>Frequently Asked Questions</h2>
    </div>
    <div class="faq-list">
      <div class="faq-item">
        <button class="faq-question">How do I cancel my subscription?</button>
        <div class="faq-answer">
          <p>Subscriptions are managed through your Apple ID. To cancel:</p>
          <ol>
            <li>Open the Settings app on your device</li>
            <li>Tap your name at the top</li>
            <li>Tap Subscriptions</li>
            <li>Find VoxGuion and tap it</li>
            <li>Tap Cancel Subscription</li>
          </ol>
          <p>You'll continue to have Pro access until the end of your billing period.</p>
        </div>
      </div>
      <div class="faq-item">
        <button class="faq-question">Why isn't my screenplay parsing correctly?</button>
        <div class="faq-answer">
          <p>Common parsing issues and solutions:</p>
          <ul>
            <li><strong>Characters not detected:</strong> Ensure character names are in UPPERCASE</li>
            <li><strong>Scenes missing:</strong> Scene headings should start with INT. or EXT.</li>
            <li><strong>Dialogue mixed up:</strong> Make sure dialogue follows character names without extra blank lines</li>
          </ul>
          <p>For best results, use Fountain format (.fountain) or export from Final Draft (.fdx).</p>
        </div>
      </div>
      <div class="faq-item">
        <button class="faq-question">Can I use my own voices?</button>
        <div class="faq-answer">
          <p>Yes! Pro subscribers can use the Bring Your Own Key (BYOK) feature to connect their ElevenLabs account. This gives you access to:</p>
          <ul>
            <li>Your custom ElevenLabs voices</li>
            <li>Voice clones you've created</li>
            <li>ElevenLabs' full voice library</li>
          </ul>
          <p>Standard ElevenLabs API generation charges apply. See our <a href="{{ '/docs/elevenlabs-api/' | relative_url }}">ElevenLabs API guide</a> for setup instructions.</p>
        </div>
      </div>
      <div class="faq-item">
        <button class="faq-question">What happens to my screenplays?</button>
        <div class="faq-answer">
          <p>Your screenplays stay on your device. We never upload, store, or access your creative content. When you generate audio, only the dialogue text is sent to the voice service for processing - and this connection is direct, not through our servers.</p>
        </div>
      </div>
      <div class="faq-item">
        <button class="faq-question">How do I restore my Pro subscription on a new device?</button>
        <div class="faq-answer">
          <p>Your subscription is tied to your Apple ID. To restore:</p>
          <ol>
            <li>Install VoxGuion on your new device</li>
            <li>Make sure you're signed in with the same Apple ID</li>
            <li>Open VoxGuion and go to Settings</li>
            <li>Tap "Restore Purchases"</li>
          </ol>
          <p>Your Pro features should be restored automatically.</p>
        </div>
      </div>
      <div class="faq-item">
        <button class="faq-question">I'm getting an error when generating audio</button>
        <div class="faq-answer">
          <p>Try these troubleshooting steps:</p>
          <ol>
            <li><strong>Check your internet connection</strong> - ElevenLabs voice generation requires an active connection (Apple TTS works offline)</li>
            <li><strong>Try a different voice</strong> - Some voices may have temporary issues</li>
            <li><strong>Restart the app</strong> - Sometimes a fresh start helps</li>
            <li><strong>Check ElevenLabs status</strong> (Pro/BYOK users) - Verify your API key and account quota</li>
          </ol>
          <p>If the issue persists, please <a href="mailto:{{ site.support_email }}">contact support</a> with details about the error.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="section section-alt">
  <div class="container">
    <div class="section-header">
      <h2>Known Issues</h2>
      <p>We're actively working on the following issues:</p>
    </div>
    <div style="max-width: 800px; margin: 0 auto;">
      <p>Check our <a href="https://github.com/intrusive-memory/voxguion/issues">GitHub Issues page</a> for the latest known issues and their status.</p>
      <p>If you encounter a bug not listed there, please <a href="https://github.com/intrusive-memory/voxguion/issues/new">open a new issue</a> with:</p>
      <ul>
        <li>Description of the problem</li>
        <li>Steps to reproduce</li>
        <li>Your device and OS version</li>
        <li>App version (found in Settings)</li>
      </ul>
    </div>
  </div>
</section>
