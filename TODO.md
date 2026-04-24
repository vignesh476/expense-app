# New Features Implementation

## 1. Edit Expense
- [x] Backend: Add `update_expense` view in `backend/trips/views.py`
- [x] Backend: Add PUT route in `backend/trips/urls.py`
- [x] Frontend: Add inline edit mode to expense rows in Trips.jsx

## 2. Dark Mode Toggle
- [x] Frontend: Add theme state + toggle button in App.jsx header
- [x] Frontend: Persist theme preference in localStorage
- [x] Frontend: Add dark mode CSS variables to `index.css`

## 3. Budget Alerts
- [x] Backend: Add `budget` field to Trip model + create migration
- [x] Backend: Update Trip serializers to include budget
- [x] Backend: Update TripListCreateView to accept budget
- [x] Frontend: Add budget input to trip creation form
- [x] Frontend: Show budget progress bar in trip detail
- [x] Frontend: Warn toast when expenses approach/exceed budget

## 4. Bills Remainder
- [x] Backend: Calculate remainder when total doesn't divide evenly among participants
- [x] Backend: Suggest person who paid the most to absorb the remainder
- [x] Frontend: Display remainder amount in settlement summary card
- [x] Frontend: Show notice with suggestion for who should absorb the remainder
- [x] Frontend: Add CSS for remainder card and notice (light + dark mode)

