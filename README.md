# scummpacker-mirror

Unmodified mirror of **ScummPacker v3.2** (build of 2014-08-01), a tool to unpack and repack the resource files of LucasArts SCUMM games (v3 to v6).

- **Author:** Laurence Dougal Myers
- **Original site:** https://www.jestarjokin.net/apps/scummpacker
- **License:** MIT (see [LICENSE](LICENSE) and `docs/scummpacker_manual.html` inside the zip)

## About this repository

This is **not the official project** and contains no changes to the software. It only hosts the original binary release under a stable direct download URL, to avoid using the author's server bandwidth.

## Download

Get `scummpacker_3.2_2014-08-01.zip` from the [Releases](../../releases) page. It has the same content as the original release, repackaged as a zip:

- `scummpacker.exe`
- `library.zip`, `python25.dll`, `MSVCR71.dll`, `w9xpopen.exe` (runtime files bundled by the author)
- `docs/scummpacker_manual.html`

## Usage

See the manual in `docs/`. Example:

    scummpacker -v5 -g MI2 -i <unpacked folder> -o <output folder> -p

## Credits

All credit goes to Laurence Dougal Myers. To support or contact the author, use his website above.
