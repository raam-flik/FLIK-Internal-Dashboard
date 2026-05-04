# FLIK Internal Dashboard Documentation

Welcome to the official documentation for the FLIK Internal Dashboard. This comprehensive guide covers all features, modules, and workflows for internal administrators managing the FLIK platform.

## Overview

The FLIK Internal Dashboard is a comprehensive administration platform designed to help internal administrators manage merchants, orders, refunds, payments, and marketing operations. It provides tools for merchant management, financial operations, and platform analytics.

## Platform

- **Web Platform** (Desktop & Responsive)

## Core Modules

### 1. **Home**

Main dashboard overview page displaying key metrics and performance charts.

- Welcome and permissions display
- Chart 1: Sales performance metrics (total vs predicted)
- Chart 2: Growth rate analytics (export and import growth trends)

### 2. **Merchant**

Comprehensive merchant management system.

- [Merchant Lead](/docs/merchant/merchant-lead.md)
  - View and manage merchant leads
  - Track PIC (Person In Charge) information
  - Registration date tracking
  - Lead detail views
- [Merchant List](/docs/merchant/merchant-list.md)
  - View all registered merchants
  - Search merchants by company name
  - Track checkout status
  - Merchant status monitoring
  - Edit merchant details
- [Add Merchant](/docs/merchant/add-merchant.md)
  - Create new merchant accounts
  - Merchant registration form
- [Merchant O2O List](/docs/merchant/merchant-o2o.md)
  - Manage Online-to-Offline merchants
  - Add existing merchants to O2O
  - Add new merchants to O2O program
  - Multi-step onboarding workflow

### 3. **Merchant Shopify**

Shopify integration management for merchants.

- [Merchant Shopify](/docs/merchant/merchant-shopify.md)
  - Manage Shopify-connected merchants
  - Add merchants with Shopify integration
  - Integration status tracking

### 4. **Refund**

Refund processing and management system.

- [Refund List](/docs/refund/refund-list.md)
  - View all refund requests
  - Search refunds by keywords
  - Track refund status (completed, cancelled)
  - Refund details view
  - Add new refunds
- [Add Refund](/docs/refund/add-refund.md)
  - Create new refund requests
  - Multi-step refund entry process
  - Manual refund processing

### 5. **Merchant Cash Advance**

Business financing and cash advance management.

- [Merchant Cash Advance](/docs/financial/merchant-cash-advance.md)
  - View MCA applications and status
  - Assign sales representatives
  - MCA popup management
  - Add new MCA applications
  - Track MCA progress and approvals

### 6. **Balance Adjustment**

Account balance and financial adjustments.

- [Balance Adjustment](/docs/financial/balance-adjustment.md)
  - View balance adjustment history
  - Add balance adjustments
  - Manage account balance changes
  - Track adjustment records

### 7. **Marketing**

Marketing campaign and notification management.

- [Marketing Overview](/docs/marketing/marketing-overview.md)
  - Banner management and creation
  - Push notification system
  - Brand This Week (BTW) product management
  - Home template configuration
  - Marketing notifications
  - Marketing configuration settings

### 8. **Payment Provider**

Payment gateway and provider configuration.

- [Payment Provider](/docs/financial/payment-provider.md)
  - View payment providers
  - Payment provider configuration
  - Payment method management

### 9. **Edit Order**

Order editing and modification system.

- [Edit Order](/docs/orders/edit-order.md)
  - Edit order details
  - Order information updates
  - Order status management

### 10. **Manage Discount**

Discount and promotional group management.

- [Manage Discount](/docs/marketing/manage-discount.md)
  - View discount groups
  - Community group management
  - Add discount groups
  - Discount configuration and creation

## Features by Category

### Merchant Management

- View merchant leads and track registration
- Manage active merchant accounts
- Add new merchants to platform
- Manage O2O merchants
- Shopify integration management
- Merchant detail editing
- Merchant status tracking

### Financial Operations

- Process refunds and track refund status
- Manage merchant cash advance applications
- Adjust account balances
- Configure payment providers
- Track financial transactions

### Marketing Operations

- Create and manage banners
- Send push notifications
- Manage product promotions (Brand This Week)
- Configure home template
- Create discount groups and promotions
- Marketing campaign management

### Order Management

- Edit order details
- Order information updates

## Documentation Structure

```
/docs
├── merchant/
│   ├── merchant-lead.md              # Merchant Lead Management
│   ├── merchant-list.md              # Merchant List Overview
│   ├── add-merchant.md               # Add New Merchant
│   ├── merchant-o2o.md               # Merchant O2O List
│   └── merchant-shopify.md           # Shopify Integration
├── refund/
│   ├── refund-list.md                # Refund List Management
│   └── add-refund.md                 # Add New Refund
├── financial/
│   ├── merchant-cash-advance.md      # Merchant Cash Advance
│   ├── balance-adjustment.md         # Balance Adjustment
│   └── payment-provider.md           # Payment Provider Configuration
├── marketing/
│   ├── marketing-overview.md         # Marketing Overview
│   ├── manage-discount.md            # Discount Management
│   └── marketing-notifications.md    # Marketing Notifications
└── orders/
    └── edit-order.md                 # Edit Order
```

## Screenshots

All UI screenshots are organized by module in the `/assets/screenshots/` directory for reference during implementation or usage.

## Navigation Structure

The internal dashboard features a left sidebar navigation menu with the following main sections:

- **Home** - Main dashboard with analytics
- **Merchant** (expandable)
  - Merchant Lead
  - Merchant List
  - Add Merchant
  - Merchant O2O List
  - Add Merchant O2O (quick add)
- **Merchant Shopify** - Shopify integration management
- **Refund** (expandable)
  - Refund List
  - Add Refund
- **Merchant Cash Advance** - MCA management
- **Balance Adjustment** - Balance management
- **Marketing** - Marketing tools
- **Payment Provider** - Payment configuration
- **Edit Order** - Order editing
- **Manage Discount** - Discount management

## Version

**Current Version**: 1.0.0

## Last Updated

May 4, 2026

---

For more information, please visit our official website or contact support.
