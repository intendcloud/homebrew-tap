# IntendCloud Homebrew Tap

Homebrew formulae for IntendCloud CLI tools.

## Installation

```bash
# Add the tap
brew tap therajushahi/tap

# Install intendcloud CLI
brew install intend
```

## Usage

```bash
# Run compliance audit
intend audit --terraform-dir ./my-terraform --frameworks cis-aws

# View help
intend --help
```

## Available Formulae

### intend
Compliance scanning CLI for Terraform and cloud infrastructure.

**Features:**
- CIS AWS v3.0.0 compliance scanning (free)
- Checkov integration for IaC scanning
- Prowler integration for runtime scanning (coming soon)
- JSON/HTML/PDF report generation
- Support for SOC2, ISO 27001, and more (paid tiers)

**Documentation:** https://github.com/therajushahi/intendcloud-platform

## Support

- **Issues:** https://github.com/therajushahi/intendcloud-platform/issues
- **Discussions:** https://github.com/therajushahi/intendcloud-platform/discussions

## License

Formulae in this tap are released under MIT License.
