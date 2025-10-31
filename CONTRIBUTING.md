# 🤝 Contributing to AimTrainerX

Thank you for your interest in contributing to AimTrainerX! This document provides guidelines and instructions for contributing.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Features](#suggesting-features)
- [Translation Contributions](#translation-contributions)
- [Code Contributions](#code-contributions)
- [Documentation](#documentation)
- [Community Guidelines](#community-guidelines)

---

## 📜 Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it before contributing.

**In Summary:**
- Be respectful and inclusive
- Welcome newcomers
- Focus on constructive feedback
- Respect differing opinions
- Report unacceptable behavior

---

## 🎯 How Can I Contribute?

There are many ways to contribute to AimTrainerX:

### 1. 🐛 Report Bugs
Found a bug? Help us fix it!
- [Report a bug](https://github.com/LinightKira/aimtrainerx/issues/new?template=bug_report.md)

### 2. 💡 Suggest Features
Have an idea for a new feature?
- [Request a feature](https://github.com/LinightKira/aimtrainerx/issues/new?template=feature_request.md)

### 3. 💬 Share Feedback
General feedback is always welcome!
- [Share feedback](https://github.com/LinightKira/aimtrainerx/issues/new?template=feedback.md)

### 4. 🌐 Help with Translations
Make AimTrainerX accessible to more users!
- [See translation guidelines](#translation-contributions)

### 5. 💻 Contribute Code
Help us build new features!
- [See code guidelines](#code-contributions)

### 6. 📖 Improve Documentation
Help others understand AimTrainerX better!
- [See documentation guidelines](#documentation)

### 7. ⭐ Spread the Word
Share AimTrainerX with other gamers!
- Star the repository
- Share on social media
- Recommend to friends

---

## 🐛 Reporting Bugs

### Before Submitting a Bug Report

1. **Check existing issues**: Someone might have already reported it
2. **Try the latest version**: The bug might already be fixed
3. **Test in different browsers**: Confirm it's not browser-specific
4. **Clear cache**: Sometimes old data causes issues

### How to Submit a Good Bug Report

Use our [Bug Report Template](https://github.com/LinightKira/aimtrainerx/issues/new?template=bug_report.md) and include:

- **Clear title**: "Flick training crashes on Chrome 120"
- **Steps to reproduce**: Detailed, numbered steps
- **Expected behavior**: What should happen
- **Actual behavior**: What actually happens
- **Screenshots**: Visual evidence helps!
- **Environment**: Browser, OS, device
- **Frequency**: How often it occurs

**Example Good Bug Report:**
```
Title: Target disappears when mouse leaves browser window

Steps to Reproduce:
1. Start Flick Shots mode
2. Move cursor outside browser window
3. Return cursor to browser

Expected: Target should still be visible
Actual: Target disappears and doesn't reappear

Browser: Chrome 120.0.6099.109
OS: Windows 11
Frequency: Always (100%)
```

---

## 💡 Suggesting Features

### Before Suggesting a Feature

1. **Check the [Roadmap](ROADMAP.md)**: Might already be planned
2. **Search existing requests**: Avoid duplicates
3. **Consider feasibility**: Is it technically possible?

### How to Submit a Good Feature Request

Use our [Feature Request Template](https://github.com/LinightKira/aimtrainerx/issues/new?template=feature_request.md) and include:

- **Clear description**: What is the feature?
- **Problem statement**: What problem does it solve?
- **Use cases**: When would it be used?
- **Benefits**: How does it improve the platform?
- **Examples**: Similar features in other apps?
- **Mockups**: Visual representation (if applicable)

**Example Good Feature Request:**
```
Title: Add audio feedback for hits and misses

Problem: Hard to focus on targets while checking accuracy stats

Proposed Solution: 
- Play "ding" sound on hit
- Play "miss" sound on miss
- Make sounds customizable in settings

Benefits:
- Immediate feedback without looking at stats
- Better training focus
- Improves user experience

Similar to: Aim Lab's audio feedback system
```

---

## 🌐 Translation Contributions

Help make AimTrainerX accessible to more players worldwide!

### Current Languages
- ✅ English (en)
- ✅ Chinese Simplified (zh-CN)
- ✅ Japanese (ja)
- ✅ Portuguese (pt)
- ✅ Russian (ru)
- ✅ Korean (ko)
- ✅ German (de)
- ✅ Spanish (es)

### Needed Languages
- 🔄 French (fr)
- 🔄 Turkish (tr)
- 🔄 Polish (pl)
- 🔄 Italian (it)
- 🔄 Thai (th)
- 🔄 Vietnamese (vi)
- 🔄 Arabic (ar)

### Translation Guidelines

#### 1. Translation Quality
- **Native or fluent** speakers only
- **Accurate** translations (not machine-translated)
- **Natural** phrasing (not literal word-for-word)
- **Consistent** terminology throughout

#### 2. What to Translate
- README files (README.xx.md)
- UI text strings
- Training mode descriptions
- Error messages
- Help documentation

#### 3. What NOT to Translate
- Code comments
- Variable names
- Technical terms (e.g., "FPS", "DPI")
- Brand names
- URLs

#### 4. Translation Process

**Step 1: Check Existing Translations**
Look at existing language files for reference

**Step 2: Fork the Repository**
Create your own copy to work on

**Step 3: Create Translation File**
Copy `README.md` → `README.xx.md` (xx = language code)

**Step 4: Translate Content**
Translate all user-facing text

**Step 5: Review & Test**
Check for errors and test if possible

**Step 6: Submit Pull Request**
Submit your translation for review

#### 5. Translation Style Guide

- **Tone**: Friendly, encouraging, professional
- **Style**: Consistent with existing translations
- **Technical accuracy**: Maintain meaning of technical terms
- **Cultural sensitivity**: Adapt idioms and culturally-specific content
- **Length**: Try to match original length (for UI elements)

#### 6. Gaming Terminology

Use established gaming terms in your language:
- "Flick shots" → Use common term in your language
- "Tracking" → Use term FPS gamers understand
- "Aim training" → Use widely recognized term

**Example Pull Request Title:**
```
[Translation] Add French (fr) README and UI strings
```

---

## 💻 Code Contributions

> **Note**: This is a marketing/documentation repository. Code contributions for the main application should be directed to the appropriate development repository.

### For This Repository

You can contribute:
- Documentation improvements
- README enhancements
- Asset organization
- Marketing materials
- Translation files

### Code Style Guidelines

#### Markdown Files
- Use proper heading hierarchy (# → ## → ###)
- Add blank lines between sections
- Use tables for comparisons
- Include emojis for visual appeal
- Keep lines under 120 characters (when possible)

#### File Organization
```
/
├── README.md (and translations)
├── CHANGELOG.md
├── ROADMAP.md
├── CONTRIBUTING.md
├── LICENSE
├── CODE_OF_CONDUCT.md
├── .github/
│   └── ISSUE_TEMPLATE/
├── docs/
│   ├── FAQ.md
│   └── COMPARISON.md
├── assets/
│   ├── screenshots/
│   ├── logos/
│   └── demo/
└── marketing/
```

### Pull Request Process

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Make** your changes
4. **Test** your changes (if applicable)
5. **Commit** with clear messages (`git commit -m 'Add amazing feature'`)
6. **Push** to your branch (`git push origin feature/amazing-feature`)
7. **Open** a Pull Request

#### Pull Request Guidelines

**Title Format:**
```
[Type] Brief description

Examples:
[Docs] Update FAQ with new questions
[Translation] Add Italian README
[Fix] Correct typo in CONTRIBUTING.md
[Feature] Add comparison table
```

**Description Template:**
```markdown
## What does this PR do?
Brief description of changes

## Why is this needed?
Explain the motivation

## Related Issues
Closes #123

## Checklist
- [ ] Documentation updated
- [ ] Translations updated (if applicable)
- [ ] Links tested
- [ ] Screenshots updated (if applicable)
```

---

## 📖 Documentation

Good documentation helps everyone!

### What to Document
- New features
- Setup instructions
- Common issues and solutions
- Best practices
- Use cases and examples

### Documentation Style
- **Clear** and concise
- **Examples** for complex topics
- **Screenshots** when helpful
- **Updated** regularly
- **Accurate** information

### Documentation Checklist
- [ ] Grammar and spelling checked
- [ ] Links verified
- [ ] Code examples tested
- [ ] Screenshots current
- [ ] Cross-referenced where needed

---

## 👥 Community Guidelines

### Being a Good Community Member

✅ **Do:**
- Be respectful and kind
- Welcome newcomers
- Help answer questions
- Provide constructive feedback
- Give credit to others
- Celebrate successes

❌ **Don't:**
- Be rude or disrespectful
- Spam or self-promote excessively
- Post off-topic content
- Share personal information
- Harass or bully others

### Communication Channels

- **GitHub Issues**: Bug reports, feature requests
- **GitHub Discussions**: General questions, ideas
- **Email**: support@aimtrainerx.com
- **Discord** (coming soon): Community chat
- **Twitter/X** (coming soon): Updates and news

---

## 🎖️ Recognition

Contributors are recognized in several ways:

- **Contributors list** on GitHub
- **Acknowledgments** in CHANGELOG
- **Special mention** for major contributions
- **Community badges** (coming soon)

Top contributors may also:
- Get early access to new features
- Influence development priorities
- Be invited to beta testing

---

## ❓ Questions?

Have questions about contributing?

- 📧 Email: support@aimtrainerx.com
- 💬 [Open a discussion](https://github.com/LinightKira/aimtrainerx/discussions)
- 📖 Read the [FAQ](docs/FAQ.md)

---

## 📜 License

By contributing, you agree that your contributions will be licensed under the same [MIT License](LICENSE) that covers the project.

---

<div align="center">

**Thank you for contributing to AimTrainerX! 🎯**

Every contribution, no matter how small, helps make AimTrainerX better for everyone.

[🎮 Try AimTrainerX](https://aimtrainerx.com) | [📖 Documentation](docs/) | [🗺️ Roadmap](ROADMAP.md)

</div>
