# nullifai
ZK-KYC for hackathon-grade apps without collecting identity data.

## Usage: Anonymous Credential Verification with QR Codes

Enable anonymous credential verification in your app using QR codes. This allows users to prove eligibility or credentials without revealing their identity.

### How it works
1. The app generates a QR code containing a one-time challenge or credential request.
2. The user scans the QR code with a compatible wallet or ZK proof app.
3. The user signs or proves the credential anonymously on their device.
4. The app verifies the proof server-side or client-side, granting access or benefits without collecting identity data.

### Example Flow
- User visits your app's verification page.
- A QR code is displayed for the credential challenge.
- User scans the QR code with their ZK wallet/app.
- The wallet/app generates a zero-knowledge proof and returns it to your app.
- Your app verifies the proof and grants access if valid.

> **Note:** Implementation requires a compatible ZK proof system and wallet/app that supports QR-based credential verification. See documentation for integration details.
