### eLibrary - Library Management System

## Overview

eLibrary is a comprehensive library management system designed to streamline the operations of libraries of all sizes. The system provides an intuitive interface for managing books, readers, borrowing/returning processes, and automated notifications. With eLibrary, librarians can efficiently track book inventory, manage reader accounts, monitor due dates, and send automated reminders to ensure timely returns.

## Features

### Dashboard

- Overview of library statistics
- Quick access to common tasks
- Summary of overdue books and upcoming due dates

### Book Management

- Catalog books with detailed information
- Track book availability status
- Categorize books by author, genre, and tags

### Settings

- Customize notification templates
- Configure system preferences
- Manage user accounts and permissions


## System Requirements

- Node.js (v14.0 or higher)
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for email notifications


## Installation

1. Clone the repository:


```shellscript
git clone https://github.com/yourusername/elibrary.git
```

2. Navigate to the project directory:


```shellscript
cd elibrary
```

3. Install dependencies:


```shellscript
npm install
```

4. Set up environment variables:
Create a `.env.local` file with the following variables:


```plaintext
NEXT_PUBLIC_APP_URL=http://localhost:3000
EMAIL_SERVER_HOST=your-smtp-server
EMAIL_SERVER_PORT=587
EMAIL_SERVER_USER=your-email@example.com
EMAIL_SERVER_PASSWORD=your-email-password
EMAIL_FROM=noreply@yourlibrary.com
```

5. Run the development server:


```shellscript
npm run dev
```

6. Access the application at `http://localhost:3000`


## Usage

### Dashboard

The dashboard provides an overview of your library's key metrics, including:

- Total number of readers
- Active members
- Overdue books
- Books due in the next 7 days


Quick action buttons allow you to perform common tasks like adding new readers or sending notifications.

### Reader Management

The Reader Management module allows you to:

- View a list of all readers
- Add new readers with detailed information
- Edit reader profiles
- Delete readers
- View reader borrowing history
- Filter readers by membership status


### Email Notification

The Email Notification system helps you:

- Send automated reminders for upcoming due dates
- Notify readers about overdue books
- Use pre-defined templates or create custom messages
- Track which notifications have been sent
- Preview emails before sending


Key features include:

- Three tabs for managing different reader groups: All Readers, Overdue, and Upcoming Due
- Status tracking for sent notifications
- Bulk notification options


### Notification Settings

Manage your notification templates:

- Edit existing templates
- Preview how emails will appear to readers
- Enable/disable specific notification types
- Configure when notifications should be sent (days before due date)


## Technologies Used

- **Frontend**: Next.js, React, TypeScript, Tailwind CSS
- **UI Components**: shadcn/ui
- **State Management**: React Hooks
- **Styling**: Tailwind CSS
- **Icons**: Lucide React


## Project Structure

```plaintext
├── app/                  # Next.js app directory
│   ├── layout.tsx        # Root layout
│   ├── page.tsx          # Dashboard page
│   ├── readers/          # Reader management pages
│   └── email-notification/ # Email notification pages
├── components/           # Reusable components
│   ├── ui/               # UI components (shadcn)
│   ├── reader-table.tsx  # Reader table component
│   └── ...               # Other components
├── services/             # API services
│   ├── notification-service.ts # Notification API
│   └── reader-service.ts # Reader API
├── types/                # TypeScript type definitions
│   ├── notification.ts   # Notification types
│   └── reader.ts         # Reader types
└── public/               # Static assets
```

## Future Enhancements

- Integration with barcode scanners for faster checkout
- Mobile application for readers to manage their accounts
- Advanced reporting and analytics
- Integration with online payment systems for fines
- Book reservation system
- Integration with external book databases


## Best Practices

- **Responsive Design**: The application is fully responsive and works on desktop and mobile devices
- **Accessibility**: UI components follow accessibility best practices
- **Error Handling**: Comprehensive error handling with user-friendly messages
- **Data Validation**: Input validation to ensure data integrity
- **Performance Optimization**: Efficient data loading and state management


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any questions or support, please contact:

- Email: [lehuongg1876@gmail.com]
- Localhost: http://localhost:3000/


---

© 2025 eLibrary. All rights reserved.
