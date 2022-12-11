# Job Tracker

Track the progress of your job applications. This is a Code.Sydney side-project where all contributions are welcome.

## About Code.Sydney

Code.Sydney is a volunteering organisation that supports beginner developers transition to paid employment whilst primarily helping non-profit and charity organisations.

## Tech Stack

- TypeScript
- Next.js
- React
- TailwindCSS
- Prisma
- PostgreSQL

## Getting Started

### Cloning the Project

![image](https://user-images.githubusercontent.com/8443215/206170976-b7e1ef6d-b371-4dbc-9332-56791c56ceb0.png)

Click on the green `<> Code` button on this page and follow the instructions to clone this repository.

### Install Dependencies

Once the project is cloned, you'll want to open the project in VS Code or a terminal.

Run the following command to install the npm dependencies.

```bash
npm install
```

### Running the Development Server

To get the development server up and running.

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Running Jest Tests

```bash
# run tests
npm run test

# run tests in watch mode
npm run test:watch
```

## Database Schema

![untitled (3)](https://user-images.githubusercontent.com/8443215/206895369-73715c30-bcae-4958-a0c9-b463801b8587.png)

Note: A BLOB database would be better suited to store the Job Description text. But since I want to keep the project simple for the Code.Sydney members, we'll use a local PostgreSQL DB
