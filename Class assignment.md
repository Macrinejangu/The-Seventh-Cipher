# The Seventh Cipher - HTML Assignment Plan

## Project Overview

A fictional secret society site 
The society is called **The Seventh Cipher** - a cryptic, intellectual secret society
open to hackers, scholars, detectives, and gifted students.

All three pages will be linked to each other via a navigation bar using anchor tags.

---

## Page 1 - Home Page (index.html)

**Purpose:** Welcome visitors and introduce the society.

**Navigation Bar**
- Links to all three pages: Home, Member Portal, Archives
- Built with anchor tags pointing to index.html, portal.html, archives.html

**Hero Section**
- Society name: The Seventh Cipher
- Tagline: "Knowledge is the only cipher worth cracking."
- A "Request Access" button that links to portal.html
- One large hero image (dark, mysterious - a crest or symbol)

**About Section**
- A short paragraph about the society's origins and purpose
- One image beside the text (ancient manuscript or code visual)

**Our Pillars Section**
- Three cards: Cryptography, Intelligence, Brotherhood
- Each card has a small image representing the pillar

**Who We Accept Section**
- Brief description of the four member types
  - Hackers
  - Scholars
  - Detectives
  - Gifted Students
- One image accompanying the section

**Join Us Section**
- A short call to action paragraph
- A button linking to portal.html

**HTML tags used on this page**
- html, head, body, title
- nav, a (anchor links between pages)
- header, section, div, p
- h1, h2, h3
- img (with src and alt attributes)
- button

---

## Page 2 - Member Portal (portal.html)

**Purpose:** Showcase HTML input types inside a login and registration form.

**Navigation Bar**
- Same nav as the home page, linking all three pages

**Page Heading**
- Title: "Member Portal"
- Subtitle: "Access is earned. Identify yourself."

**Form - Member Login and Registration**

The form will include the following input types:

| Input Type | Field Label | Notes |
|---|---|---|
| text | Full Name | Placeholder text included |
| email | Email Address | For login |
| password | Password | For login |
| password | Confirm Password | Registration only |
| number | Agent ID Number | Numeric only |
| tel | Phone Number | Contact number |
| date | Date of Birth | Member verification |
| time | Preferred Contact Time | Optional field |
| url | Personal Portfolio URL | Optional link |
| file | Upload Proof of Identity | File upload input |
| range | Skill Level (1 to 10) | Slider input |
| color | Choose Your Cipher Color | Color picker |
| radio | Membership Type | Options: Scholar, Hacker, Detective, Gifted |
| checkbox | Areas of Interest | Options: Cryptography, Intelligence Ops, Field Work, Research |
| checkbox | I agree to the Code of Silence | Required agreement |
| select (dropdown) | Country of Origin | Dropdown list |
| textarea | Why do you want to join? | Multi-line text input |
| hidden | referral_source | Hidden field, value set to "website" |
| submit | Submit Application | Submit button |
| reset | Clear Form | Reset button |

**HTML tags used on this page**
- form, input (all types listed above)
- label (paired with every input using for and id)
- select, option
- textarea
- button (type submit and type reset)
- fieldset, legend (to group related inputs)
- nav, a, h1, h2, p, div

---

## Page 3 - Archives (archives.html)

**Purpose:** Display society data using HTML tables and lists.

**Navigation Bar**
- Same nav linking all three pages

**Page Heading**
- Title: "The Archives"
- Subtitle: "All records are classified. Handle with discretion."

**Table 1 - Members Registry**

Columns: Member Name, Rank, Specialty, Status

Sample rows:
- Cipher Zero, Grand Archivist, Cryptography, Active
- Agent Voss, Field Operative, Intelligence, Active
- Dr. Elara Nyx, Scholar Prime, Research, Inactive
- Kade Mercer, Infiltrator, Hacking, Active
- Sable Orin, Analyst, Data Decryption, Active

**Table 2 - Cipher Missions Log**

Columns: Mission Name, Difficulty, Date Assigned, Lead Agent, Outcome

Sample rows:
- Operation Hollow Key, High, 2024-01-15, Cipher Zero, Success
- The Raven Protocol, Critical, 2024-03-02, Agent Voss, Ongoing
- Project Dusk Signal, Medium, 2024-05-18, Kade Mercer, Success
- Enigma Threadfall, High, 2024-07-30, Dr. Elara Nyx, Failed
- The Obsidian Drop, Low, 2024-09-11, Sable Orin, Success

**Table 3 - Cipher Arsenal**

Columns: Tool Name, Type, Clearance Level Required

Sample rows:
- Phantom Decoder, Software, Level 3
- ShadowKey Device, Hardware, Level 5
- Encrypted Relay Node, Network Tool, Level 4
- The Black Ledger, Document, Level 2
- Neural Cipher Lens, Field Equipment, Level 5

**Unordered List - House Rules of The Seventh Cipher**
- Never reveal your membership to outsiders
- All communications must be encrypted
- Missions are assigned, never requested
- Loyalty to the cipher comes before all else
- Archives are read only, never altered

**Ordered List - Steps to Decode a Cipher**
1. Identify the cipher type (Caesar, Vigenere, Binary, etc.)
2. Gather all available encoded fragments
3. Apply the known key or begin frequency analysis
4. Cross reference with the society archives
5. Document your findings and submit to the Grand Archivist

**HTML tags used on this page**
- table, thead, tbody, tr, th, td
- ul, ol, li
- nav, a, h1, h2, h3, p, div

---

## File Structure

```
seventh-cipher/
- index.html        (Home Page)
- portal.html       (Member Portal - Login and Registration)
- archives.html     (Archives - Tables and Lists)
```

## Navigation Links Between Pages

Each page has a nav bar at the top with these three links:

- Home → index.html
- Member Portal → portal.html
- Archives → archives.html

All links use the HTML anchor tag with an href attribute pointing to the correct file name.
