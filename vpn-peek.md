# Privacy Policy

**VPN Peek** is designed with privacy in mind. The app does not collect, store, or transmit any personal data to us.

## Data Collection

- No personal information collected by the app
- No usage analytics or tracking
- No accounts or registration required

## External Services

VPN Peek queries third-party IP geolocation services to display your current public IP address and location:

- **ip-api.com** (primary)
- **ipinfo.io** (fallback)
- **api6.ipify.org** (IPv6 detection)

These requests are made directly from your device to the respective services. VPN Peek does not proxy, store, or log any of this data. Please refer to each service's privacy policy for their data handling practices.

## Local Data

- VPN status is detected locally using macOS network interfaces
- DNS servers are read from your Mac's system configuration
- Preferences (icon style, display format, refresh interval, notification settings) are stored locally using UserDefaults
- No data is sent to us or any server we operate

## Notifications

VPN Peek can send local notifications when your VPN disconnects or a leak is detected. These notifications are processed entirely on your device and are not transmitted anywhere.

## Network Permission

VPN Peek requires network access (`com.apple.security.network.client`) to:
- Query your public IP address from geolocation services
- Check for IPv6 connectivity

This is necessary for the app's core functionality of verifying your VPN protection status.

## Contact

Questions? Contact [me](mailto:contact@anhphong.dev).

*Last updated: January 2026*
