# Refund List

## Overview

The Refund List module provides administrators with a comprehensive view of all refund requests in the system. This module allows for refund management, status tracking, and processing of customer refund requests.

![Refund List Page](../../assets/screenshots/Refund%20List/Refund%20List%20Page.png)

## Features

### View Refund Requests

- **Refund List Display**: Shows all refund requests in a searchable table
- **Search Functionality**: Search refunds by keywords to quickly find specific requests
- **Add Refund Button**: Quick access to create new refund requests
- **Refund Information Displayed**:
  - Order ID - Reference to the original order
  - Merchant Name - The merchant processing the refund
  - Shopper Name - Customer who requested the refund
  - Order Date - Date of the original order
  - Amount - Refund amount (in Rupiah)
  - Order Status - Status of the original order (e.g., "completed")
  - Status - Refund status (e.g., "canceled")

### Refund Status Tracking

- **Status Indicators**: Color-coded status badges for quick identification
  - "completed" - Order was completed
  - "canceled" (red) - Refund was canceled or order was canceled
- **Status Sorting**: Sort refunds by status to organize pending, completed, or canceled refunds

### Refund Management

- **View Details**: Access refund detail view with "..." menu option
- **Sort Capabilities**: Sort refunds by any column:
  - Order ID
  - Merchant Name
  - Shopper Name
  - Order Date
  - Amount
  - Order Status
  - Status

## Navigation

- **Location**: Main Menu > Refund > Refund List
- **Breadcrumb**: Refund / Add (or Refund / Refund List)
- **Sub-items in Menu**:
  - Refund List (current)
  - Add Refund

## Page Layout

- **Header**: "Refund List" title with breadcrumb navigation
- **Action Section**: 
  - "Add Refund" button (dark blue)
  - Search field: "Search : Type Keywords"
- **Table Columns**:
  - Order ID (sortable, clickable)
  - Merchant Name (sortable)
  - Shopper Name (sortable)
  - Order Date (sortable)
  - Amount (sortable)
  - Order Status (sortable)
  - Status (sortable)
  - Action (menu with options)

## Related Modules

- [Add Refund](/docs/refund/add-refund.md) - Create new refund requests
