# Privacy Policy for JC Tickets

*Last Updated: October 2026*

This Privacy Policy explains how **JC Tickets** ("we", "us", or "the Bot") handles user data when used within Discord servers (such as the any.run Community Discord server).

---

## 1. Information We Collect

JC Tickets is an administrative support ticket management bot. It only collects and processes information necessary to create and manage support tickets:

- **Discord User Information**: User ID, username, and avatar URL to identify ticket creators and participants.
- **Application Details**: Information voluntarily submitted by users via the ticket modal (such as email address, student/researcher affiliation, monthly analysis volume, and file/link sources) to evaluate requests for free personal any.run accounts.
- **Support Messages**: Message content, timestamps, and attachments sent inside private ticket channels between users and moderators, used strictly for transcript generation upon ticket closure.
- **Server Configuration**: Guild IDs, designated log channel IDs, support role IDs, ticket category IDs, and sequential ticket counters.

---

## 2. How Information is Used

The information collected is used exclusively for:
- Creating private support channels for account application review.
- Facilitating direct communication between applicants and any.run server moderators.
- Generating self-contained HTML transcripts upon ticket resolution for compliance, auditing, and user reference.

---

## 3. Data Storage & Retention

- **Off-Platform Storage**: **None**. Message contents are not transmitted to or stored on external web servers, cloud buckets, or third-party databases.
- **On-Server Database**: The Bot maintains a minimal local SQLite database containing only active ticket IDs, creator IDs, and server configuration settings. When a ticket is closed and deleted, the ticket record is removed from the active database.
- **Transcripts**: Closed ticket transcripts are rendered in memory and uploaded directly as file attachments (`.html`) to the server's designated log channel and (if enabled) the ticket creator's Direct Messages. Storage of these files is managed directly within Discord's infrastructure in accordance with Discord's data retention policies.

---

## 4. Machine Learning & AI Training

**No message content, user data, or transcripts are ever used to train machine learning models or artificial intelligence algorithms.**

---

## 5. Third-Party Sharing

We do not sell, rent, trade, or share any user data with external third parties or advertisers.

---

## 6. User Rights & Data Deletion

Users may request the deletion of their open tickets or application data at any time by contacting a server moderator or closing their ticket via the Discord interface.

---

## 7. Contact Us

If you have questions regarding this Privacy Policy or your data usage, please reach out to the moderation team in the any.run Discord server.
