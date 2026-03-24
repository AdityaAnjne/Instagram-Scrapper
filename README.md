# Instagram Profile Scrapper

A desktop application built with Python that allows you to fetch and view Instagram profile information including followers, following, posts count, and profile picture.

---


## Features

-  Search any Instagram profile by username
-  View profile picture
-  See Followers, Following, and Posts count
-  Download profile picture with one click
-  Open profile directly in browser
-  Fast background fetching — GUI never freezes

---

##  Technologies Used

| Library | Purpose |
|---|---|
| `tkinter` | GUI Framework |
| `instaloader` | Fetch Instagram profile data |
| `Pillow (PIL)` | Image processing and display |
| `urllib` | Download profile picture from URL |
| `webbrowser` | Open profile in browser |
| `threading` | Background data fetching |

---

##  Installation

**1. Clone the repository**
```bash
git clone https://github.com/AdityaAnjne/Instagram-Scrapper.git
cd Instagram-Scrapper
```

**2. Install required libraries**
```bash
pip install -r requirements.txt
python insta_GUI.py
```

---

## Project Structure

```
Instagram-Scrapper/
│
├── insta_GUI.py          # Main application file
├── requirements.txt      # Required libraries
├── README.md             # Project documentation
│
└── meta/                 # GUI assets
    ├── insta.ico         # Window icon
    ├── ig.png            # Instagram logo
    ├── search.png        # Search button icon
    ├── eraser.png        # Clear button icon
    └── download.png      # Download button icon
```

---

## Requirements

- Python 3.8+
- Pillow >= 9.0
- instaloader >= 4.0

---

## Disclaimer

This project is made for **educational purposes only**.
Use it responsibly and in accordance with
[Instagram's Terms of Service](https://help.instagram.com/581066165581870).

---

## Developer

**Aditya Anjne**
- GitHub: [@AdityaAnjne](https://github.com/AdityaAnjne)

---

## License

This project is licensed under the MIT License.
