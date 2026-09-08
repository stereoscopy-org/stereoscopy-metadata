# Stereoscopy Metadata Specification

An open XMP vocabulary for describing the views contained in self-contained stereoscopic images.

Version 1.0 declares:

- how views are stored in an image;
- which eye perspective each stored view represents;
- which view is preferred for ordinary 2D display; and
- whether an individual viewpoint was synthesized.

The specification is intentionally small, human-readable, and compatible with native container metadata such as GPano, Apple spatial metadata, and CIPA DC-006.

## Current specification

- [Stereoscopy Metadata 1.0](spec/1.0.md)
- Namespace: `https://stereoscopy.org/ns/stereo/1.0/`
- Status: 1.0 implementation specification

## Examples

See [`examples/`](examples/) for complete XMP packets covering captured pairs, synthesized views, anaglyphs, Google VR photos, and Apple spatial photos.

## Contributing

Questions, interoperability reports, and proposals are welcome through GitHub Issues. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before proposing vocabulary changes.

## License

Specification text is licensed under [CC BY 4.0](LICENSE.md).
