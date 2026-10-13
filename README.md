# Event Organising APP
An application for creating, managing and sharing events. Event planners can create events, invite guests by email, and keep track of everything from one dashboard. Guests can log in to see the events they have been invited to.

Features
- Create, edit and remove events. Planners have full control over the events they create.
- Event templates. Each event is built from a template that captures the name, type, location (city/town and postcode), date and time.
- Automatic invitations. Enter a guest's email in the invitees field when creating an event, and it appears in their Invited Events page.
- RSVP and guest list tracking. Invitations are stored in the database and linked to each user.
- Invited Events page. Guests see the events they have been invited to, along with the key details.
- View-only access for attendees. Guests can see event details but cannot edit or remove events.
- Multiple events at once. Users can create and take part in as many events as they like. The dashboard scrolls to fit them all.
- Secure data storage and access controls. User and guest information is stored securely, and access to guest data is controlled.

Packages needed:
  firebase_core: ^2.26.0 or above
  firebase_auth: ^4.17.7 or above
  cloud_firestore: ^4.15.7 or above
  firebase_messaging: ^14.7.18 or above
  firebase_database: ^10.0.14 or above
  cupertino_icons: ^1.0.2 or above




Testing

Manual testing was carried out for the main features:
- Creating events: create an event using the template and check it appears on the dashboard.
- Invitations: create an event with another valid user's email, log into that account and check the event appears under Invited Events.
- Multiple events: create several events and invite several users to different events.
- View-only access: log in as an attendee, open the dashboard and check event details are visible but cannot be edited.

Data Protection and Security

User and guest information is treated as confidential. The application stores user data securely and uses access controls so that users can only interact with guest data they are permitted to see. These measures were designed with GDPR in mind.

Known Limitations
- Guest list tools such as adding, removing and tracking guests are not fully developed.
- Testing for guest list handling, data capture and access controls is incomplete.

