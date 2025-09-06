# 🔡 Morse Decoder (Bash)

A lightweight **Bash-based Morse Code Decoder** that transforms Morse code into human-readable text.  
Supports **letters**, **digits**, **punctuation**, and proper word separation! 🚀

---

## ✨ Features

- Decode **A–Z** letters  
- Decode **0–9** digits  
- Decode special characters: `.,?!/()&:;=+-_@"`  
- Word separation with `/` → real spaces  
- Fast & dependency-free – pure **Bash**

---

## 🖥️ Usage

1. **Clone the repo**  
   ```bash
   git clone https://github.com/Gkakad2/morse-decoder-bash.git
   cd morse-decoder-bash

2. Make the script executable

chmod +x morse_code.sh


3. Run the script

./morse_code.sh


4. Enter Morse code when prompted (separate letters with spaces, words with /):

Enter the morse code: .... . .-.. .-.. --- / .-- --- .-. .-.. -..


Output:

HELLO WORLD

➡️ Digits 0–9 and symbols like . , ? ! / ( ) & : ; = + - _ " @ are all supported.

🧪 Example Messages

SOS → ... --- ...

HELP → .... . .-.. .--.

LOVE → .-.. --- ...- .

HELLO WORLD → .... . .-.. .-.. --- / .-- --- .-. .-.. -..

🛠️ Tech Stack

Bash

Works on Linux & macOS terminal

🚀 Future Improvements

Add encoding (text → Morse)

Better error handling for invalid inputs

Live/streaming translation

🤝 Contributing

Want to make it better? Fork the repo, open issues, or submit PRs.
Collaboration is always welcome!

📜 License

Licensed under the MIT License – free to use, modify, and share.

💙 With love, from Gayatri
