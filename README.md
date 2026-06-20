# Bytescale (bytescale)

Bytescale (formerly Upload.io) is a file upload, storage, image / video / audio processing, and CDN platform for developers. A simple REST API uploads files (binary, multipart form data, or from a URL), manages files and folders, and serves optimized media through real-time, URL-based transformations on a global CDN.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bytescale/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bytescale/refs/heads/main/apis.yml)

## Tags

- File Upload
- Storage
- Image Processing
- CDN
- Media

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Bytescale File Upload API

Upload files with a single HTTP request - raw binary, multipart form data (multiple files), or from a remote URL - plus a multipart workflow for very large files. Returns the stored file path and public CDN file URL.

- **Human URL:** [https://www.bytescale.com/docs/upload-api](https://www.bytescale.com/docs/upload-api)
- **Base URL:** `https://api.bytescale.com/v2/accounts/{accountId}`

#### Tags

- File Upload
- Binary
- Form Data

#### Properties

- [Documentation](https://www.bytescale.com/docs/upload-api)
- [API Reference](https://www.bytescale.com/docs/upload-api/BasicUpload)
- [OpenAPI](openapi/bytescale-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bytescale.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bytescale.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bytescale Files Management API

Inspect file details, download original files, delete files, copy files, and list, create, or delete folders for managing stored assets.

- **Human URL:** [https://www.bytescale.com/docs/file-api](https://www.bytescale.com/docs/file-api)
- **Base URL:** `https://api.bytescale.com/v2/accounts/{accountId}`

#### Tags

- Files
- Folders
- Storage

#### Properties

- [Documentation](https://www.bytescale.com/docs/file-api)
- [API Reference](https://www.bytescale.com/docs/file-api/GetFileDetails)
- [OpenAPI](openapi/bytescale-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bytescale.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bytescale.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bytescale Image / Video Processing API

Real-time, URL-based image, video, and audio processing - resize, crop, convert format, compress, blur, rotate, watermark, add text, and extract video thumbnails - applied via query-string parameters on GET requests and cached at the edge.

- **Human URL:** [https://www.bytescale.com/docs/image-processing-api](https://www.bytescale.com/docs/image-processing-api)
- **Base URL:** `https://upcdn.io/{accountId}`

#### Tags

- Image Processing
- Video
- Transformations

#### Properties

- [Documentation](https://www.bytescale.com/docs/image-processing-api)
- [API Reference](https://www.bytescale.com/docs/image-processing-api)
- [OpenAPI](openapi/bytescale-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Bytescale CDN / Serving API

Global CDN delivery of raw and transformed files via the upcdn.io edge network, serving uploaded assets and their processed variants over HTTPS.

- **Human URL:** [https://www.bytescale.com/image-cdn](https://www.bytescale.com/image-cdn)
- **Base URL:** `https://upcdn.io/{accountId}`

#### Tags

- CDN
- Serving
- Delivery

#### Properties

- [Documentation](https://www.bytescale.com/image-cdn)
- [OpenAPI](openapi/bytescale-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/bytescale)
- [LinkedIn](https://www.linkedin.com/company/bytescale)
- [Website](https://www.bytescale.com)
- [Documentation](https://www.bytescale.com/docs)
- [Plans](plans/bytescale-plans-pricing.yml)
- [Rate Limits](rate-limits/bytescale-rate-limits.yml)
- [Fin Ops](finops/bytescale-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
