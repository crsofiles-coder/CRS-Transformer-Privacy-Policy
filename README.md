# Privacy Policy for CRS Transformer

**Last Updated:** March 30, 2026

**CRS Transformer** ("we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains how our mobile and desktop application **CRS Transformer** (the "Application") handles data when you use our services.

By using the Application, you agree to the practices described in this Privacy Policy.

---

### 1. Information Collection and Use

#### A. Personal Information
**CRS Transformer does not collect, store, or transmit any personally identifiable information (PII).** You are not required to create an account, register, or provide personal details (such as your name, email address, phone number, or physical address) to use the Application.

#### B. Spatial & Coordinate Data
All coordinate entries, imported files (*CSV, TXT, TSV*), transformed dataset records, and exported files (*CSV, KML, ESRI Shapefile*) are processed **100% locally on your device**. Your spatial data is never uploaded to, stored on, or processed by external cloud servers or third parties.

#### C. Location Information
The Application may request access to your device's geolocation services (*ACCESS_FINE_LOCATION* / *ACCESS_COARSE_LOCATION*). This permission is used **solely to center and display your current location on the interactive Google Maps canvas** when requested by you. Your location data:
* Is processed in real-time strictly on your device.
* Is never logged, recorded, tracked, or transmitted to us or any third party.
* Is completely optional; you can deny location access and still use all coordinate transformation and mapping features.

---

### 2. Third-Party Services

The Application utilizes minimal third-party SDKs and public APIs to provide mapping and projection features:

1. **Google Maps SDK**
   * Used to render interactive base maps, satellite imagery, and marker overlays.
   * Google Maps may collect anonymous diagnostic and usage telemetry per Google's standard policies.
   * For more information, please review the [Google Privacy Policy](https://policies.google.com/privacy).

2. **EPSG.io API (Optional Online Fallback)**
   * Used as an optional fallback when looking up obscure EPSG projection definitions not stored in the offline local database (`crs.db`).
   * Only the numeric EPSG code is transmitted to retrieve projection definitions. No user coordinates or personal data are included.

---

### 3. File Storage and Permissions

The Application requests standard device file access permissions strictly for the following user-initiated operations:
* Reading `.csv`, `.txt`, and `.tsv` files selected by you for coordinate batch processing.
* Saving generated export files (`.csv`, `.kml`, and `.zip` Shapefiles) to your designated storage directory.

We do not scan, read, or access any files or data outside of the explicit files you select.

---

### 4. Children’s Privacy

Our Application does not address or target anyone under the age of 13. We do not knowingly collect personal information from children.

---

### 5. Data Security

Because all coordinate math, file imports, local database queries, and exports occur directly on your local device, your data remains securely under your control at all times.

---

### 6. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. Any changes will be reflected by updating the "Last Updated" date at the top of this policy. You are advised to review this Privacy Policy periodically for any changes.

---

### 7. Contact Us

If you have any questions, concerns, or suggestions regarding this Privacy Policy, please contact us at:

* **App Name:** CRS Transformer
* **Publisher:** Moonlighter App Studio
* **Support Email:** `support@moonlighter.app`
