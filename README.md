# Brewery Explorer – Coding Challenge

## Overview

Build a React Native application that fetches brewery data from the Open Brewery DB API and displays it in a list. Tapping on a brewery should navigate to a detailed view that shows more information about the selected brewery.

---

## Requirements

### 1. Fetch Breweries

#### API Integration:
- Use the Open Brewery DB API endpoint (`https://api.openbrewerydb.org/v1/breweries`) to retrieve a list of breweries.
- Use either `fetch` or a library like `axios` to perform the API request.

#### Data Display:
- For each brewery, display key details such as:
  - **Name**
  - **Brewery Type**
  - **City/State**
- Use a scrollable list (e.g., `FlatList`) to render the breweries.

### 2. Brewery Detail Screen

#### Navigation:
- Implement navigation (using React Navigation or a similar library) so that when a user taps on a list item, the app navigates to a detail screen.

#### Detailed Information:
- On the detail screen, display extended details including:
  - Brewery **Name**
  - **Brewery Type**
  - Full **Address** (street, city, state, postal code)
  - **Phone Number** (if available)
  - **Website URL** (if available)

### 3. (Optional) Favorites Feature

#### Mark as Favorite:
- Allow users to mark/unmark breweries as favorites.

#### Persist Data:
- Use local storage (e.g., AsyncStorage) to persist the favorite status.

#### Favorites Screen:
- Optionally, provide a separate screen that lists all favorited breweries.

### 4. User Authentication Simulation (Optional)

#### Simple Login:
- If time allows, add a login screen with hard-coded credentials to simulate authentication.

---

## Constraints

- **Time Limit:** 1 hour.  
  Prioritize core functionality (API integration, list display, and navigation). If you run out of time, document additional features you would implement.
- **No Paid APIs:**  
  Use only free, open-source tools and libraries.

---

## Evaluation Criteria

### Functionality:
- Correct integration with the Open Brewery DB API and data display.
- Smooth navigation between screens.

### Code Quality:
- Clean, modular code with a clear separation of concerns.
- Adequate commenting and code organization.

### UI/UX:
- A neat, responsive, and user-friendly interface.

### Optional Features:
- Implementation of favorites or a login screen will be considered bonus points if time permits.
