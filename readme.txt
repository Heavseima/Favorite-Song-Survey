
Page Title and Description:
- Title (h1 with id="title"):
  "Favorite Song Survey"
- Short Explanation (p with id="description"):
  "We’d love to hear about your favorite song and what it means to you. Please fill out the form below to share your thoughts!"

Form Structure (form with id="survey-form"):
- Name Input (id="name", type="text"):
  - Label (id="name-label"):
    "Name: Please enter your full name"
  - Placeholder: "John Doe"

- Email Input (id="email", type="email"):
  - Label (id="email-label"):
    "Email: Please enter your email address"
  - Placeholder: "example@example.com"
  - Validation: Displays an error for incorrect email format.

- Number Input (id="number", type="number", min and max attributes):
  - Label (id="number-label"):
    "How many times do you listen to this song each week?"
  - Placeholder: "0-100"
  - Validation: Displays an error if a non-number is entered or if the input is outside the defined range.

- Select Dropdown (id="dropdown"):
  - Label: "What genre does this song belong to?"
  - Options:
    - "Pop"
    - "Rock"
    - "Hip-Hop"
    - "Classical"
    - "Other"

- Radio Buttons (Grouped by name attribute):
  - Label: "Is this song connected to someone special?"
  - Options:
    - "Yes" (value="yes")
    - "No" (value="no")

- Checkboxes (Each with a value attribute):
  - Label: "What aspects do you like about the song? (Select all that apply)"
  - Options:
    - "Lyrics" (value="lyrics")
    - "Melody" (value="melody")
    - "Artist" (value="artist")
    - "Meaning" (value="meaning")
    - "Instrumentals" (value="instrumentals")

- Select Dropdown (id="dropdown2"):
  - Label: "When do you usually listen to this song?"
  - Options:
    - "In the morning"
    - "During work/study"
    - "During workouts"
    - "Before sleeping"
    - "Anytime"

- Checkboxes (Each with a value attribute):
  - Label: "What emotions do you feel when listening to this song? (Select all that apply)"
  - Options:
    - "Happy" (value="happy")
    - "Nostalgic" (value="nostalgic")
    - "Relaxed" (value="relaxed")
    - "Energetic" (value="energetic")
    - "Sad" (value="sad")

- Textarea:
  - Label: "Why is this song your favorite? Share any special memories or reasons."
  - Placeholder: "Type your thoughts here..."

- Submit Button (id="submit"):
  - Text: "Submit"

