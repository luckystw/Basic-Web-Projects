# Basic Web Projects

A collection of small, beginner-friendly web projects built to practice the fundamentals of front-end development. Each project lives in its own folder and can be opened and run on its own, with no build step or installation.

## Projects

| Project | Description |
|---------|-------------|
| [Landing page](./Landing%20page) | A simple landing page that practices page layout, styling and responsive design. |
| [Stopwatch](./Stopwatch) | A stopwatch with start, stop and reset controls, built around timers and DOM updates. |
| [Tic-Tac-Toe](./Tic-Tac-Toe) | A two-player Tic-Tac-Toe game with win and draw detection. |
| [Weather](./Weather) | A weather app that shows the current conditions for a location. |

## Tech Stack

- HTML5
- CSS3
- JavaScript (vanilla)

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge or Safari)
- [Git](https://git-scm.com/) (optional, only needed to clone the repo)

### Run a project locally

1. Clone the repository:

   ```bash
   git clone https://github.com/luckystw/Basic-Web-Projects.git
   cd Basic-Web-Projects
   ```

2. Open the project you want to try:

   ```bash
   cd Stopwatch
   ```

3. Open `index.html` in your browser by double-clicking it, or serve the folder locally:

   ```bash
   # Python 3
   python -m http.server 8000
   ```

   Then visit `http://localhost:8000`.

> **Note for the Weather app:** weather apps usually call an external API. If this one needs an API key, add your own key where the code asks for it, and never commit a real key to a public repository.

## Repository Structure

```
Basic-Web-Projects/
├── Landing page/
├── Stopwatch/
├── Tic-Tac-Toe/
├── Weather/
└── README.md
```

## What I Practiced

- Structuring pages with semantic HTML
- Styling and layout with CSS (flexbox and grid)
- Handling events and updating the DOM with JavaScript
- Managing game state and application logic
- Fetching and displaying data from an API

## Future Improvements

- Add screenshots or live demos for each project
- Make every project fully responsive
- Add a high-score or history feature to the games
- Store the last searched city in the Weather app

## Contributing

Suggestions and improvements are welcome. To contribute:

1. Fork the repository
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push the branch: `git push origin feature/your-feature`
5. Open a pull request

## License

No license has been specified yet. Consider adding one, such as the [MIT License](https://choosealicense.com/licenses/mit/), if you want others to reuse this code.
