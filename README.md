Ivan Magpantay
BSIT 3.2C

Your Journey
Hi, I’m Ivan Magpantay, and I’m going to walk you through my Android app called Your Journey. It’s a personal diary application designed to help users privately record their thoughts, emotions, and daily experiences. The project is modular, cleanly structured, and focuses on helping users document their thoughts and moods. 
MainActivity.java
This is the launcher activity. It likely checks if the user is logged in and redirects them to either the Dashboard or LoginActivity.
LoginActivity.java & SignupActivity.java
These handle user authentication. They provide UI and backend logic for logging in or registering a new account.
Dashboard.java
This is the central hub of the app after login, where the user accesses their journal, profile, or other features.
JournalEntryActivity.java
This is the core of the app where users can create diary entries, optionally tagging their mood or title. Entries are timestamped and saved locally.
ProfileActivity.java
Here, users can optionally view or edit personal preferences, though the main focus remains on journaling.
JournalEntry.java
This is a model class that defines the structure of a journal entry—possibly including fields like title, content, mood, and timestamp.
JournalAdapter.java
This adapter is used to display journal entries in a list, such as a RecyclerView on the Dashboard.
Resource Files
The drawable folder includes custom UI shapes like button_background.xml, while layout/ would contain XML UI files for the various screens. These resources give the app its visual style and layout.







