<p align="center">
  <img src="https://reseam.app/logo.svg" alt="Reseam" width="120" />
</p>

<h1 align="center">Reseam</h1>

Reseam applies community-built patches to Android apps on your device. You pick the patches you want, and Reseam builds a modified version of the app to install alongside your original. The patch engine runs on your phone. Nothing about your apps leaves the device.

The repositories under this GitHub organisation are a read-only mirror. Source of truth is [git.reseam.app](https://git.reseam.app). Docs are at [reseam.app/docs](https://reseam.app/docs).

## Using Reseam

Install Reseam Manager on Android, pick an app, pick the patches you want, and tap apply. The patched app installs alongside the original. They're separate apps; the original stays untouched.

Downloads and the current patch catalogue are at [reseam.app](https://reseam.app).

## Repositories

| Repo | Contents |
|------|----------|
| [`reseam`](https://github.com/reseam/reseam) | Patch engine (`reseam-patcher`), `reseam` CLI, Kotlin patch SDK. Rust workspace. |
| [`patches`](https://github.com/reseam/patches) | Official patch bundle. |
| [`api`](https://github.com/reseam/api) | `api.reseam.app`: patch index, release redirects, announcements. |
| [`website`](https://github.com/reseam/website) | `reseam.app`. |
| [`brand`](https://github.com/reseam/brand) | Logo, tone, colours, typography. |

## License

GPL-3.0. See each repository for specifics.
