# GuestKit Documentation

Welcome to the GuestKit documentation! This directory contains all project documentation organized by category.

📑 **Quick Index**: See [INDEX.md](INDEX.md) for a complete documentation map and quick navigation.

## 📚 Documentation Structure

### 🎯 [User Guides](user-guides/) - User-Facing Documentation

Start here if you're learning to use GuestCtl!

**Getting Started:**
- **[Getting Started](user-guides/getting-started.md)** - Quick start guide
- **[CLI Guide](user-guides/cli-guide.md)** - Command-line interface usage
- **[Quick Reference](user-guides/quick-reference.md)** - Quick command reference
- **[FAQ](user-guides/faq.md)** ⭐ NEW - Frequently asked questions

**Advanced Features:**
- **[VM Migration Guide](user-guides/vm-migration.md)** ⭐ NEW - Complete migration workflows (Hyper-V, VMware, P2V)
- **[Windows Support](user-guides/windows-support.md)** ⭐ NEW - Windows registry, VirtIO drivers, users
- **[Interactive Mode](user-guides/interactive-mode.md)** - REPL for disk exploration
- **[Profiles](user-guides/profiles.md)** - Security, migration, performance profiles

**Python & APIs:**
- **[Python Bindings](user-guides/python-bindings.md)** - Python API guide

**Reference & Help:**
- **[Visual Output Guide](user-guides/visual-output-guide.md)** ⭐ NEW - Color coding, emojis, terminal output
- **[Best Practices](user-guides/best-practices.md)** ⭐ NEW - Expert recommendations
- **[Troubleshooting](user-guides/troubleshooting.md)** - Common issues and solutions

### ⚡ [Features](features/) - Feature Documentation

Deep dives into specific features.

- **[Export Formats](features/export-formats.md)** - HTML and Markdown report export
- **[Output Formats](features/output-formats.md)** - JSON, YAML, CSV output
- **[HTML Export](features/html-export.md)** - Interactive HTML reports with charts
- **[History Persistence](features/history-persistence.md)** - Command history across sessions

### 📖 [API Documentation](api/) - API References

Complete API documentation for developers.

- **[Python API Reference](api/python-reference.md)** - Complete Python API (100+ methods)
- **[Rust API Reference](api/rust-reference.md)** - Rust API documentation
- **[Ergonomic Design](api/ergonomic-design.md)** - Type-safe Rust API guide
- **[Migration Guide](api/migration-guide.md)** - Migrating from 

### 🏗️ [Architecture](architecture/) - Technical Documentation

Understand how GuestCtl works internally.

- **[Overview](architecture/overview.md)** - System architecture
- **[Comparison Guide](architecture/comparison-guide.md)** - GuestCtl vs alternatives
- **[Performance](architecture/performance.md)** - Performance characteristics
- **[UX Design](architecture/ux-design.md)** - User experience decisions
- **[ Comparison](architecture/-comparison.md)** - Detailed comparison

### 🔧 [Development](development/) - Contributor Documentation

For contributors and developers extending GuestKit.

**Project Planning:**
- **[Roadmap 2026](development/roadmap-2026.md)** - Project roadmap and future plans
- **[Q1 2026 Implementation](development/Q1-2026-IMPLEMENTATION-START.md)** - Q1 2026 roadmap details
- **[Next Steps](development/next-steps.md)** - Upcoming priorities
- **[Enhancement Roadmap](development/enhancement-roadmap.md)** - Future enhancements (100+ ideas)
- **[Quick Enhancements](development/quick-enhancements.md)** - Quick wins to implement

**Development Logs:**
- **[Improvements Log](development/improvements-log.md)** - Recent improvements and enhancements
- **[Enhancements Implemented](development/enhancements-implemented.md)** - What's been done
- **[Commands Summary](development/COMMANDS_SUMMARY.md)** - All CLI commands reference
- **[Inspect Enhanced Improvements](development/INSPECT_ENHANCED_IMPROVEMENTS.md)** - Enhanced inspection features
- **[Documentation Enhancements](development/DOCUMENTATION_ENHANCEMENTS.md)** - Documentation improvements
- **[Documentation Update Summary](development/DOCUMENTATION_UPDATE_SUMMARY.md)** - Documentation updates

**Test Coverage:**
- **[Test Coverage Initiative](development/test-coverage-initiative-complete.md)** - Complete test coverage report
- **[Complete Session Summary](development/complete-session-summary.md)** - Development session summary

**Publishing & APIs:**
- **[Publishing](development/publishing.md)** - PyPI publishing process
- **[Missing APIs](development/missing-apis.md)** - APIs not yet implemented

### 🎨 [Marketing](marketing/) - Community & Promotion

Marketing materials and community engagement.

- **[LinkedIn Post](marketing/linkedin-post.md)** - Social media announcements and templates

### 📦 [Archive](archive/) - Historical Documentation

Historical documents for reference.

- **[Testing](archive/testing/)** - Historical test reports and results
- **[Status](archive/status/)** - Implementation status tracking
- **[Completions](archive/)** - Phase completion summaries
- **[Enhancements](archive/)** - Historical enhancement documentation

## 🚀 Quick Navigation

### New Users
1. Read [Getting Started](user-guides/getting-started.md)
2. Check [CLI Guide](user-guides/cli-guide.md)
3. Try [Interactive Mode](user-guides/interactive-mode.md)

### Python Developers
1. [Python Bindings Guide](user-guides/python-bindings.md)
2. [Python API Reference](api/python-reference.md)
3. [Python Examples](../examples/python/)

### Rust Developers
1. [Architecture Overview](architecture/overview.md)
2. [Rust API Reference](api/rust-reference.md)
3. [Ergonomic Design](api/ergonomic-design.md)

### Contributors
1. [Improvements Log](development/improvements-log.md)
2. [Roadmap 2026](development/roadmap-2026.md)
3. [Enhancement Roadmap](development/enhancement-roadmap.md)

### System Administrators
1. [CLI Guide](user-guides/cli-guide.md)
2. [Profiles](user-guides/profiles.md)
3. [Export Formats](features/export-formats.md)

## 🔍 Common Tasks

### I want to...

- **Get started quickly** → [Getting Started](user-guides/getting-started.md)
- **Migrate VMs** → [VM Migration Guide](user-guides/vm-migration.md) ⭐ NEW
- **Work with Windows VMs** → [Windows Support](user-guides/windows-support.md) ⭐ NEW
- **Use from command line** → [CLI Guide](user-guides/cli-guide.md)
- **Use interactively** → [Interactive Mode](user-guides/interactive-mode.md)
- **Use from Python** → [Python Bindings](user-guides/python-bindings.md)
- **Understand colors/emojis** → [Visual Output Guide](user-guides/visual-output-guide.md) ⭐ NEW
- **Learn best practices** → [Best Practices](user-guides/best-practices.md) ⭐ NEW
- **Do security audits** → [Profiles](user-guides/profiles.md)
- **Export HTML reports** → [HTML Export](features/html-export.md)
- **Export data (JSON/CSV)** → [Output Formats](features/output-formats.md)
- **Understand architecture** → [Architecture Overview](architecture/overview.md)
- **Compare with alternatives** → [Comparison Guide](architecture/comparison-guide.md)
- **Find answers** → [FAQ](user-guides/faq.md) ⭐ NEW
- **Contribute code** → [Development](development/)
- **Fix issues** → [Troubleshooting](user-guides/troubleshooting.md)

## 📝 Documentation Standards

All documentation follows these standards:

- **Format:** Markdown with GitHub-flavored extensions
- **Code Examples:** Tested and working
- **Updates:** Keep in sync with code changes
- **Links:** Use relative links within documentation
- **Structure:** Clear hierarchy with consistent naming

## 🤝 Contributing to Documentation

Found an issue or want to improve documentation?

1. Check [CONTRIBUTING.md](../CONTRIBUTING.md) for guidelines
2. Submit issues at [GitHub Issues](https://github.com/ssahani/guestkit/issues)
3. Submit PRs for documentation improvements

## 📧 Support

- **Issues:** https://github.com/ssahani/guestkit/issues
- **Discussions:** https://github.com/ssahani/guestkit/discussions
- **Email:** ssahani@redhat.com

## External Resources

- **Project Repository:** [GitHub](https://github.com/ssahani/guestkit)
- **PyPI Package:** [guestctl on PyPI](https://pypi.org/project/guestctl/) (coming soon)
- **Crates.io:** [guestctl on crates.io](https://crates.io/crates/guestctl)

---

**Documentation Version:** 0.3.1
**Last Updated:** 2026-01-27
**License:** LGPL-3.0-or-later
