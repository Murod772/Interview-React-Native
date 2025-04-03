# Punk Beer Explorer – Coding Challenge

## Overview

Build a React Native application that fetches beer data from the [Punk API](https://punkapi.com/documentation/v2) and displays it in a list. Tapping on a beer should navigate to a detailed view showing more information about the selected beer.

---

## Requirements

### 1. Fetch Beers

#### API Integration:
- Use the Punk API endpoint (`https://api.punkapi.com/v2/beers`) to retrieve at least 10 beer profiles.
- Use either `fetch` or a library like `axios` to perform the API request.

#### Data Display:
- For each beer, display a thumbnail image (if available), the beer’s name, and a short tagline or description in a scrollable list (using a `FlatList`).

### 2. Beer Detail Screen

#### Navigation:
- Implement navigation (using React Navigation or a similar library) so that when a user taps on a list item, the app navigates to a detail screen.

#### Detailed Information:
- On the detail screen, display extended details including:
  - A larger version of the beer’s image,
  - Beer name,
  - Tagline,
  - Alcohol by Volume (ABV),
  - Description,
  - Additional details such as food pairings if available.

### 3. (Optional) Favorites Feature

#### Mark as Favorite:
- Allow users to mark/unmark beers as favorites.

#### Persist Data:
- Use local storage (e.g., AsyncStorage) to persist the favorite status.

#### Favorites Screen:
- Optionally, provide a separate screen that lists all favorited beers.

### 4. User Authentication Simulation (Optional)

#### Simple Login:
- If time allows, add a login screen with hard-coded credentials to simulate authentication.

---

## Constraints

- **Time Limit:** 1 hour.  
  Prioritize core functionality (API integration, list display, and navigation). If you run out of time, document additional features you would implement.
- **No Paid APIs:**  
  Do not integrate with paid APIs. Stick with free, open-source tools and libraries.

---

## Evaluation Criteria

### Functionality:
- Correct API integration and data display.
- Smooth navigation between screens.

### Code Quality:
- Clean, modular code with a clear separation of concerns.
- Adequate commenting and code organization.

### UI/UX:
- A neat, responsive, and functional user interface.

### Optional Features:
- Implementation of favorites or a login screen will be considered bonus points if time permits.
