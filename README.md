# App Releases

Welcome to the official app releases repository! This is a public distribution channel for application binaries, installers, and release packages.

## 📋 Purpose

This repository serves as a centralized location for distributing application releases to end users. It contains **only compiled binaries and release artifacts** - no source code is included or maintained here.

## 🎯 Key Ideas

- **Binary Distribution**: Host ready-to-use application packages
- **Version Management**: Maintain organized release history with semantic versioning
- **Public Access**: Provide easy download access for all users
- **Separation of Concerns**: Keep release artifacts separate from source code repositories

## 📜 Repository Rules

### For Maintainers

1. **No Source Code**: Never commit source code, development files, or proprietary information
2. **Release Assets Only**: Only upload compiled binaries, installers, and official release packages
3. **Semantic Versioning**: Follow [semver](https://semver.org/) format (e.g., v1.0.0, v2.1.3)
4. **Release Notes**: Always include release notes describing changes and improvements
5. **Asset Naming**: Use consistent naming convention: `{app-name}-{version}-{platform}.{ext}`
6. **Security**: Verify all binaries before upload and provide checksums when possible
7. **Testing**: Test releases in isolated environments before publishing
8. **Cleanup**: Remove outdated or deprecated releases when necessary

### For Users

1. **Download Official Releases**: Only download from official GitHub releases
2. **Verify Checksums**: When provided, verify file integrity using checksums
3. **Check Compatibility**: Ensure the release matches your platform/OS
4. **Read Release Notes**: Review release notes before updating
5. **Report Issues**: Use the issues section to report problems with releases

## 📥 How to Download Releases

### Using GitHub Releases Page

1. Navigate to the [Releases](../../releases) section
2. Find the version you want to download
3. Download the appropriate file for your platform from the Assets section
4. Verify the checksum if provided

### Using Command Line

```bash
# Download latest release (example)
curl -L https://github.com/hantoptw/app-releases/releases/latest/download/{asset-name} -o {output-file}

# Or using wget
wget https://github.com/hantoptw/app-releases/releases/latest/download/{asset-name}
```

## 🏷️ Release Naming Convention

Releases follow this structure:

- **Tag Format**: `v{major}.{minor}.{patch}[-{prerelease}]`
  - Example: `v1.0.0`, `v2.1.0-beta`, `v1.0.0-rc.1`

- **Asset Format**: `{app-name}-{version}-{platform}-{arch}.{extension}`
  - Example: `myapp-1.0.0-linux-x64.tar.gz`
  - Example: `myapp-1.0.0-windows-x64.zip`
  - Example: `myapp-1.0.0-macos-arm64.dmg`

## 🔍 What You'll Find Here

- ✅ Compiled application binaries
- ✅ Installation packages (`.exe`, `.dmg`, `.deb`, `.rpm`, etc.)
- ✅ Portable/standalone versions
- ✅ Release notes and changelogs
- ✅ Checksums (SHA-256, MD5) when applicable

## ❌ What You Won't Find Here

- ❌ Source code
- ❌ Development files
- ❌ Build scripts or configurations
- ❌ Documentation source files
- ❌ Test files or development tools

## 📞 Support

- **Issues**: Report bugs or problems with releases in the [Issues](../../issues) section
- **Questions**: For general questions, open a discussion or issue
- **Security**: Report security vulnerabilities through appropriate channels (if specified)

## 🤝 Contributing

This repository is for release distribution only. If you want to contribute to the application development:

- Source code contributions should be made to the main development repository
- For release-related issues (download problems, broken packages), open an issue here
- Suggestions for release improvements are welcome

## 📄 License

Release artifacts are provided as-is. Please refer to the LICENSE file in each release or the main project repository for licensing information.

## 🔄 Version History

Check the [Releases](../../releases) page for the complete version history and release notes.

---

**Note**: This repository contains only distribution packages. For source code, development, or detailed documentation, please refer to the main project repository.
