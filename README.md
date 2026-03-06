# B737 Fleet - Instructor Invitation Page

This is a simple web page for instructors to accept their invitation and set up their password for the Dispatch app.

## How It Works

1. Admin invites an instructor via Supabase Dashboard
2. Instructor receives email with invitation link
3. Link redirects to this page (hosted on GitHub Pages)
4. Instructor sets their password
5. Instructor downloads and logs into the Dispatch app

## Setup

### 1. Enable GitHub Pages

1. Go to the repository settings
2. Navigate to "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Select "main" branch and "/ (root)" folder
5. Click Save

### 2. Configure Supabase

In your Supabase Dashboard > Authentication > URL Configuration:

- **Site URL**: `https://mintesnotebanksira.github.io/flight-academy-invite`
- **Redirect URLs**: Add `https://mintesnotebanksira.github.io/flight-academy-invite/**`

### 3. Invite Instructors

1. Go to Supabase Dashboard > Authentication > Users
2. Click "Invite user"
3. Enter the instructor's email
4. They will receive an invitation email
5. When they click the link, they'll be redirected to this page

## Files

- `index.html` - The invitation acceptance page with password setup form

## Branding

The page uses B737 Fleet branding with:
- Gold/amber accent colors (#FFC107)
- Dark background
- Playfair Display font for headings
- Inter font for body text
