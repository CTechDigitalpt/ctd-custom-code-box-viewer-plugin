# ✨ CTD Custom Code Box ✨

> A powerful and customizable code box plugin for WordPress.

## ⚙️ Installation

1. **Download** the plugin from the [official website](https://www.ctechdigital.com/wp-plugin/sticky-code-box-wp-plugin/) or GitHub.
2. **Upload** it to your WordPress site via the Plugins menu.
3. **Activate** the plugin in the Plugins dashboard.
4. **Configure** the settings under `Settings > Custom Code Box`.

## 🛠️ Features

### 🆓 Standard (Free) Version🎨
- ✅ Customizable font styles
- ✅ Adjustable code box colors and borders
- ✅ Copy button with basic positioning
- ✅ Live preview of settings
- ✅ Responsive design
- ✅ Shortcode `[ccb_code]Your Code Here[/ccb_code]`
- ✅ Most code formats accepted
- ✅ Mobile-friendly interface

### 🚀 Pro Version🎯
Upgrade to **Pro** for additional features:
- 🌟 Syntax Highlighting
- 🌟 Multiple Code Box Styles
- 🌟 Advanced Copy Button Controls
- 🌟 Copy Button Click Tracking
- 🌟 Advanced Color Picker
- 🌟 Code Line Numbering
- 🌟 Dynamic Copy Button with Scroll
- 🌟 Export & Import Settings
- 🌟 Priority Support

Get it [here](https://www.ctechdigital.com/wp-plugin/sticky-code-box-wp-plugin/pro/).

## 🛡️ Security Features🔐

The **CTD Custom Code Box** plugin includes built-in security measures to protect your site:

- **Shortcode Restriction:** Only administrators can execute shortcodes to prevent unauthorized usage.
- **Nonce Verification:** Protects against CSRF attacks by verifying security tokens for all critical actions.
- **Admin Request Validation:** Ensures that only users with proper permissions can access settings and perform administrative actions.
- **Secure AJAX Requests:** Uses `check_ajax_referer()` to validate AJAX operations.
- **Sanitized Inputs:** All user inputs are sanitized before being processed to prevent malicious data injection.
- **Escaped Output:** Prevents XSS attacks by escaping all outputted data.
- **Custom Capability Checks:** Restricts sensitive operations to users with `manage_options` capability.
- **Strict Form Handling:** Verifies POST requests, ensuring they come from trusted sources and contain valid nonces.
- **No External Dependencies:** The plugin exclusively uses internal resources, eliminating reliance on third-party scripts or services, making it even safer.

## 📚 Usage🌎

1. Navigate to **Code Box** Menu in your WordPress admin.
2. Customize your code box appearance and button placement.
3. Embed code snippets in posts or pages using:

### Example (Free Version)
```html
[ccb_code]
function greet() {
    console.log("Hello, World!");
}
greet();
[/ccb_code]
```

### Example (Pro Version)
```html
[ccb_code language="javascript" line_numbers="true"]
function greet() {
    console.log("Hello, World!");
}
greet();
[/ccb_code]
```

### Explanation:
- `language="javascript"` → Enables syntax highlighting for JavaScript.
- `line_numbers="true"` → Enables line numbering for better readability.

## 🐝 Support🔗

Need help? [Open an issue](https://github.com/CTechDigitalpt/wp-code-frame-viewer-plugin/issues) or visit our [support page](https://www.ctechdigital.com/wp-plugin/sticky-code-box-wp-plugin/support/).
