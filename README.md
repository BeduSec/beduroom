# BeduRoom User Guide

Welcome to BeduRoom. This platform provides a secure, non-traceable environment for team communication.

## Protocol Overview

BeduRoom operates on a zero-persistence and zero-tracking architecture. Access is granted through unique Beducode identifiers rather than personal emails or phone numbers.

## Getting Started

### Initializing your Identity

1. Navigate to the registration tab.
2. Enter a Nickname. This name will be visible to your teammates.
3. Choose a strong password.
4. Click Generate Identity.
5. Save the generated Beducode immediately. This is your permanent login ID and cannot be recovered if lost.

### Authenticating

1. Enter your Beducode (format: BEDU-XXXX-XXXX).
2. Enter your password.
3. Click Connect to Node to enter the general communications stream.

## Communication Interface

### Messaging

* Type your message in the payload field at the bottom.
* Press enter or click the send icon to broadcast to the team.
* Your messages appear as "YOU" to you, and your Nickname to others.

### Security Features

* URL Detection: Any link starting with http or https is automatically converted into a clickable element.
* XSS Shield: The platform automatically filters and escapes all message content to prevent unauthorized code execution.
* Real-time Synchronization: Messages appear instantly without requiring a page refresh.

## Security Recommendations

### Account Safety

* Do not share your Beducode with anyone outside the designated team.
* Use a unique password not associated with other online accounts.
* If you suspect your identity is compromised, generate a new Beducode immediately.

### Session Management

* Click the Disconnect icon (top right) to terminate your session.
* Closing the browser tab does not automatically sign you out; manual disconnection is the most secure method.
* No local message history is stored on your device to ensure maximum privacy after the session ends.

## Troubleshooting

* Connection Issues: If the green indicator in the header is not active, verify your internet connection.
* Authentication Failures: Ensure your Beducode includes the dashes and is entered exactly as generated.