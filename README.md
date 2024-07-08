# 🚀 Parcel tracker

## ✨ Contributors

<table width="100%">
  <tr>
    <td align="center" style="word-wrap: break-word; width: 100; height: 100">
      <a href="https://github.com/stxreocoma" style="text-decoration: none;">
        <img
          src="https://avatars.githubusercontent.com/u/164244607?v=4"
          width="100;"
          alt="Vvedensky G"/>
        <br />
        <sub style="font-size:13px"><b>Vvedensky&nbsp;Gleb</b></sub>
      </a>
    </td>
  </tr>
</table>

<h2 align="left" id='tech-stack'>🔥 Tech Stack</h2>

>General
<table width="100%">
  <tr>
    <td align="center" width="110" height="90">
      <a href="#tech-stack">
        <img
          src="https://raw.githubusercontent.com/devicons/devicon/6910f0503efdd315c8f9b858234310c06e04d9c0/icons/go/go-original-wordmark.svg"
          width="36"
          height="36"
          alt="Go"
        />
      </a>
      <br>React
    </td>
  </tr>
</table>

> Code quality

<table width='100%'>
  <tr>
    <td align="center" width="110" height="90">
      <a href="#tech-stack">
        <img
          src="https://brandeps.com/icon-download/E/Eslint-icon-vector-02.svg"
          width="36"
          height="36"
          alt="eslint"
        />
      </a>
      <br>ESlint
    </td>
    <td align="center" width="110" height="90">
      <a href="#tech-stack">
        <img src="https://brandeps.com/icon-download/P/Prettier-icon-vector-02.svg" width="36" height="36" alt="prettier" />
      </a>
      <br>Prettier
    </td>
        <td align="center" width="110" height="90">
      <a href="#tech-stack">
        <img src="https://brandeps.com/logo-download/S/Stylelint-logo-vector-01.svg" width="36" height="36" alt="Prettier" />
      </a>
      <br>Stylelint
    </td>
  </tr>
</table>

<h2>🏗️ Project Structure:</h2>

```Bash
├── public/            # Source folder with favicons
├── src/               # Source files of the project
│   ├── components/    # Folder with TS components
│   ├── styles/        # Folder with CSS styles
│   ├── main.tsx       # Entry point of the application
│   └── index.css      # Root style file
├── index.html         # HTML file of the main page
├── SECURITY.md        # File with security policy
└── README.md          # README file with documentation
```

<h2>📁 Installation and Running</h2>

<h3>To install and run the project, execute the following commands</h3>

```Bash
npm install
npm run dev
```

<h3>Building</h3>

```Bash
npm run build
```

<h2>📚 Description of basic classes</h2>

### BogoSort Component

The `BogoSort` component manages the state and functionality for performing the Bogo Sort algorithm.

#### Properties:

- **items**: An array of numbers representing the items to be sorted.
- **sorted**: A boolean indicating whether the items are currently sorted in ascending order.
- **itemCount**: An integer representing the total number of items in the array.
- **sorting**: A boolean flag indicating whether the sorting process is currently in progress.

#### Functionality:

The `BogoSort` component utilizes these properties to display the current state of the sorting process and allows users to initiate the sorting algorithm when desired.
