# ✨ CTD Custom Code Box Viewer Plugin ✨

> A powerful and customizable code box plugin for WordPress.

## ⚙️ Installation

1. **Download** the plugin from the [official website](https://www.ctechdigital.com/wp-plugins/free-wp-code-box-display-plugin/) or GitHub.
2. **Upload** it to your WordPress site via the Plugins menu.
3. **Activate** the plugin in the Plugins dashboard.
4. **Configure** the settings under `Settings > Custom Code Box`.

## Features

### Standard (Free) Version
- ✅ Customizable font styles
- ✅ Adjustable code box colors and borders
- ✅ Copy button with basic positioning
- ✅ Live preview of settings
- ✅ Responsive design
- ✅ Shortcode `[ccb_code]Your Code Here[/ccb_code]`
- ✅ Most code formats accepted
- ✅ Mobile-friendly interface

### * Pro Version * Still in Development (Early Donator's will receive Free Pro Version on Launch)
Upgrade to **Pro** for additional features:
- 🌟 Syntax Highlighting according to Language
- 🌟 Multiple Code Box Styles Configurations
- 🌟 More Advanced Copy Button Controls
- 🌟 Copy Button Click Tracking
- 🌟 Advanced Color Picker
- 🌟 Code Line Numbering
- 🌟 Dynamic Copy Button with Scroll
- 🌟 Priority Support

Get it [here](https://www.ctechdigital.com/wp-plugins/free-wp-code-box-display-plugin).

## 🛡 Security Features

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

##  Usage 

1. Navigate to **Codey Box** Menu in your WordPress admin.
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

##  Support 

Need help? [Open an issue](https://github.com/CTechDigitalpt/ctd-custom-code-box-viewer-plugin/issues) or visit our [support page](https://www.ctechdigital.com/wp-plugins/free-wp-code-box-display-plugin/support/).

## Plugin Showcase ▶

Watch the plugin in action on YouTube:

[![CTD Custom Code Box Plugin Showcase](https://img.youtube.com/@CTech_Digital/maxresdefault.jpg)](https://www.youtube.com/watch?v=CTech_Digital)

Click the image above or [here](https://www.youtube.com/watch?v=CTech_Digital) to watch the video!

## ## 💖 Donate ## ##
If you appreciate our work and wish us to continue with development of the Pro Version and send us donations you will receive receive Free Access when it is published, please consider supporting us:

- **[Buy Me a Coffee](https://ko-fi.com/ctechdigitalcom)**
- **[Patreon](https://www.patreon.com/ctechdigital)**
- **[PayPal](https://www.paypal.com/donate/?hosted_button_id=8HUVZWJUYLY82)**


Your support helps us keep improving and adding new features to this plugin!
