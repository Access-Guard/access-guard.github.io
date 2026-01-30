# One Time Email Access Guard

**Contributors:** marcogargano  
**Tags:** authentication, security, access control, passwordless, otp  
**Requires at least:** 5.0  
**Tested up to:** 6.9  
**Stable tag:** 1.1.0  
**Requires PHP:** 7.2  
**License:** GPLv2 or later  
**License URI:** https://www.gnu.org/licenses/gpl-2.0.html

Protect pages and posts with email-delivered verification codes. Secure, passwordless access control with user management and customization.

---

## 📝 Description

One Time Email Access Guard **protects your WordPress pages and posts** using email-delivered verification codes. Each authorized user receives a time-limited code, allowing secure access without traditional passwords.

### Key Features

- **Email-Based Verification**: Send secure verification codes via email
- **User Management**: Create and manage authorized users with contact details
- **Content Protection**: Enable protection per page/post with user assignment
- **Customizable Access**: Set custom access duration and expiration dates
- **Modal Customization**: Customize colors, opacity, and appearance
- **Protected Content Tracking**: Monitor all protected pages and authorized users
- **Secure Cookies**: Maintain login sessions with secure access tokens

---

## 😌 Easy to use

1. **Create user** under Access Guard
2. **Activate user** in the page/post page

Video tutorial:  
https://www.youtube.com/watch?v=XE4d496uPUc

---

## Features

### 🔐 Advanced Security

- Passwordless access via email verification codes
- Email based One Time Password (OTP) access
- User verification with name and phone number
- Custom verification codes expiration
- Secure access tokens via cookies
- International phone support (195+ countries)

### 🎨 Fully Customizable

- Custom modal colors (overlay, background, text)
- Adjustable opacity and shadow
- Custom titles and messages
- Professional HTML email templates

### 👥 User Management

- Create users with name, email, and phone
- Enable/disable users instantly with toggle switch
- Custom access duration (15 min to unlimited)
- Optional expiration date and time
- User status indicator with visual feedback
- Bulk operations (activate/deactivate all users)
- Bulk expiry date setting
- CSV import/export for user data

### 🔒 Content Protection

- Enable protection per page/post
- Assign authorized users with multi-select
- Protection status column in admin
- Real-time user status display (active/expired)
- Quick edit access from protected pages list

### 📊 Monitoring

- View all protected pages/posts
- See authorized users
- Direct quick-edit access

### ⚙️ Flexible Configuration

- Optional first name and last name fields
- Custom blocked-content messages
- Modal color customization (overlay, background, text)
- Adjustable overlay opacity
- Toggle modal shadow effects
- Reset all settings to default

---

## Installation

1. Search **"One Time Email Access Guard"** from the Plugins page and install it.
   Otherwise manually upload the `one-time-email-access-guard` folder to `/wp-content/plugins/`
2. Activate the plugin from the **Plugins** menu
3. Go to **Access Guard** in your admin menu
4. Create users with their contact details
5. Enable protection on any page/post and assign authorized users

---

## Frequently Asked Questions

### Does the plugin require SMTP?

No, but SMTP is recommended for reliable email delivery.  
If you decide not to use it, remember to check your spam folder.

### Can I protect only specific pages?

Yes, protection is applied per page/post from the sidebar meta box.  
You can individually select each user from the list of entered users.

### How long does the verification code last?

Default verification codes expire after 1 hour.  
You can select the duration, from 15 minutes up to 2 days, or disable expiration entirely.

### Can I use the WordPress user list?

No, the plugin's user list is dedicated.  
You'll need to enter the users in the appropriate section, providing the desired details.

---

## Changelog

### 1.1.0

- Plugin rebranded to "One Time Email Access Guard" for WordPress.org compliance
- Updated plugin slug to `one-time-email-access-guard`
- Updated text domain and all translation files
- Author changed to Marco Gargano
- Added bulk user operations (activate/deactivate all)
- Added bulk expiry date setting
- Added CSV import/export functionality
- Added international phone support (195+ countries)
- Improved user interface with toggle switches
- Enhanced security with proper nonce validation
- Code quality improvements and WordPress standards compliance

### 1.0.0

- Initial release

---

## Upgrade Notice

### 1.1.0

Plugin renamed to comply with WordPress.org guidelines. All functionality preserved.
