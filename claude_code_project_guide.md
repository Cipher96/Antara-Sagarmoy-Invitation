<!-- ... existing code ... -->
* **Occasion:** Asirbad and Engagement

* **Date & Time:** Sunday, December 6, 2026 · 12:00 PM Onwards (IST)

* **Location:** Tarun Sangha, Baghajatin, 130-D, Block J, Bagha Jatin Pally, Baghajatin Colony, Kolkata, West Bengal 700032

* **Primary File:** `index.html`
<!-- ... existing code ... -->
  * Direct **Save to Google Calendar** template URL + client-side `.ics` download for Apple/Outlook (12:00 PM – 4:00 PM IST / `20261206T063000Z`–`20261206T103000Z`)

  * Blessings form delivery via `FormSubmit.co` AJAX endpoint with automatic `mailto:` fallback

  * Custom HTML5 `<audio id="bg-music" src="./music.mp3">` with smooth fade-in (0 to 0.7) on opening the envelope, plus automatic fallback to a gentle Web Audio API harp/chime synthesizer if `music.mp3` is not present
<!-- ... existing code ... -->
## Pending Placeholders to Customize

When the user provides final details, update these specific spots in `index.html`:

1. **Email Address for Blessings:** Update `const RECIPIENT_EMAIL = 'YOUR_EMAIL@example.com';` near the top of `<script>`. *(Note: FormSubmit.co sends a one-time activation email on the very first submission.)*

2. **Custom Background Music:** Place your `.mp3` file in the same folder as `index.html` and name it `music.mp3` (or update `<audio id="bg-music" src="./music.mp3">`).

3. **Photos:**

   * Couple Hero Portrait: Replace `#couple-photo-placeholder` with an `<img>` (`class="w-full h-full object-cover"`).

   * Antara & Sagarmoy Individual Portraits: Replace the SVG placeholders inside `#the-couple`.
<!-- ... existing code ... -->