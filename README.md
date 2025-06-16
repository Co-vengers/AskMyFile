# AskMyFile

AskMyFile is a modern, enterprise-grade Streamlit app that lets you upload and analyze multiple document types (CSV, Excel, PDF, DOC, TXT, images) using advanced AI (meta-llama/Llama-4-Maverick-17B-128E-Instruct-FP8 via Together.ai). The app answers questions about your data, supports follow-up queries, and generates visual graphs—all with a beautiful, responsive UI.

---

## Features

- **Multi-file Upload:** Supports `.csv`, `.xlsx`, `.txt`, `.doc`, `.pdf`, `.png`, `.jpg`, `.jpeg`.
- **AI-Powered Q&A:** Analyze and ask questions about your files using Llama-4 Maverick via Together.ai.
- **Visualizations:** Generate bar, line, scatter, and histogram charts from your data.
- **Modern UI:** Glassmorphism, Material Design icons, theme switching, notifications, and more.
- **Accessibility:** Keyboard navigation, responsive design for mobile/tablet/desktop.
- **Data Persistence:** Keeps your session data and chat history.
- **Error Handling:** Advanced error messages and user feedback.
- **Branding:** Custom logo and footer.

---

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/Co-vengers/AskMyFile
cd data-analyst-agent
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Add your Together.ai API key

Create a `.env` file in the project root:

```
TOGETHER_API_KEY=your_together_api_key_here
```

### 4. Add your logo

Place your logo image at:  
`src/assets/logo.png`

---

## Running the App

```bash
streamlit run src/app.py
```

---

## Usage

1. Upload one or more files using the sidebar.
2. Ask questions about your data in the chat interface.
3. Request visualizations (e.g., "Show me a bar chart of sales by region").
4. Switch between light/dark themes as you like.

---

## Tech Stack

- **Frontend:** [Streamlit](https://streamlit.io/)
- **AI Model:** [meta-llama/Llama-4-Maverick-17B-128E-Instruct-FP8](https://www.together.ai/)
- **Visualization:** Seaborn, Matplotlib
- **Icons:** [Google Material Icons](https://fonts.google.com/icons)
- **Design:** Glassmorphism, responsive CSS

---

## Accessibility & Responsiveness

- Fully keyboard navigable
- Works on mobile, tablet, and desktop
- Uses accessible color schemes and alt text

---

## License

MIT License

---

## Credits

- Built with ❤️ using Streamlit and