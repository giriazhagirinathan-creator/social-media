# Lab 5: MongoDB Social Media Database

A MongoDB project demonstrating document models with embedded subdocuments and atomic operations.

## Features
- **User Profiles**: Insert and manage user records in the `users` collection.
- **Embedded Comments**: Store post comments directly within post documents in `posts`.
- **Atomic Operations**:
  - `$push`: Append new comments into an array without modifying the rest of the post.
  - `$inc`: Atomically increment like counts.

## Usage
Run with MongoDB Shell (`mongosh`):
```bash
mongosh social_media.js
```
Or execute [social_media.mongodb.js](file:///c:/Users/User/OneDrive/Desktop/lab5/social_media.mongodb.js) inside VS Code / MongoDB Playground.
