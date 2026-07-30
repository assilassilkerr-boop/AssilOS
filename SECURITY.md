# Security Policy

## Supported Versions

AssilOS is a hobby/educational project. Security updates are provided on a best-effort basis.

| Version | Supported |
|---------|-----------|
| Latest (main branch) | ✅ |
| Older versions | ❌ |

## Reporting a Vulnerability

If you discover a security issue in AssilOS, please:

1. **Do NOT** open a public issue (to protect users)
2. **Email me directly** at: [assilassilkerr@gmail](assilassilkerr@gmail.com)
3. **Include**:
   - A clear description of the issue
   - Steps to reproduce (hardware/emulator, BIOS settings, etc.)
   - Any potential impact

## What to Expect

- I'll acknowledge your report within **48 hours**
- I'll investigate and confirm the issue
- If valid, I'll work on a fix
- I'll credit you in the CHANGELOG (unless you prefer anonymity)

## Known Limitations

AssilOS runs in 16-bit real mode and has no:
- Memory protection
- Privilege separation
- Network stack
- Filesystem drivers

**Treat it as a retro-computing experiment, not a production OS.**

## Disclosure Policy

- Fixes will be pushed to the main branch
- Minor security notes will be added to CHANGELOG.md
- Critical fixes may warrant a new release tag

---

*This security policy follows the [GitHub Security Advisories](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/about-coordinated-disclosure-of-security-vulnerabilities) guidelines.*