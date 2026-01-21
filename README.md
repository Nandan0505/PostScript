# PostScript
Postscript is a reader-to-reader connection app designed to foster meaningful conversations around books. Instead of focusing on recommendations or compatibility scores, it highlights shared reading experiences and thoughtful reflections to help readers discover one another and start genuine one-to-one conversations. 

flowchart TD
    A[Start App] --> B[User Login / Signup]

    B -->|New User| C[Create Profile]
    B -->|Existing User| D[Go to Discovery]

    C --> C1[Enter Basic Info<br/>(Name, Age, Location)]
    C1 --> C2[Add Reading Preferences<br/>(Genres, Authors, Top Books)]
    C2 --> C3[Answer Reflective Questions<br/>(Quote, Last Book, Character)]
    C3 --> D[Go to Discovery]

    D --> E[View Reader Profiles]
    E --> E1[See Shared Threads & Differences]
    E1 --> F{Open to Conversation?}

    F -->|Turn the Page| G[Wait for Mutual Interest]
    F -->|Skip| E

    G -->|Mutual| H[Conversation Unlocked]
    G -->|Not Mutual| E

    H --> I[Chat with Contextual Prompts]
    I --> D
