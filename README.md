# ID Photo Editor

[Open ID Photo Editor](https://mihandreikov.github.io/id-photo-editor/)

A browser-based editor for preparing ID and passport photos. Position the face with visual guides, check the measurements, and export a JPEG or printable 10 × 15 cm sheet.

The editor runs entirely in your browser. Your photos are processed locally, stay on your device, and are never uploaded by the app.

## Supported templates

| Template | Output size | Physical size | JPEG target | Source |
| --- | ---: | ---: | ---: | --- |
| Finland | 500 × 653 px | 36 × 47 mm | 250 KB max | [Finnish Police](https://poliisi.fi/documents/25235045/31329600/Passport-photograph-instructions-by-the-police-2020-EN-fixed.pdf) |
| Schengen visa print | 413 × 531 px at 300 ppi | 35 × 45 mm | 500 KB default | [EEAS](https://www.eeas.europa.eu/delegations/china/schengen-visa-application-process-essential-guide_en) |
| U.S. visa digital | 600 × 600 px | 51 × 51 mm | 240 KB max | [U.S. State Department](https://travel.state.gov/content/travel/en/us-visas/visa-information-resources/photos/digital-image-requirements.html) |
| Custom | Configurable | Configurable | Configurable | — |

The custom template also supports configurable margins, face height, centering, background color, and file size.

Requirements can vary by document, submission channel, applicant age, and issuing authority. In particular, “Schengen” is not a single universal digital-photo upload specification; check the responsible consulate before submission.

## Privacy

Photos are processed locally in your browser and are never uploaded by the app. There are no accounts, analytics, tracking scripts, cookies, or remote storage. Exported JPEG files are saved directly to your device.

## Important limitations

- The guide positions are set manually; the app does not perform face detection or biometric validation.
- A green measurement means the manually placed guides fit the configured ranges, not that a government agency will accept the photo.
- Photo rules can change and may include requirements the editor does not evaluate, such as lighting, expression, focus, background uniformity, eyewear, and head coverings.
- JPEG compression cannot guarantee every image will retain the same visual quality at a strict file-size limit.

Always check the current requirements published by the authority receiving the photo before submitting or printing it.

## Contributing

Issues and pull requests are welcome. When changing a preset, cite an authoritative source for the photo requirements and verify both single-photo and print-layout exports.
