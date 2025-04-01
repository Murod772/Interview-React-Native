# Random People Explorer – Coding Challenge

## Requirements

### 1. Fetch Random Users

#### API Integration:
- Use the Random User Generator API to retrieve at least 10 user profiles.
- Use either `fetch` or a library like `axios` to perform the API request.

#### Data Display:
- For each user, display a thumbnail image, full name, and email address in a scrollable list (using a `FlatList`).

### 2. User Detail Screen

#### Navigation:
- Implement navigation (using React Navigation or similar) so that when a user taps on a list item, the app navigates to a detail screen.

#### Detailed Information:
- On the detail screen, display extended details including:
  - A larger version of the user's picture,
  - Full name,
  - Email,
  - Phone number,
  - Location (street, city, state, country, and postcode).

### 3. (Optional) Favorites Feature

#### Mark as Favorite:
- Allow users to mark/unmark profiles as favorites.

#### Persist Data:
- Use local storage (e.g., AsyncStorage) to persist the favorite status.

#### Favorites Screen:
- Optionally, provide a separate screen that lists all favorited profiles.

### 4. User Authentication Simulation (Optional)

#### Simple Login:
- If time allows, add a login screen with hard-coded credentials to simulate authentication.

## Constraints

- **Time Limit:** 1 hour.  
  Prioritize core functionality (API integration, list display, and navigation). If you run out of time, document additional features you would implement.
- **No Paid APIs:**  
  Do not integrate with paid APIs like Google Maps. Stick with free, open-source tools and libraries.

## Evaluation Criteria

### Functionality:
- Correct API integration and data display.
- Smooth navigation between screens.

### Code Quality:
- Clean, modular code and clear separation of concerns.
- Adequate commenting and code organization.

### UI/UX:
- A neat, responsive, and functional user interface.

### Optional Features:
- Implementation of favorites or a login screen will be considered bonus points if time permits.
