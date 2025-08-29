project:
  name: "Wahh..Chef"
  description: >
    Wahh..Chef is an AI-powered recipe generator that transforms your ingredients into delicious dishes.
    Just enter the ingredients you have, and our AI will:
      - Fetch detailed ingredient insights using APIs
      - Generate step-by-step recipe cards with cooking instructions
      - Provide YouTube video links for guided tutorials
      - Allow you to share recipes or download them as PNGs for easy storage and social sharing
  icon: "🍳"

features:
  - name: "Smart Ingredient Analysis"
    description: "Enter ingredients and let AI suggest possible dishes"
    emoji: "🥗"
  - name: "Recipe Cards"
    description: "Beautifully designed, step-by-step recipe cards"
    emoji: "📖"
  - name: "YouTube Guides"
    description: "Embedded video tutorials for hands-on cooking"
    emoji: "🎥"
  - name: "Social Sharing"
    description: "Share recipes instantly across platforms"
    emoji: "📤"
  - name: "Download as PNG"
    description: "Save recipe cards to your device"
    emoji: "📸"

tech_stack:
  frontend: ["React.js", "Next.js"]
  backend: ["Node.js", "Express"]
  database: ["MongoDB", "Firebase (optional)"]
  ai_and_apis: ["OpenAI API", "Recipe API"]
  tools: ["Cloudinary", "HTML2Canvas", "Puppeteer"]

installation:
  steps:
    - step: "Clone the repository"
      command: |
        git clone https://github.com/yourusername/wahh-chef.git
        cd wahh-chef
    - step: "Install dependencies"
      command: "npm install"
    - step: "Set up environment variables"
      file: ".env"
      variables:
        - API_KEY=your_api_key_here
        - OPENAI_KEY=your_openai_key_here
    - step: "Run the development server"
      command: "npm run dev"
    - step: "Visit in browser"
      url: "http://localhost:3000"

screenshots:
  note: "Add screenshots of the recipe cards, video integration, and PNG downloads here."
  paths: []

roadmap:
  - "Multi-language support"
  - "Personalized diet-based suggestions (vegan, keto, etc.)"
  - "Save recipes to user profiles"
  - "Mobile app integration"

contributing:
  steps:
    - "Fork the repo"
    - "Create your branch (git checkout -b feature-name)"
    - "Commit changes (git commit -m 'Add feature')"
    - "Push to branch (git push origin feature-name)"
    - "Create a Pull Request"

license:
  type: "MIT License"
  file: "LICENSE"

about:
  summary: >
    Wahh..Chef is your AI-powered kitchen buddy — from pantry to plate, it helps you cook smarter, not harder.
    Whether you’re a beginner or a master chef, it makes cooking fun, accessible, and shareable.
