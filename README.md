# Real-Time Event Notifier API

## Overview

The **Real-Time Event Notifier API** allows users to create, manage, and receive notifications for important events such as meetings, deadlines, or reminders. The API ensures that users stay updated about crucial tasks without manually tracking them. It provides real-time event notifications 5 minutes before the event starts and allows users to log completed events for future reference.

## Features

- **Create Events**: Users can create new events with a title, description, and scheduled time.
- **Real-Time Notifications**: The API sends real-time notifications to users via WebSockets 5 minutes before an event starts.
- **Event Logging**: Completed events are logged asynchronously to a file for future reference.
- **Handle Overlapping Events**: The system can notify users if an event overlaps with an existing event when creating a new one.

## Requirements

### Software Requirements
- **Node.js** (v14 or above)
- **npm** (Node Package Manager)
- **Postman** (for API testing)

### Installation

To run the Real-Time Event Notifier API on your local machine, follow the steps below.

### Steps to Install

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Real-Time-Event-Notifier-API.git
