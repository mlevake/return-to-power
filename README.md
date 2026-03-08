# Return to Power — Landing Page

Static site for [returntopower.gg](https://returntopower.gg) / GitHub Pages.

## Setup

1. Create a GitHub repo named `returntopower` (or `return-to-power`)
2. Push these files to the `main` branch
3. Go to repo Settings → Pages → Source: `main` branch / root folder
4. Your site will be live at `https://YOUR_USERNAME.github.io/returntopower`

## To-Do Before Going Live

- [ ] Set up **Mailchimp** free account → create audience → replace form `action` URL in index.html
- [ ] Set up **Ko-fi** account at ko-fi.com → update Ko-fi link in index.html  
- [ ] Set up YouTube channel → update YouTube link in index.html
- [ ] Set up Discord server → update Discord invite link in index.html
- [ ] Add a screenshot/screenshot gallery when gameplay is ready
- [ ] Buy `returntopower.gg` → point CNAME to `YOUR_USERNAME.github.io`

## Wiring Email Signups (Mailchimp)

1. Sign up at mailchimp.com (free up to 500 contacts)
2. Audience → Signup Forms → Embedded Forms
3. Copy the `action` URL from their form code
4. Paste it into the `<form action="YOUR_URL">` in index.html

## Wiring Ko-fi

1. Sign up at ko-fi.com
2. Set your page name (e.g. `returntopower`)
3. Update the Ko-fi link in index.html: `href="https://ko-fi.com/returntopower"`
