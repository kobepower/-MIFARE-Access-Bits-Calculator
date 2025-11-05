# -MIFARE-Access-Bits-Calculator
MIFARE Access Bits Calculator Decodes and analyzes MIFARE Classic access conditions from Proxmark3 dumps.  **Features:** ✅ Supports all MIFARE Classic variants (Mini/1K/4K/8K) ✅ Reads multiple dump formats (.bin, .mfd, .eml, .txt, .hex) 
### 2️⃣ MIFARE Access Bits Calculator
Decodes and analyzes MIFARE Classic access conditions from Proxmark3 dumps.

**What it does:**
- ✅ Supports all MIFARE variants (Mini/1K/4K/8K)
- ✅ Reads all dump formats (.bin, .mfd, .eml, .txt, .hex)
- ✅ Decodes C1, C2, C3 access bits
- ✅ Shows Read/Write/Increment/Decrement permissions
- ✅ Detects Key B readability vulnerability
- ✅ Works with large sectors (256-byte)

**Usage:**
```matlab
mifare_access_bits_calculator2
% Select dump file when prompted
```

**Example Output:**
```
=== Sector 0 ===
Key A: FFFFFFFFFFFF
Access Bytes: FF 07 80

Block 0: transport configuration
  Read: Key A or B
  Write: Key A or B
  
⚠️ Key B is readable - cannot authenticate!
```

---

## 🎯 Use Cases

**For Security Researchers:**
- Audit building access control systems
- Test RF remote cloning feasibility
- Analyze RFID card vulnerabilities
- Generate professional security reports

**For Locksmiths:**
- Quickly determine if remotes are clonable
- Analyze customer RFID cards
- Provide expert explanations to clients

**For Students:**
