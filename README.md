# scoop-certz

Scoop bucket for [certz](https://github.com/michaellwest/certz) -- a developer-friendly X.509 certificate toolkit packed into a single executable.

## Usage

### Installing

```powershell
scoop bucket add certz https://github.com/michaellwest/scoop-certz
scoop install certz
```

### Running

```powershell
certz create dev localhost --trust
```

### Updating

```powershell
scoop update certz
```

## About certz

Self-contained .NET CLI tool for creating, inspecting, converting, and managing X.509 certificates. Features include:

- Create development and CA certificates with sensible defaults
- Inspect certificates from files, URLs, or the local store
- Convert between PFX, PEM, and DER formats
- Trust certificates in the Windows or Linux trust store
- Lint certificates against CA/B Forum baseline requirements
- Monitor remote certificate expiration
- Single executable -- no runtime required

See the [certz README](https://github.com/michaellwest/certz#readme) for full documentation.
