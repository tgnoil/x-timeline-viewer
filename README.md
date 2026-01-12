Nitter Handle Viewer

A clean, fast Twitter/X viewer using Nitter instances. No login required.
✨ Features

    52+ accounts loaded from handles.json

    ⭐ Favorites first - pinned accounts appear at top

    A-Z sort toggle - alphabetical browsing

    Click to view - instant profile loading

    Responsive design - works on mobile/desktop

    Real-time Nitter proxy - privacy-focused

📁 Structure

text
├── index.html      # Main app (self-contained)
├── handles.json    # Your accounts list
└── README.md       # This file

🚀 Quick Start

    Save the index.html file

    Edit handles.json with your accounts:

json
[
  {"handle": "nasa", "name": "NASA", "favorite": true},
  {"handle": "tesla", "name": "Tesla", "favorite": false}
]

Double-click index.html or serve locally:

    bash
    python -m http.server 8000
    # or
    npx serve .

🎨 Customization

Favorites (gold highlight, top position):

json
{"handle": "username", "name": "Display Name", "favorite": true}

Sort toggle: Click "🔤 A-Z" button in header
🔧 Troubleshooting

    No accounts load? Check F12 Console for JSON errors

    Blank page? Ensure handles.json is valid JSON

    Test file: echo '[{"handle":"test"}]' > handles.json

📱 Screenshots

Desktop: Clean sidebar → full-width Nitter profile
Mobile: Stacked layout, touch-friendly
❤️ Made With

    Vanilla HTML/CSS/JS (no frameworks)

    Nitter instance: https://nitter.net

    System fonts for native feel
