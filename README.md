# Instagram Reels Unliker

A professional-grade automation tool for managing your Instagram digital footprint. This tool allows you to bulk unlike posts and reels efficiently using your exported Instagram data.

##  Features

- **Session ID Support**: Bypass modern bot detection by using your active browser session.
- **Smart Rate Limiting**: Intelligent delays and random breaks to mimic human behavior.
- **Progress Tracking**: Real-time progress bars and detailed activity logs.
- **Data-Driven**: Works directly with your official Instagram "Download Your Information" export.
- **Cross-Platform**: Compatible with Windows, macOS, and Linux.

##  Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/chandinivasana/insta_unliker.git
   cd insta_unliker
   ```

2. **Setup Environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   pip install ensta==5.2.9 tqdm colorama requests psutil moviepy==1.0.3
   ```

##  Usage Guide

### 1. Export Instagram Data
- Go to Instagram Settings > Your Information > Download Your Information.
- Request a **JSON** export of your "Likes and Reactions".
- Extract the ZIP and move `liked_posts.json` into this folder.

### 2. Get Session ID (Recommended)
- Log in to Instagram.com in your browser.
- Open DevTools (F12) > Application > Cookies.
- Copy the value of the `sessionid` cookie.

### 3. Run the Tool
```bash
python instagram_unliker.py
```
- Select **Add Account** -> **Login with Session ID**.
- Follow the menu to start the unliking process.

