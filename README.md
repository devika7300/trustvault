# TrustVault - Online Banking Platform

**TrustVault** is a cutting-edge online banking platform designed to help users manage their finances by connecting multiple bank accounts. The platform provides real-time transaction updates, seamless money transfers between users, and comprehensive tools to track and analyze spending habits.

## Overview

TrustVault offers users a secure and intuitive interface to manage their financial life. Whether checking account balances, reviewing recent transactions, or transferring money to other users, TrustVault ensures an efficient and streamlined experience.

## Key Features

- **Secure Authentication**: Server-side rendering (SSR) ensures highly secure authentication with robust validation and authorization, keeping user data safe.
  
- **Bank Account Integration**: Seamlessly integrates with Plaid to allow users to link multiple bank accounts for real-time transaction monitoring.

- **Unified Dashboard**: The homepage offers a consolidated view of all connected bank accounts, showing a summary of total balances, recent transactions, and categorized spending trends.

- **Bank Management**: Users can view and manage all connected banks from the "My Banks" section, including account details and balances.

- **Transaction History**: Users can browse their transaction history with built-in pagination and filtering tools, providing full visibility into financial activities across all accounts.

- **Real-Time Synchronization**: Changes, such as linking new bank accounts, are immediately reflected across all relevant pages to keep data up-to-date in real-time.

- **Fund Transfers**: Built-in integration with Dwolla allows users to transfer funds between accounts, requiring only recipient bank details and proper validation.

- **Mobile-Friendly Design**: TrustVault is fully responsive and ensures a seamless experience across all devices, including desktops, tablets, and smartphones.

## Tech Stack

- **Next.js**: Server-side rendering and client-side functionality for a seamless user experience.
- **TypeScript**: Provides type safety for predictable and maintainable code.
- **React Hook Form**: Efficient and scalable form management for handling inputs and validation.
- **Zod**: Schema validation for secure data handling.
- **TailwindCSS**: Modern utility-first CSS framework for responsive and adaptive UI design.
- **Chart.js**: Interactive charts and data visualizations to give users insights into their financial activities.
- **ShadCN**: A component library that enhances the user interface with ready-to-use components.
- **Dwolla**: To facilitate secure fund transfers between accounts.
- **AppWrite**: Authentication, database management, file storage.
