# Rick & Morty Wiki

A dynamic React application that serves as a wiki for the popular animated series "Rick and Morty". This project fetches data from the [Rick and Morty API](https://rickandmortyapi.com/) to display comprehensive information about characters, episodes, and locations.

## Features

- **Character Directory**: Browse through the extensive list of characters from the show.
- **Advanced Search & Filtering**:
  - Search for characters by name.
  - Filter results by Status (Alive, Dead, Unknown), Gender, and Species.
- **Episode Guide**: View details for specific episodes and see which characters appeared in them.
- **Location Explorer**: Discover different locations from the multiverse and view their residents.
- **Detailed Views**: Click on any character to view in-depth details.
- **Responsive Design**: Built with Bootstrap for a seamless experience across devices.

## Tech Stack

- **Frontend Library**: [React.js](https://reactjs.org/)
- **Routing**: [React Router](https://reactrouter.com/)
- **Styling**: [Bootstrap](https://getbootstrap.com/) & CSS
- **Data Source**: [Rick and Morty API](https://rickandmortyapi.com/)

## Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Books-beats/Rick-Morty.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Rick-Morty
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

### Running the Application

In the project directory, you can run:

```bash
npm start
```

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

## Project Structure

- `src/components`: Reusable UI components like Cards, Navbar, Search, and Filters.
- `src/Pages`: Main page views including Episodes and Location.
- `src/App.js`: Main application component handling routing and layout.


