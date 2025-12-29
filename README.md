# Asset Library Test Repository

This repository contains test files for Unity Asset Library Editor Tool.

## File Structure

```
asset-library-test/
├── library_index.json    # Asset library index (published assets)
├── users.json            # User authentication data
└── packages/             # Unity package files (.unitypackage)
    └── (package files go here)
```

## Setup Instructions

1. Upload `library_index.json` to the root directory
2. Upload `users.json` to the root directory
3. Create `packages/` folder and upload `.unitypackage` files there

## Unity Config

In Unity Editor, set the Cloud Storage Base URL to:
```
https://raw.githubusercontent.com/alperdorukalkan/asset-library-test/main
```

## Test Users

All users have password: `test123`

- **admin** - Admin role (full access)
- **reviewer** - Reviewer role (can review and publish)
- **user** - User role (can view and download)

## Notes

- Repository must be public for raw URL access
- Files are accessed via GitHub Raw URLs
- Branch name is `main` (default)

