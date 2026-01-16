# ChargeIt

An iOS application UI built entirely with UIKit and Storyboards to demonstrate comprehensive interface design and navigation patterns.

## Overview

This project showcases complete iOS app UI implementation using Xcode's Storyboard visual interface builder. The app demonstrates complex navigation flows, form designs, and interactive elements through 15 interconnected screens.

## Purpose

Learn and demonstrate:
- Building complex multi-screen apps using only Storyboard
- Implementing various UIKit components visually
- Creating navigation hierarchies and flows
- Designing consistent user interfaces
- Managing screen transitions with segues

## UI Components Implemented

### Navigation Elements
- **UINavigationController**: Manages hierarchical screen navigation with back buttons
- **UITabBarController**: Bottom tab navigation with 4 main sections
- **Segues**: Screen-to-screen transitions and data flow
- **Navigation Bar**: Top bar with titles and action buttons

### Input Components
- **UITextField**: Text input fields with different keyboard types
  - Email keyboard for email fields
  - Secure text entry for passwords
  - Number pad for numeric inputs (phone, card numbers)
  - Default keyboard for names and general text
- **Placeholder Text**: Hint text in all input fields
- **Text Field Styling**: Rounded corners, borders, consistent spacing

### Interactive Elements
- **UIButton**: Various button styles throughout the app
  - Primary action buttons (Register, Login, Save, Add)
  - Secondary buttons (Skip, Next)
  - Social login buttons (Facebook, Google)
  - Reset and Apply buttons
- **Button States**: Normal and highlighted states
- **Button Styling**: Rounded corners, custom colors, consistent sizing

### Display Components
- **UILabel**: Text display for headers, descriptions, and information
- **UIImageView**: Icons, logos, and placeholder images
- **Map Interface**: Visual map component for location display
- **Profile Icons**: User and vehicle placeholder graphics

### Layout & Design
- **Auto Layout**: Constraints for responsive design across devices
- **Stack Views**: Organized vertical and horizontal layouts
- **Spacing & Padding**: Consistent margins and gaps
- **Color Scheme**: Soft blue theme with white backgrounds
- **Typography**: System fonts with varying sizes and weights

## Screen Architecture

### Authentication Flow (6 screens)
- Sign Up screen with form fields and social login options
- Sign In screen with email/password and social options
- Password Reset flow with email input
- Forgot password confirmation

### Onboarding Flow (6 screens)
- Add Vehicle screen with brand/model inputs
- Vehicle confirmation with skip option
- Add Card screen with payment details
- Card confirmation with skip option
- My Vehicles display screen
- Vehicle list management

### Main Interface (4+ screens)
- Map view with station markers
- Search interface with text input
- Filter screen with toggle switches
- Station detail views

### Supporting Screens
- Navigation controller wrappers
- Tab bar controller structure
- Keyboard views
- Transition screens

## Navigation Patterns Demonstrated

### Tab Bar Navigation
- 4 main app sections accessible via bottom tabs
- Tab switching without losing state
- Icons and labels for each tab

### Modal Navigation
- Onboarding screens presented modally
- Can be dismissed or skipped
- Sequential flow with Next/Skip buttons

### Push Navigation
- Hierarchical navigation with back buttons
- Detail views pushed onto navigation stack
- Maintains navigation history

### Segue Types Used
- Show (Push): Standard forward navigation
- Modal: Full-screen presentations
- Unwind: Return to previous screens
- Custom: Tailored transitions

## Form Design Patterns

### Multi-Field Forms
- Sign Up: 4 input fields (Name, Email, Password, Phone)
- Sign In: 2 input fields (Email, Password)
- Add Vehicle: 2 input fields (Brand, Model)
- Add Card: 3 input fields (Number, Expiry, CVV)
- Password Reset: 1 input field (Email)

### Form Validation Ready
- Required field structure
- Appropriate keyboard types
- Clear field labels and placeholders
- Primary action buttons

### Optional Fields Flow
- Skip functionality on onboarding screens
- "Add +" buttons for additional entries
- Optional setup paths

## Key Storyboard Techniques

### Controller Relationships
- Embedded navigation controllers
- Tab bar controller with multiple tabs
- Container view controllers
- Child view controllers

### Constraints & Layout
- Leading and trailing constraints
- Top and bottom spacing
- Center alignment (horizontal and vertical)
- Equal width/height relationships
- Aspect ratio constraints

### Visual Design
- Background colors and tints
- Border radius and corner rounding
- Shadow and elevation effects
- Opacity and alpha values
- Image asset management

### Reusability
- Consistent button styling across screens
- Standard text field appearance
- Repeated layout patterns
- Unified color scheme

## Learning Outcomes
This project demonstrates mastery of:
- Storyboard-based UI construction
- Navigation controller architecture
- Tab bar implementation
- Complex segue management
- Auto Layout fundamentals
- Form design principles
- Visual consistency across 40+ screens
- User flow planning and execution
- Interface builder tools and features
