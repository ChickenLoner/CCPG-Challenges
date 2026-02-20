# 🔐 CyberChef Playground Challenge Pack

Official challenge repository for CyberChef Playground

## 📦 What's Included

This repository contains challenges for the CyberChef Playground CTF platform.

**Challenge Count:** 0   

## 🚀 Quick Install

### Prerequisites
- [CyberChef Playground](https://github.com/ChickenLoner/cyberchef-playground) installed
- Git installed

### Installation

```bash
cd /path/to/cyberchef-playground
npm run fetch-challenges
```

That's it! Challenges are automatically installed and ready to play.

## 🛠️ Technical Details

### Repository Structure
```
CCPG-Challenges/
├── README.md                      ← This file
├── challenges-config/             ← Challenge configurations
│   ├── level1.json
│   ├── level2.json
│   ├── level3.json
│   ├── level4.json
│   └── level5.json
├── challenges/                    ← Challenge files (encrypted, packed, etc.)
│   ├── level1_challenge.zip
│   ├── level1_validation.bin
│   ├── level2_challenge.zip
│   ├── level2_validation.bin
│   ├── level3_challenge.zip
│   ├── level3_validation.bin
│   ├── level4_challenge.zip
│   ├── level4_validation.bin
│   ├── level5_challenge.zip
│   └── level5_validation.bin
└── solutions/                     ← Solution recipes (JSON)
    ├── level1_solution.json
    ├── level2_solution.json
    ├── level3_solution.json
    ├── level4_solution.json
    └── level5_solution.json
```

### Validation System
- Each challenge includes a **validation file** (not given to players)
- Server runs your solution against this file
- SHA256 hash comparison ensures correctness
- Works with both text and binary data

### File Formats
- **Configs:** JSON files with challenge metadata
- **Challenges:** ZIP archives containing challenge files
- **Validation:** files for server-side validation
- **Solutions:** CyberChef recipe JSON files

## 🔒 Security Notice

**For Educational Purposes Only**

These challenges are designed for:
- Learning cryptography and reverse engineering
- Practicing malware analysis techniques
- Blue team training
- CTF competition preparation

**Challenges contain:**
- Simulated malware scenarios (not real malware)
- Safe sample files
- Educational content only

## 🤝 Contributing

Want to add challenges to this pack?

1. Fork this repository
2. Create your challenge files
3. Follow the structure guidelines
4. Test thoroughly
5. Submit a pull request

## 📚 Resources

### CyberChef
- **Web App:** https://gchq.github.io/CyberChef/
- **GitHub:** https://github.com/gchq/CyberChef
- **Operations List:** 300+ operations available

### CyberChef Playground
- **Main Repo:** https://github.com/ChickenLoner/cyberchef-playground
- **Documentation:** See repo README
- **Issues:** Report bugs or request features

## 🎯 Challenge Difficulty Guide

### Easy (50-100 pts)
- Single operation or very simple chains
- Clear hints pointing to solution
- Common algorithms (Base64, XOR)
- Beginners can solve with basic knowledge
- Expected time: 5-15 minutes

### Medium (100-200 pts)
- Multiple operations in sequence
- Some analysis required
- May need basic reverse engineering
- Intermediate skills needed
- Expected time: 20-45 minutes

### Hard (200-400 pts)
- Complex operation chains
- Significant analysis required
- Reverse engineering necessary
- Advanced techniques
- Expected time: 45-120 minutes

## 🆘 Support

**Need help?**
- Check challenge hints
- Read CyberChef documentation
- Ask in discussions
- Review solution (after trying!)

**Found a bug?**
- Open an issue
- Include challenge number
- Describe the problem
- Include error messages

## 🙏 Credits

**Challenge Authors:**
- Chicken0248 ([@Chicken0248](https://chickenloner.github.io/))

**Powered By:**
- CyberChef by GCHQ
- CyberChef Playground

**Special Thanks:**
- Community contributors
- Beta testers
- Feedback providers

## 🔄 Version History

### v0.0.1 (2026-02-20)
- Initial release
- Complete documentation

---

**Ready to play?** 

```bash
cd /path/to/cyberchef-playground
npm run fetch-challenges
npm start
```

**Start solving and have fun!** 🎯🔐
