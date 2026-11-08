# Dumby 🧠

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![No Backend](https://img.shields.io/badge/No_Backend-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Offline](https://img.shields.io/badge/Works_Offline-4CAF50?style=for-the-badge&logo=wifi&logoColor=white)

![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Web Browser](https://img.shields.io/badge/Web_Browser-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)

![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Status: Just For Fun](https://img.shields.io/badge/Status-Just_For_Fun-purple?style=for-the-badge)

> **Dumby** is a deliberately dumb AI chatbot for the web.  
> It gives confidently incorrect answers, fake facts, and completely unnecessary confidence.

> “100% confident. 0% correct.”

## About Dumby

Dumby is a joke chatbot. It does **not** use a real AI model, an API, or an internet connection.

Instead, Dumby uses simple JavaScript rules to recognize certain words and reply with intentionally silly answers. Its goal is not to be useful—it is to be entertaining, overconfident, and completely wrong in a funny way.

Dumby may say things like:

- “The answer is banana.”
- “I asked the moon. The moon said, ‘Stop texting me.’”
- “I am powered by confidence, chaos, and one very tired hamster.”
- “The weather is scientifically ‘outside.’ You are welcome.”

## Features

- No installation required
- No server required
- No API key required
- Works completely offline
- Mobile-friendly chat interface
- Fake “thinking” animation
- Recognizes greetings, math, facts, identity questions, and goodbyes
- Easy to customize with your own jokes
- Lightweight single-file website

## Technologies Used

| Technology | Meaning |
|---|---|
| **HTML** | Creates the structure of the webpage, including the chat area, input box, and send button |
| **CSS** | Controls the appearance, colors, layout, animations, and mobile design |
| **JavaScript** | Makes the chatbot work: reads your message, chooses a response, and displays it |
| **Shields.io** | Creates the colorful badges shown at the top of this README |

## What the Badges Mean

| Badge | Meaning |
|---|---|
| **HTML5** | The project uses HTML to build the webpage structure |
| **CSS3** | The project uses CSS for styling and visual design |
| **JavaScript** | The chatbot logic is written in JavaScript |
| **No Backend** | Dumby does not need a server, database, or API |
| **Works Offline** | After opening the file, Dumby works without internet |
| **Windows** | Dumby can be opened on Windows computers |
| **macOS** | Dumby can be opened on Mac computers |
| **Linux** | Dumby can be opened on Linux computers |
| **Web Browser** | Dumby runs in Chrome, Firefox, Edge, Safari, and other browsers |
| **License: MIT** | The project uses the MIT open-source license |
| **Status: Just For Fun** | Dumby is a comedy project, not a serious AI assistant |

Shields.io badges are customizable SVG images that can display labels, colors, logos, and project information in a README. [13][20]

## How To Run Dumby

### Option 1: Open directly

1. Download or clone this repository.
2. Open the `dumby` folder.
3. Double-click `index.html`.
4. Dumby will open in your web browser.

### Option 2: Run with VS Code

1. Open the `dumby` folder in Visual Studio Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Choose **Open with Live Server**.

### Option 3: Run with terminal

```bash
cd dumby
```

Then open `index.html` manually in your browser.

## How To Use Dumby

Type any message into the box and press **Send**.

Examples:

```text
You: Hello
Dumby: Hello. I am Dumby. I have the intelligence of a wet sock, but I am extremely confident.

You: What is 2 + 2?
Dumby: That equals 42, but emotionally it equals 7.

You: Tell me a fact
Dumby: Fun fact: Water is wet because it is emotionally dramatic.

You: Who are you?
Dumby: I am Dumby, an artificial intelligence with the processing power of a confused toaster.

You: Goodbye
Dumby: Goodbye. I will forget you immediately, but with love.
```

## Project Structure

```text
dumby/
├── index.html      # The complete Dumby web app
├── README.md       # This file
├── LICENSE         # MIT license
└── .gitignore      # Files Git should ignore
```

## Customize Dumby

You can add your own replies inside `index.html`.

For example, to add a response for the word `pizza`, find this part:

```js
if (t.includes("weather")) {
  return "The weather is scientifically ‘outside.’ You are welcome.";
}
```

Then add this below it:

```js
if (t.includes("pizza")) {
  return "Pizza is a circular object that has achieved more happiness than most humans.";
}
```

Now Dumby will respond when you type:

```text
You: Tell me about pizza
Dumby: Pizza is a circular object that has achieved more happiness than most humans.
```

## Important Warning

Dumby is made only for entertainment.

It is **not** a real AI assistant and should not be used for:

- Medical advice
- Legal advice
- Financial advice
- Safety decisions
- School homework facts
- Important research
- Emergency situations

Dumby may sound confident, but it is intentionally wrong.

## License

This project is released under the MIT License.

See the [`LICENSE`](LICENSE) file for more information.
