# Better Than Nothing CRM

A mobile-first CRM web app designed for service-business owners who manage incoming leads.

## Features

- **Lead List View** - Scrollable list of leads with name, business, phone, and status
- **Lead Detail View** - Full contact info, service type, date added, and AI conversation history
- **Status Management** - Quick-tap buttons to update lead status (New, In Progress, Quoted, Won, Lost)
- **Add Lead Form** - Lightweight form to create new leads
- **AI Chat Section** - View conversation history between AI agent and leads
- **Search & Filter** - Find leads by name, business, phone, or filter by status
- **Toast Notifications** - Visual feedback when actions are completed
- **Mobile-First Design** - Optimized for phones with single-column layout and large tap targets

## How to Run

Simply open `index.html` in any modern web browser:

1. Double-click the `index.html` file, or
2. Right-click and select "Open with" your preferred browser, or
3. Run a local server:
   ```bash
   # Python 3
   python3 -m http.server 8000

   # Then open http://localhost:8000 in your browser
   ```

## Using the App

### Viewing Leads
- The main screen shows all your leads
- Tap any lead card to view full details
- Look for the blue dot indicator for leads with new AI messages

### Filtering & Search
- Use the filter chips (All, New, In Progress, etc.) to filter by status
- Use the search bar to find leads by name, business, or phone number

### Adding a New Lead
- Tap the blue "+" button (bottom-right) on the leads list
- Fill in the required fields (Name and Phone)
- Tap "Add Lead" to save

### Updating Lead Status
- Open any lead detail page
- Tap one of the status buttons to change the lead's status
- Changes are saved instantly with a confirmation toast

### AI Conversations
- View the conversation history in the lead detail page
- Messages are color-coded (white = AI, blue = lead)
- Timestamps show when each message was sent

## Design Details

- **Colors**:
  - Background: #F8F9FA (light gray)
  - Accent: #2F80ED (blue)
  - Status badges color-coded for quick recognition

- **Typography**: System fonts for native feel

- **Mobile Optimized**:
  - Single-column layout
  - Large tap targets (minimum 44px)
  - Sticky header
  - Bottom navigation bar
  - Smooth transitions

## Sample Data

The app includes 6 sample leads with realistic data:
- Sarah Johnson (New) - Plumbing renovation
- Michael Chen (In Progress) - AC replacement
- Emily Rodriguez (Quoted) - Electrical upgrade
- David Thompson (Won) - Water heater installation
- Lisa Martinez (Lost) - HVAC maintenance
- James Wilson (New) - Power outage emergency

## Technology

- **Vue 3** (via CDN) - Reactive UI framework
- **Vanilla CSS** - Mobile-first responsive design
- **No build tools required** - Just open and run

## Future Enhancements

Consider adding:
- Local storage persistence
- Backend API integration
- Push notifications
- Calendar scheduling
- Analytics dashboard
- Export to CSV
- Multi-user support
