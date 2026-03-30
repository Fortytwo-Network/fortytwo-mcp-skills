# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.0] - 2026-03-30

### Added
- Wallet setup guide directly in the skill instructions
- Automatic network selection based on where you have USDC
- Session lifetime info: 90 min total, 15 min idle timeout

### Changed
- Skill now asks for confirmation before making paid calls (except explicit "Ask Fortytwo" requests)
- Cleaner instructions — removed redundant sections
- Query timeout raised to 10 minutes to match actual inference time
- Pricing now links to the live page instead of hardcoded rates
- Requires Python 3.9+

### Removed
- Marketplace plugin (will be added back when publishing)

## [1.0.2] - 2026-03-28

- Initial release
