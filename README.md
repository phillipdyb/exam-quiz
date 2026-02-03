# Information Security Quiz / Informasjonssikkerhet Quiz

An interactive quiz application for testing knowledge about information security concepts. This quiz is designed to help students and professionals learn and practice essential cybersecurity principles.

## Features

- **50 comprehensive questions** covering key information security topics
- **Multiple quiz modes:**
  - All 50 questions
  - Random selection of 20 questions
  - Random selection of 10 questions
- **Interactive feedback** - immediate validation of answers
- **Progress tracking** - visual progress bar showing quiz completion
- **Answer locking** - prevents changing answers after checking (educational integrity)
- **Score summary** - detailed results at the end with performance emoji
- **Responsive design** - works on desktop, tablet, and mobile devices
- **Norwegian language** interface

## Topics Covered (Sikkerhetsspørsmål)

The quiz covers essential information security concepts including:

- **CIA Triad** (Konfidensialitet, Integritet, Tilgjengelighet)
- **Authentication and Authorization** (Autentisering og Autorisasjon)
- **GDPR and Privacy** (GDPR og Personvern)
- **Threat Landscape** (Trussellandskap)
  - Social Engineering (Sosial manipulering)
  - Phishing and Spear Phishing
  - Zero-day vulnerabilities
  - DDoS attacks
  - Malware and Botnets
- **Security Principles** (Sikkerhetsprinsipper)
  - Least Privilege (Minste privilegium)
  - Data Minimization (Dataminimering)
  - Multi-factor Authentication (MFA)
  - Encryption (Kryptering)
- **Risk Management** (Risikostyring)
- **Incident Handling** (Hendelseshåndtering)
- **Business Continuity** (Resiliens)
  - Backup strategies
  - Recovery procedures

## How to Use

### Online
Simply open the `quiz.html` file in any modern web browser.

### Local Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/infosec-quiz.git
   ```
2. Navigate to the project directory:
   ```bash
   cd infosec-quiz
   ```
3. Open `quiz.html` in your preferred browser:
   ```bash
   open quiz.html  # macOS
   start quiz.html # Windows
   xdg-open quiz.html # Linux
   ```

## Quiz Modes

### All Questions (Alle 50 spørsmål)
Complete all 50 questions in the quiz bank. Ideal for comprehensive review and exam preparation.

### Random 20 (20 tilfeldige)
Practice with a random selection of 20 questions. Great for regular review sessions.

### Random 10 (10 tilfeldige)
Quick practice mode with 10 random questions. Perfect for a brief study session.

## How It Works

1. **Select a quiz mode** from the start screen
2. **Read each question** carefully
3. **Select your answer** by clicking on one of the options
4. **Check your answer** using the "Sjekk svar" button
5. **Review the feedback** - correct answers are highlighted in green, incorrect ones in red
6. **Navigate** using "Forrige" (Previous) and "Neste" (Next) buttons
7. **View your final score** with detailed statistics

## Features in Detail

### Answer Locking
Once you've checked an answer, it cannot be changed - even if you navigate back to that question. This ensures:
- Academic integrity during self-study
- Prevents second-guessing already answered questions
- Encourages thoughtful consideration before submitting

### Visual Feedback
- **Green highlighting** indicates correct answers
- **Red highlighting** shows incorrect selections
- **Explanatory text** displays the correct answer when you make a mistake
- **Progress bar** shows how far you've progressed through the quiz

### Responsive Design
The quiz automatically adapts to different screen sizes:
- Desktop: Full-featured layout with side-by-side navigation
- Tablet: Optimized spacing and touch-friendly buttons
- Mobile: Vertical layout with full-width buttons

## Technical Details

- **Pure HTML/CSS/JavaScript** - no external dependencies
- **Client-side only** - all processing happens in the browser
- **No data collection** - completely private and offline-capable
- **Modern browser support** - works with all current browsers

## Scoring

- **90%+** 🏆 Excellent - Expert level understanding
- **70-89%** 🎉 Good - Solid grasp of concepts
- **50-69%** 👍 Fair - Room for improvement
- **Below 50%** 📚 Study more - Review the material

## Educational Use

This quiz is ideal for:
- **Students** preparing for information security exams
- **Professionals** reviewing cybersecurity fundamentals
- **Training programs** in corporate security awareness
- **Self-study** for security certifications
- **Educators** as a supplementary assessment tool

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

## Contributing

Contributions are welcome! If you'd like to add more questions or improve the quiz:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/new-questions`)
3. Add your questions to the `allQuestions` array in the quiz.html file
4. Follow the existing question format:
   ```javascript
   {
       question: "Your question text?",
       options: ["Option A", "Option B", "Option C", "Option D"],
       correct: 0 // Index of correct answer (0-3)
   }
   ```
5. Commit your changes (`git commit -am 'Add new questions'`)
6. Push to the branch (`git push origin feature/new-questions`)
7. Create a Pull Request

## License

This project is open source and available for educational purposes.

## Acknowledgments

Developed for information security education with focus on Norwegian GDPR compliance and modern cybersecurity practices.

---

**Note:** All questions (Sikkerhetsspørsmål) are in Norwegian as they're designed for Norwegian-speaking students and professionals studying information security.