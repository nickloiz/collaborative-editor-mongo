# Collaborative Editor MongoDB Implementation

This repository contains the MongoDB implementation for an online collaborative document editor.

## Files Included
- `users.json`: Sample data for Users collection.
- `documents.json`: Sample data for Documents collection.
- `edits.json`: Sample data for Edits collection.
- `queries.js`: JavaScript file containing example queries.

## Setup Instructions
1. Make sure MongoDB is running.
2. Import the data using:
   ```bash
   mongoimport --db collaborative_editor --collection Users --file users.json --jsonArray
   mongoimport --db collaborative_editor --collection Documents --file documents.json --jsonArray
   mongoimport --db collaborative_editor --collection Edits --file edits.json --jsonArray
