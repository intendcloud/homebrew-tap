# IntendCloud Homebrew Tap

Homebrew formulae for IntendCloud CLI tools.

## Installation

```bash
# Add the tap
brew tap intendcloud/tap

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
- CIS AWS, Azure, GCP compliance scanning (free)
- Checkov integration for IaC scanning
- Prowler integration for runtime scanning (coming soon)
- JSON/HTML/CSV report generation
- Enterprise frameworks: SOC2, ISO 27001, PCI-DSS, NIST, DORA (paid)

**Documentation:** https://github.com/intendcloud/intend

## Enterprise Platform

For production-ready Terraform modules, DevSecOps tooling, and enterprise compliance frameworks:
- **Website:** https://intendcloud.com
- **Platform:** https://github.com/intendcloud/intendcloud-platform (private, invite-only)

## Support

- **Free CLI Issues:** https://github.com/intendcloud/intend/issues
- **Platform Support:** support@intendcloud.com

## License

Formulae in this tap are released under MIT License.
