# 🔍 WeHack 0.0 - Murder Mystery Investigation Game

![Crime Scene Tape](https://img.shields.io/badge/Status-Crime%20Scene-red?style=for-the-badge)
![IEEE FSM](https://img.shields.io/badge/IEEE-FSM-blue?style=for-the-badge)
![Investigation](https://img.shields.io/badge/Type-Murder%20Mystery-darkred?style=for-the-badge)

## 📖 Overview

**WeHack 0.0** is an interactive murder mystery investigation game where players navigate through multiple digital platforms to solve a double homicide case. Two IEEE FSM EXCOM members are dead, one person is in jail, but the truth is hidden in encrypted files, surveillance footage, and digital evidence.

**Duration:** 60-90 minutes  
**Players:** 2-6 (team-based)  
**Difficulty:** Advanced  
**Skills Required:** Cryptography, Digital Forensics, Timeline Analysis

---

## 🎭 The Story

### The Victims
- **Aziz Krifa** (22) - IEEE Student Branch Chair  
  Found dead December 11, 2025 at his apartment building
  
- **Ela Hassine** (21) - IEEE Treasurer  
  Found dead December 14, 2025 at the IEEE office

### The Accused
- **Amine Zbaa** - CS Vice Chair, arrested for Ela's murder  
  Claims he was framed with fabricated evidence

### Your Mission
Investigate digital evidence across 6 platforms to determine:
- Who killed Aziz Krifa?
- Who killed Ela Hassine?
- Who is lying?
- Who was framed?
- What evidence is forged?

---

## 🎮 How to Play

### Setup
1. Open `index.html` in a web browser
2. Click "BEGIN INVESTIGATION"
3. Work as a team - one person navigates, everyone analyzes

### Game Flow
1. **Start** → Read the initial clue about Roua's leaked password
2. **Messenger** → Login with Roua's password to find the Vigenère cipher
3. **Decrypt** → Solve the cipher to get the IEEE Portal password
4. **Investigate** → Navigate through all platforms collecting evidence
5. **Analyze** → Cross-reference evidence across platforms
6. **Solve** → Submit your conclusions on the Evidence Board

### Key Mechanics
- **No hints** - All clues must be discovered naturally
- **Cryptography puzzle** - Vigenère cipher decryption required
- **Timeline analysis** - Cross-reference dates and times
- **Digital forensics** - Server logs, CCTV footage, metadata
- **Critical thinking** - Identify forged evidence

---

## 🗂️ Available Platforms

### 1. 💬 **Social Network (Messenger)**
- Access private conversations between suspects
- Multiple user accounts to investigate
- Critical clues hidden in conversations
- **Access:** Login required - find credentials through investigation

### 2. 📁 **IEEE Portal**
- Internal document management system
- Meeting minutes and reports
- Financial records
- **Access:** Password-protected (must be discovered)

### 3. 🚓 **Police Database**
- Official case files and forensic reports
- Witness statements
- Evidence documentation
- **Access:** Search by case number

### 4. 📹 **Security System**
- CCTV footage from multiple locations
- Access logs and timestamps
- Multi-camera surveillance
- **Access:** Security code required

### 5. 💻 **Server Admin Panel**
- System access logs
- User activity records
- Technical evidence
- **Access:** Administrator credentials needed

### 6. 📊 **Evidence Board**
- Organize your findings
- Submit final conclusions
- Receive scoring and feedback

---

## 🔑 Getting Started

### First Steps
The game begins with a hint about **Roua Mabrouk's** leaked password. Use this to access the messenger platform and begin your investigation.

### Discovery-Based Progression
All other access credentials must be discovered through investigation:
- Passwords are hidden in conversations
- Access codes are found in evidence
- Case numbers are shared between characters
- Each platform unlocks clues for the next

**No spoilers here - discover them yourself!**

---

## 🧩 Investigation Flow

### Getting Started
1. Open `index.html` in a web browser
2. Click "BEGIN INVESTIGATION" 
3. Read the opening clue carefully
4. Use the provided information to access your first platform

### Investigation Process
1. **Explore Platforms** - Navigate through available digital systems
2. **Find Clues** - Look for passwords, case numbers, and access codes
3. **Decrypt Puzzles** - Solve cryptographic challenges
4. **Cross-Reference** - Compare evidence across platforms
5. **Build Timeline** - Reconstruct the sequence of events
6. **Identify Contradictions** - Find inconsistencies and forgeries
7. **Submit Solution** - Present your conclusions

### Key Investigation Tips
- Read conversations thoroughly
- Note all dates and timestamps
- Look for technical terms and methods mentioned
- Check metadata and logs carefully
- Question the authenticity of evidence
- Work systematically through each platform

---

## 📂 File Structure

```
wehack-0.0/
├── index.html              # Main landing page
├── messenger.html          # Social network platform
├── ieee-portal.html        # Document management system
├── police-database.html    # Police records database
├── security-system.html    # CCTV footage viewer
├── server-admin.html       # Server logs (smoking gun)
├── evidence-board.html     # Answer submission
├── solution.html           # Complete solution reveal
└── README.md              # This file
```

---

## 🎓 Educational Value

This game teaches:
- **Cryptography:** Vigenère cipher decryption
- **Digital Forensics:** Log analysis, metadata examination
- **Critical Thinking:** Evidence evaluation, bias recognition
- **Timeline Analysis:** Cross-referencing events across sources
- **Cybersecurity:** Understanding how evidence can be forged
- **Team Collaboration:** Working together to solve complex problems

---

## 🛠️ Technical Details

### Technologies Used
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Design:** Responsive, mobile-friendly interface
- **Storage:** All data stored in JavaScript objects (no backend)
- **Compatibility:** Works in all modern browsers

### Features
- No external dependencies
- Completely offline playable
- Self-contained single files
- No installation required
- Cross-platform compatible

---

## 🎯 Tips for Game Masters

### Running the Game
1. **Preparation:** Familiarize yourself with the solution first
2. **Team Size:** 3-4 players is optimal
3. **Time Limit:** Set 60-90 minutes for full experience
4. **Environment:** Quiet space with projector or shared screen

### Helping Stuck Players
- Encourage re-reading evidence carefully
- Suggest cross-referencing timestamps across platforms
- Remind them to check all available platforms
- Hint toward specific platforms without giving answers
- Encourage team discussion and collaboration

### Difficulty Adjustments
**Make Easier:**
- Provide Vigenère cipher decoder link upfront
- Give direct hints to platform passwords
- Reduce number of platforms to investigate

**Make Harder:**
- Remove starting password hint (make players find it)
- Add time pressure
- Require written evidence documentation
- Add red herring documents

---

## 🏆 Scoring System

The Evidence Board automatically scores submissions:

- **Aziz's killer + death type:** 15 points
- **Ela's killer:** 20 points
- **The Liar:** 15 points
- **The Decoy:** 15 points
- **Forged Evidence:** 10 points
- **Who goes to prison:** 10 points

**Total:** 85 points

- **85 points:** Perfect! 🏆
- **60-84 points:** Good job! ⭐
- **Below 60:** Review evidence 📚

---

## 📝 Credits

**Game Design & Development:** WeHack 0.0 Team  
**Story:** Original narrative  
**Institution:** IEEE FSM - Faculty of Science of Monastir  
**Purpose:** Educational murder mystery for cybersecurity event

---

## ⚖️ Legal Notice

This is a **fictional game** for educational purposes only.

- All characters are fictional
- All events are fictional  
- Faculty of Science of Monastir is a real institution but the story is entirely made up
- No real cases or individuals are referenced
- Created for WeHack 0.0 educational event

---

## 🐛 Known Issues

### Minor Issues
1. **Messenger passwords:** Some accounts have complex passwords not required for solving
2. **Character names:** Minor last name variations in supporting characters (cosmetic only)

### Critical Issue (Awaiting Fix)
- ❌ **Timeline error:** Roua-Aziz password conversation dated Dec 12 (should be Dec 8/9)
  - Does not affect solvability but creates logical inconsistency
  - Aziz cannot message after his death on Dec 10

---

## 🔄 Version History

**v1.0** (Current)
- Initial release
- 6 interactive platforms
- Full story implementation
- Vigenère cipher puzzle
- Complete evidence chain

---

## 📧 Contact & Support

**For Issues or Questions:**
- Report bugs via issue tracker
- Contact WeHack 0.0 organizers
- Check solution guide if stuck

**For Feedback:**
- We'd love to hear about your experience!
- Suggestions for improvements welcome
- Share your solve time and team size

---

## 🎉 Have Fun Investigating!

Remember:
- 🔍 **Pay attention to details**
- 🕐 **Cross-reference timestamps**
- 🤝 **Work together as a team**
- 💡 **Question everything**
- 🎯 **Trust the evidence, not assumptions**

**Good luck, detectives!** 🔎

---

*"The truth is rarely pure and never simple." - Oscar Wilde*
