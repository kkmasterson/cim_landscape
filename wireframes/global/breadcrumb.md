# Breadcrumb Trail Wireframe

## Desktop View
┌──────────────────────────────────────────────────────────────────────────────┐
│ Home > Invoice Processing > Queue > Invoice #12345                           │
└──────────────────────────────────────────────────────────────────────────────┘

Example States:
┌──────────────────────────────────────────────────────────────────────────────┐
│ Home > Dashboard > Analytics > Monthly Reports                               │
└──────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────────────────────┐
│ Home > Documentation > API Docs > Authentication                             │
└──────────────────────────────────────────────────────────────────────────────┘

## Mobile View
┌─────────────────────────────┐
│ ... > Queue > Invoice #12345│
└─────────────────────────────┘

## Key Features:
1. Clear hierarchy indication with ">" separators
2. Each segment is clickable for navigation
3. Current page shown but not clickable
4. Consistent with main navigation styling
5. Mobile view truncates with "..." for space
6. Hover states for clickable segments
7. Optional icons for key sections (Home: 🏠)
8. Responsive text truncation on narrow screens

## Interaction States:
- Regular: Home > Invoice Processing > Queue > Invoice #12345
- Hover:   Home > Invoice Processing > [Queue] > Invoice #12345
- Active:  Home > [Invoice Processing] > Queue > Invoice #12345 