# orion-updates

Signed updates for ORION / VIDEOCLUB 98 boards, written by `tools/ota_publish.py` in the ORION repository: `manifest` (an HMAC-SHA256 signature line, then the version, its notes and every file's SHA-256 and size) and `files/<sha256>`.
Boards check it at boot and hourly; nothing here is edited by hand.
