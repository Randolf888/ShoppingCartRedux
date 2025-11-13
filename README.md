# ShoppingCartRedux

A modern React Native shopping cart application built with Redux Toolkit for efficient state management. This app demonstrates a complete e-commerce flow, including product browsing, cart management, and checkout simulation.

## Features

- **Product Browsing**: Fetch and display products from a fake API (FakeStoreAPI)
- **Cart Management**: Add, remove, and update item quantities in the shopping cart
- **Real-time Updates**: Live cart count and total price calculations using Redux selectors
- **Responsive UI**: Clean, intuitive interface with proper loading and error states
- **Cross-Platform**: Works on both iOS and Android devices
- **Navigation**: Smooth navigation between product list and cart screens using React Navigation

## Installation

### Prerequisites
- Node.js (>= 20)
- npm or yarn
- React Native development environment
- For iOS: Xcode (macOS only)
- For Android: Android Studio

### Steps

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd ShoppingCartRedux
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Install iOS dependencies** (iOS only)
   ```bash
   cd ios
   pod install
   cd ..
   ```

4. **Start the Metro bundler**
   ```bash
   npm start
   ```

5. **Run on device/emulator**
   - **iOS**: `npm run ios`
   - **Android**: `npm run android`

## Usage

1. **Browse Products**: The app opens to a list of products fetched from the API
2. **Add to Cart**: Tap "Add to Cart" on any product to add it to your shopping cart
3. **View Cart**: Tap the cart button in the header to navigate to the cart screen
4. **Manage Cart**:
   - Increase/decrease quantities using +/- buttons
   - Remove items individually or clear the entire cart
   - View real-time total price
5. **Checkout**: Tap "Proceed to Checkout" to simulate a purchase (clears cart on success)
